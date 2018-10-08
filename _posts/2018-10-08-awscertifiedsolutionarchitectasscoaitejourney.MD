---
layout: post
title: "My journey to AWS Certified Solutions Architect - Associate"
date: 2018-10-8 16:00:00 +0800
categories: aws amazon web services certification acloudguru readify professional development
---

Following my announcement with my journey towards getting AWS Certified Solutions Architect - Associate (Feb 2018 version) certification, I received numerous requests to share my experience with AWS and how I successfully managed to pass it from the first time with little experience.

# A bit of history

First a bit of my background, I'm Mo who works with [Readify](https://readify.net/) as a Senior Software Consultant. I have more than 12 years diverse experience with many technologies including Azure. I have good cloud knowledge but AWS wasn't my thing before I started looking into it in 2016 as part of my professional development. I have a little AWS experience from many online courses and local Meetups sessions.

# My journey

## A Cloud Guru

I started looking into AWS certifications and planning to do it only two month ago (late July 2018). I started with doing my research  to look into AWS and found that the Ozzy guy Ryan Kroonenburg crafted perfect courses that target the AWS certificates on [A Cloud Guru](https://acloud.guru/). 
The course is 22 hours of videos that are focused on the certification. I took me around 50 hours to run through the whole videos, writing my side notes and doing most of the labs.  

My thoughts around the course:

- Pro :
  - Great bird's eye view for all AWS services
  - Many useful labs
  - Exam-oriented
  - Almost up-to-date with the exam topics (covered mostly all of exam topics but missing a few details about some of the services)
- Cons:
  - Not great for in details learning only for exam
  - Missing some important exam questions such as Auto Scaling - scale in policies which came to 2 exam questions.
  - Not great on covering for the AWS Well Architected Framework pdf. Ryan recommended reading it yourself but I think Ryan could do better summarizing this one as it was a key part to understand the AWS philosophy.

Side note: I bought it from my [Udemy](https://www.udemy.com/aws-certified-solutions-architect-associate/learn/v4/content) for A$15. Why Udemy? Because it was cheaper than the subscription from ACloudGuru with life-time access. I understand that some people that don't like Udemy as there is some news around Udemy and privacy. I fully understand it and that I made sure that the Author of the course is the one who distributes the course on Udemy so there is no privacy issue behind my purchase. But I wouldn't purchase it if it was stolen one.

## AWS sample questions and practice test

After spending around two weeks and completed the A Cloud Guru course, it gave me the first steps into learning the AWS platform and the exam. But I wasn't sure that I'm ready for the exam and a bit hesitated to book it. So, I started looking into practice exams. I found the official AWS sample questions [Link](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS_Certified_Solutions%20Architect_Associate_Feb_2018_Sample%20Questions_v1.0.pdf) and tried it and got 7 out of 10 right which is great but what I need. It gave me a small light but I wanted to have more practice so I went to the paid AWS practice exam which is almost half exam only - 25 questions in 30 minutes for almost A$30. I answered them in less 30 minutes, and I passed it. I found it easier than I thought and more abstracted as well without too much numbers and details.

Here is my report for AWS Certified Solutions Architect - Associate - Practice exam
Overall Score: 80%

Topic Level Scoring:
1  Design Resilient Architectures: 77%
2  Define Performant Architectures: 71%
3  Specify Secure Applications and Architectures: 83%
4  Design Cost-Optimized Architectures: 100%
5  Define Operationally-Excellent Architectures: 100%

My thoughts around sample questions and practice test:

- Pro:
  - Roughly good understand how is the exam questions look like
  - Rough figure around your score
- Cons:
  - Not a complete exam
  - Too simple comparing to the actual exam

Side note: when I went to buy the AWS Certified Solutions Architect - Associate (Feb 2018 version) practice exam, I wrongly purchased the professional architect one and paid around A$60 for it and didn't realize it. I went through it and failed to pass it. I got 32% score and found it very hard. This is a bad time as I had a bad night till discussing my results with one of my friends at Readify who told me that I went with the wrong practice exam which the professional exam. I was aware that there are three exams associate and the professional one. But I'm human being (and assume you are too) so take care what are you about to purchase.

## AWS White-papers and FAQs

After that I should go and read the whitepapaers and FAQs pdfs according to ACloudGuru and the exam preparation guide recommendations [Link](https://aws.amazon.com/certification/certification-prep/). But what happened that I decided to ignore them. This was because of being an "Abstract Thinkers" guy (INTP personality). You can read more about that [INTP personality "The Logican"](https://www.16personalities.com/intp-personality). I was afraid to deep dive into the details of each service and its huge information on cost, models, numbers etc. It thought it would distract me from understand and absorb what I have learnt already. Again, this is my personal way of learning, in the first shot I wouldn't give too much attention to the fine details. I was wrong about not reading these docs and will tell you more later why.

## WhizLabs

Later on, I got more confidence but I wanted more practice. So, I found [WhizLabs AWS Solutions Architect Associate practice exams](https://www.whizlabs.com/aws-solutions-architect-associate/). Again, I signed up to take their [WhizLabs free practice test](https://www.whizlabs.com/aws-solutions-architect-associate/free-test/). It is 20 questions in 40 minutes. I went through it and got 70% pass score which is good but I found that there were many questions similar to the official AWS practice exam so I decided to go and buy the full ones [WhizLabs 7 practice tests and section-based tests](https://www.whizlabs.com/aws-solutions-architect-associate/practice-tests/). This consists of 7 full practice exams and small 11 section-based tests (between 10-25 questions) covering VPC, S3, EFS, API Gateway, ECS, Lambda, EBS, STS, SNS, SQS, ELB, Auto Scaling, Route53 and general one. The cost was ~ A$25 for it (all of these questions). Which I thought it is a great deal so I bought this one. Also, in the same day, I booked my AWS exam two weeks away as I found the practice tests that would make me confident enough.

What I started to do is to solve them one by one in order. My process to complete one test and then go through all the questions I guessed the answers and the ones I got them wrong. And then I read the question/answer again, make a note of each of these questions and go/search/read the discussion/FAQ/point behind it till I got it. Example, I know all S3 and Glacier types/models but I didn't give too much attention to the retrieval time and I found many questions around that points so I read them and made sure I understand and remember them well. In the first round, I got around the boarding passing mark (~70-75%) and took slightly more than one hour from me to complete one of them. The was great but still not enough to pass. This worked very well with me and did each one of the 7 practices tests between 2-3 times and ended up with an average score 95% (all my results were between 59-64 out of 65) and average time to finish one in 50 minutes. I got the confidence that I would pass the exam.

Later on, I went into more detailed approach by going through the section-based tests offered by WhizLabs. I went into many of them (VPC, S3, EBS, Route53 and generic one) and followed the same process as the practices tests by revising the questions with answers then dive into the point online. But I didn't find enough time to go through all of them with the same process and the day arrived.

My thoughts around WhizLabs:

- Pro:
  - Great 7 practice tests with the price of the same price of the half AWS practice test  
  - There is no big overlap between the 7 tests questions that means a great coverage
  - Put you in a real exam situation with a timer and start/stop/pause to monitor your progress
  - Great explanation for each question/answer with link to read more on AWS side
  - Support that will reply to you within almost 24h in case you raised a question/correction to one of the questions
- Cons:
  - The section-based tests should be a part of the tests as they have the tricks questions for each service. I didn't see the point of splitting the platform into 7 practices and the section-based tests.
  - The 7 practice questions could give you a false confidence that you can pass while you are missing many important points  

# The exam

I went that day and started the exam on time. I struggled to scan my driver license and was a bit nervous but the technical support person understood there was something wrong and helped me. I started and it took from me almost one hour to answer all questions with almost 15-17 questions marked to review. And it took from me another hour to review most of the questions and focus the marked questions and think again about them. Sadly, the exam session stopped working twice but I was aware of this issue as one of my friends told me about it. Again the technical support person helped me in the two times and got me back on track again without losing any progress (Thanks for whoever was there monitoring me).

It took me almost the whole time (almost 2 hours and 8 minutes) to finish the exam. It was tough and stressful as it requires refreshing many topics in your head. I finished and finally I passed the certification. The result showed immediately on the screen as Passed. It was a great pleasure and just got the result of three months of hard studying.

The tricky questions in the exam are around (as far as I remember):  

- The controlling which Auto Scaling Instances Terminate During Scale In with and without termination
- Saving logs on a terminated EC2
- Stopping/termination on-spot instances
- Accessing RDS
- How to secure/encrypt the connection between DB and EC2
- ElastiCache details specially write-through
- IPV6 internet traffic in VPC and Security Groups
- AWS X-ray was one of the options
- Data encryption on S3 and Glacier
- Options of how put for db and app server into EC2 containers
- App A and app B with mixed range of subnets, need A to call b but b cannot call A

# My overall experience tips

- It is a very tricky exam and not easy for people without any cloud experience
- Go for ACloudGuru for training and WhizLabs for tests practices
- Read AWS FAQ and white-papers, if you can
- Don't just answer WhizLabs, but read the answer and description in details
- There is no real value to buy the AWS practice test as it is a bit expensive for only less than half of a full test.
- The main topics in the exam are (for sure) EC2, S3, RDS, VPC, Autoscaling and ELB. If you don't understand any of them very well, my advice is NOT GOING to the exam

At last, I would like to say thanks to @Readify to give me time and support to achieve this and for my wife Riham who gave me the support I needed all the time. Feel free to message me on Twitter [@MZaatar](https://twitter.com/MZaatar) or [LinkedIn](https://www.linkedin.com/in/mzaatar/)
