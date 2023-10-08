---
title: g0lden's OSWE Thoughts!
date: 2023-10-08 1:00:00 -500
categories: [course-review]
tags: [course-review] # tag names should be lowercase
---
# My OSWE Journey

Hello! The following article will go over how I felt about Offensive Security’s AWAE course, as well as the exam to get OSWE certified. In this article I will cover:
- My background and experience coming into the course
- Recommendations for prep
- General thoughts on the AWAE course
- Quick tips for the exam

## 1. My Background and Starting Point

My first introduction to anything to do with ethical hacking, red teaming, and penetration testing was about 9 months ago! About 7 months ago I took the test and was able to get my OSCP. From that point on I went on doing bug bounties and CTFs as much as I could. I should also mention in this section that I do NOT do any kind of ethical hacking for my day job (yet?). After my OSCP, I focused mainly on web application hacking in the bug bounty programs I participate in. And that got me interested in getting my OSWE.

## 2. AWAE Prep

Honestly, I did very little compared to others to actually prepare before I started the coursework. These are two main places I would go if you are looking for some resources of exactly WHAT to study to prepare:
- [z-r0crypt's AWAE Preparation](https://z-r0crypt.github.io/blog/2020/01/22/oswe/awae-preparation/)
- [wetw0rk's AWAE-PREP on GitHub](https://github.com/wetw0rk/AWAE-PREP)
- [OSWE Cheat Sheet by cyber-dragon.nl](https://cyber-dragon.nl/2020/06/10/oswe-cheat-sheet/)

My simple tips for prep would be:
- Pick a scripting language you want to work on writing your exploits in and practice it! Personally, I would very highly recommend python, since most of the time you can just rely on the “requests” library! If you want practice scripting web exploits, go to [PortSwigger Academy](https://portswigger.net/web-security) and practice turning the exploits explained within into python scripts.
- Read “The Web Application Hacker’s Handbook”! I cannot stress enough how much even skimming through this book to understand the concepts and vulnerabilities can help you in your quest to OSWE. Half the battle in white box testing will be actually FINDING the vulnerability you have to exploit.
- DON’T stress as much on learning the languages. Try to get a wide overview of what all the languages look and feel like when being used to build a web application.

## 3. Short Little Rant About the Course

This section will be short since obviously I can not talk about the contents of the course or exam outside of what the syllabus mentions. But I will say this. Please take the time to work through ALL of the coursework. This will GREATLY increase your chances of success on the exam. In my opinion the coursework does an incredible job of preparing you for what is on the exam. So don’t fly through the coursework, and don’t skip the extra miles. If you complete everything including the extra miles and the lab machines, you should be more than ready for the exam!

Also, as far as lab time goes, that really depends on how comfortable you are debugging and testing web apps. If you have experience and the time to commit, you can probably get away with 30 days of lab time. I personally opted to take the full 90, though, to really slow down and take my time.

## 4. The Exam

Obviously, I cannot say anything about the contents of the exam. But I wanted to give a few pointers and some advice based both on my own experience and on the tips I received from others before I took the exam.
- Take lots of breaks! (Even just to walk around)
- Don’t get stuck on one thing. If you think you have something, look into it. But if you get nowhere, then go back and keep searching!
- Don’t blindly look through the whole code base. Find “signals” of certain vulnerabilities and grep through the code to try and see if they are present.
- Use and abuse the debugger, turn on database logging, and — if needed — add debugging print statements! (THIS CAN SAVE YOU A LOT OF TIME)
- Never give up!

## Conclusion

In my opinion, this course was an amazing opportunity to learn and experience web application security. The course, the extra miles, and the lab machines do an excellent job to prepare you for the exam. So really focus on understanding and getting through all the material they give you, and you should be all set for the exam. I honestly cannot recommend this course enough and I hope you enjoy it!

Thank you for reading! Feel free to connect with me using the links in the bottom left!
