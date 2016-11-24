---
layout: post
title:  "Why Powershell Build?"
date:   2016-11-25 23:00:00 +0800
categories: .Net Powershell Build vsts visualstudio
---

Hello, recently I was working to manage building complex and different types of .Net/Azure Cloud Service/Azure Web Apps/Windows Services projects to be hosted by Azure and on premises servers.
The release management solutions were different as well, some of projects are managed by Octupus Delopy and other were managed by Visual Studio Release Management.

The old builds were Visual Stuido Online (VSO) XAML builds, and I should transform them to vNext build and the question that came to my mind, should I use VSTS tasks or use a custom powershell build such as psake or cake?
For the first look, I found that VSTS tasks-based build is very comperhensive and cover most of the job so I started to use it. But after a couple of builds, I found it's very hard to customize it. So I started to move my head around to fix the issues.
On that day, I went to my home and felt bad and upset because I sepnt too much time trying to customize VSTS tasks-based build and it should be a smarter way to do it. I couldn't resist to give the powershell build (psake) a try.
So I finished my dinner and started to investigate in powershell build. In a couple of hours, I managed to build a custom psake build that do all the job for me with less headache.
So, I started to use it. Now, In a couple of days I have done around 10 fully customzied psake builds. The build proceess that took from me hours to build, now takes only maximum one hour to finish or maybe less.

So, for everyone who is asking or still hesitated about powershell-based build, I encourage you to go and give it a try for many reasons. 
I will illustrate my two cents about powershell-based build:

1. You have the ability to test your build steps locally. That is the greatest thing, you can test your GitVersion config, different build targets and configuration. In VSTS tasks-based build, you have to push a branch and maybe merge it to see the results and fix it in another branch which is not a convienent thing.

2. All your build scripts and processes are version-controlled. You can see the history and manage them easily better than to be steps you or someone else delete/edit it without a fully managed version control. I know that VSTS gives you the ability to see the history of the build process and see the differences but it is not like the great Git.

3. You have the full power to do whatever you want without getting an approval to install a task in VSTS which the project owner may refuse to install. You can copy files, transform xml, build, publish, deploy and create the best suitable packages according to your solution/set up. In VSTS, you have these put limited to the API exposed to you by the task such as MSBuild step.

4. You have the ability to do things that are not applicable in VSTS task, such as smashing many MSBuilds in one script which will be one task in VSTS. Actually, maybe it is not a great thing but it was an issue for me which psake solved it in a couple of lines.

5. That gives you the ability to create many different packages in one build and helps the Release Management to deploy the right package into the right environemnt. That was a great thing to do and helped me a lot in doing MSBuild for the solution and then build and package for a ccproj to create two Azure cloud services in one shot with two different configurations.

These are such a great benefits but not all. You should have more problems solved when you start using the powershell-based build instead of relying on VSTS tasks.

Hope that cover most of the issues you would face in building a customized solutions.

Happy to help and discuss that if you have any issue. 