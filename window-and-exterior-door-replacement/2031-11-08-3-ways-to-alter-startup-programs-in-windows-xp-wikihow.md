---
title: "3 Ways to Alter Startup Programs in Windows XP - wikiHow"
date: 2031-11-08 09:26
author: Daniel Okafor
---

# 3 Ways to Alter Startup Programs in Windows XP - wikiHow

Skip to Content Quizzes PRO Courses Hot Guides  Tech Help Pro  Expert Videos  About wikiHow Pro  Upgrade  RANDOM EXPLORE

Tech Help ProAbout UsRandom ArticleQuizzes

[XP wikiHow](https://xp-wikihow.northlist.shop/xp-wikihow/20260826.html)

Request a New ArticleCommunity DashboardTrendingForums

Arts and EntertainmentArtworkBooksMovies

Computers and ElectronicsComputersPhone SkillsTechnology Hacks

HealthMen's HealthMental HealthWomen's Health

RelationshipsDatingLoveRelationship Issues Hobbies and CraftsCraftsDrawingGames

[Programs in Windows XP](https://programs-in-windows-xp.swapstreet.shop/programs-in-windows-xp/20260826.html)

Education & CommunicationCommunication SkillsPersonal DevelopmentStudying

Personal Care and StyleFashionHair CarePersonal Hygiene

QuizzesLove QuizzesPersonality QuizzesFun Games

[Windows XP](https://windows-xp.swapstreet.shop/windows-xp/20260826.html)

Arts and EntertainmentFinance and BusinessHome and GardenRelationship Quizzes

Cars & Other VehiclesFood and EntertainingPersonal Care and StyleSports and Fitness

Computers and ElectronicsHealthPets and AnimalsTravel

[Ways to Alter](https://ways-to-alter.themaplelane.com/ways-to-alter/20260826200.html)

Education & CommunicationHobbies and CraftsPhilosophy and ReligionWork World

Family LifeHolidays and TraditionsRelationshipsYouth LOG IN Log in

Social login does not work in incognito and private browsers. Please log in with your username or email to continue. Facebook Google wikiHow Account No account yet? Create an account Subscribe Home Random Browse Articles TrendingNew Quizzes & Games All QuizzesHot Love Quizzes Personality Quizzes Fun Games Dating Simulator Learn Something New Forums Courses Happiness Hub Explore More Support wikiHow About wikiHow Log in / Sign up Terms of Use

wikiHow is where trusted research and expert knowledge come together. Learn why people trust wikiHow Categories Computers and Electronics Operating Systems Windows XP Instructions

How to Alter Startup Programs in Windows XP Download Article Author Info Last Updated: July 8, 2025 Download Article MSConfig | Windows Defender | Registry Editor | Video | Q&A | Tips | Warnings | Things You'll Need |Show more|Show less X

wikiHow is a “wiki,” similar to Wikipedia, which means that many of our articles are co-written by multiple authors. To create this article, 37 people, some anonymous, worked to edit and improve it over time. 

This article has been viewed 1,930,678 times.  Learn more...

If you've been using Windows XP for a while, you may have noticed that your computer is taking longer to boot up. This is because programs are adding themselves to your start up, and they all have to load before you can start using the computer. Just follow the simple steps below and your computer will start a lot faster! Steps Method 1 Method 1 of 3: MSConfig Download Article 1

Open Microsoft's System Configuration Utility (called MSConfig). Go to START -> Run, and enter msconfig. Hit enter to start the program. The following window should appear. Choose Selective Startup.

[Windows XP wikiHow](https://windows-xp-wikihow.northlist.shop/windows-xp-wikihow/20260826.html)

If Run is not found in the Start Menu, to add the "Run command": Right click Start -> Properties -> select tab "Start Menu" -> Customize -> Customize Start Menu -> check the Run box -> Apply -> OK . 2

Click on the 'Startup' tab. Here, you will see a list of programs that is similar to the one below: Advertisement 3

Uncheck any programs that you do not want Windows to run at startup. 4

Click 'OK'. A new window will appear, asking you to restart your computer. 5 Click 'Restart.' Advertisement Method 2 Method 2 of 3: Windows Defender Download Article 1

Download Windows Defender from Microsoft. 2

Click on the Start menu. Click All Programs and then select Windows Defender. 3 Choose Tools and the Software Explorer. 4

Click the names of the programs in the Name column that you want to disable. When you are finished, click Disable. Advertisement Method 3 Method 3 of 3: Registry Editor Download Article 1

Open the Start menu and click Run. Type regedit into the field. 2

Locate 1 of the following registry keys:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce 3

Find the program that you want to remove from the startup sequence. Delete that one program from either or both of those registry keys.

Caution: Do not delete other items in regedit that you see. Many may be unknown, peculiarly named system files. You could easily disable program associations, needed services, make the system fail or to be unstable. Advertisement Community Q&A  Search Add New Question Question

I am trying to get the program to not only start, but for the application window to be open and ready to use. Right now it just goes to the taskbar. What do I do? Community Answer

[in Windows](https://in-windows.swapstreet.shop/in-windows/20260826258.html)

Create a shortcut to the app (drag with the right button, let go, and select "Shortcut"), then drop a shortcut in the startup folder under applications.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 0Helpful 0 Question

I have a timing issue on a CNC control with application starting before network is ready. Any way to put in a delay before starting an application? Arrogance Top Answerer

[Windows XP](https://windows-xp.northlist.xyz/windows-xp/202608262345.html)

Not directly, but you could put a batch (.bat) file in the Startup folder to open the program instead of a shortcut. Not all Windows XP systems have a sleep command, so a common workaround is to use ping to wait for a set amount of time. For example, you could have a .bat file that looks like: @echo off ping -n 31 127.0.0.1>nul cnc.exe  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 0Helpful 0 Ask a Question 200 characters left

Include your email address to get a message when this question is answered. Submit Advertisement Video Tips

If you are unsure which programs are slowing your computer down, disable all the startup programs in Windows XP by clicking the Disable All button on the Startup Tab window. Restart your PC and, if the speed improves, then start adding programs back in one at a time until you discover which program is slowing down your startup. Thanks Helpful 18 Not Helpful 8

If you are unsure whether or not to leave a program running, search for the file name on ProcessLibrary.com to see whether a particular startup process should or should not be removed. Thanks Helpful 0 Not Helpful 0 Submit a Tip 

All tip submissions are carefully reviewed before being published Name 

Please provide your name and last initial Submit Thanks for submitting a tip for review!  Advertisement Warnings

Back up your registry before you alter it, just in case you make an error. Thanks Helpful 8 Not Helpful 2

Some programs are essential to system stability, such as ctfmon.exe,cmd.exe, and svchost.exe. Do not disable these processes. Thanks Helpful 9 Not Helpful 3 Advertisement Things You'll Need PC with Windows XP Windows Defender (optional) You Might Also Like How to Speed up a Windows XP Computer How to Stop Norton Antivirus Startup How to

Access System Configuration (msconfig) in Windows How to

Add and Remove Startup Programs in Windows 7 How to

Speed Up a Slow Windows Computer for Free How to

Make Windows 7 Faster: A Step-by-Step Guide How to

Clean the Registry by Hand, Regedit, & Cleanup Apps

17 Easy Ways to Boost Your PC's Speed & Performance How to

Make Your PC Run Faster: Complete Guide & Tips How to Make Your Windows 11 PC Run Faster How to Speed Up Acer Aspire One

Clean Up a Slow Performing Computer: Fixing Common Issues Advertisement References

How to disable programs that run at startup when you log in on windows xp professional edition? ProcessLibrary About This Article

wikiHow is a “wiki,” similar to Wikipedia, which means that many of our articles are co-written by multiple authors. To create this article, 37 people, some anonymous, worked to edit and improve it over time. This article has been viewed 1,930,678 times.  How helpful is this? Co-authors: 37 Updated: July 8, 2025 Views: 1,930,678 Categories: XP Instructions In other languages Italian Spanish German Dutch Chinese Russian Indonesian Japanese Print Send fan mail to authors

[Windows XP wikiHow](https://windows-xp-wikihow.curblist.xyz/windows-xp-wikihow/20260826.html)

Thanks to all authors for creating a page that has been read 1,930,678 times. Is this article up to date? YesNo Advertisement

Cookies make wikiHow better. By continuing to use our site, you agree to our cookie policy. About This Article Click a star to vote Co-authors: 37 Updated: July 8, 2025 Views: 1,930,678 Quizzes & Games Am I Chronically Online Quiz Take Quiz What Type of Clutterbug Am I? Take Quiz What Age Is My Brain Quiz Take Quiz Cognitive Test Take Quiz You Might Also Like How to Speed up a Windows XP Computer How to Stop Norton Antivirus Startup How to

[Alter Startup Programs](https://alter-startup-programs.northlist.shop/alter-startup-programs/202608267387.html)

[Windows XP wikiHow](https://windows-xp-wikihow.northlist.shop/windows-xp-wikihow/20260826432.html)

[How to Care for a Rabbit: Absolutely Everything Your Bunny Needs](https://github.com/ynx4vmkvha/kjefya/blob/main/auto-detailing/2031-07-01-how-to-care-for-a-rabbit-absolutely-everything-your-bunny-ne.md)

Access System Configuration (msconfig) in Windows How to

Add and Remove Startup Programs in Windows 7 Trending Articles Am I Chopped Quiz Kiss, Marry, Kill Quiz What Type of Person Do I Attract Quiz Which World-Ending Catastrophe Are You? Trending Articles

Pick a Door and We'll Reveal What You're Missing What’s the Name of My Crush? Am I a Side Chick or a Main Chick Quiz What Kind of Doomed Am I? Take the Quiz. Face the Truth. 🔥 Am I Gay Quiz Do I Have a Type? Am I Hard to Love? Am I a Spoiled Brat? 🤔 Are You More... 🤔 How Tuff Am I? What Kind of Wolf Is My Personality?

Am I More Golden Retriever or Black Cat? Villain or Hero Quiz Featured Videos How to Create a Cone from Paper: 2 DIY Methods How to

Tell If Your Phone Is Tapped: Telltale Signs + Fixes

7 Ways to Know if You’re Addicted to Wearing Diapers A Beginner's Guide to Bullet Journaling Hot Takes Only 🔥

Do You Agree with These Hygiene Hot Takes?

Weird Would You Rather: What Do You Choose?

Do You Agree With These Spicy Hot Takes? Overrated or Underrated Game Your Daily Dose of Fun 🎉 Can We Guess Your Hair Color?

Can You Pull Off The Perfect Heist? Prove Yourself

Do You Agree with These Popular Hot Takes?

Let Us Guess Your Age Based On Video Game Nostalgia Categories Computers and Electronics Operating Systems Windows XP Instructions

© 2026 wikiHow, Inc. All rights reserved. Use of site content is subject to our Terms of Use. wikiHow Tech Newsletter You're all set!

Helpful tech how-tos delivered to your inbox every week! Sign me up!

By signing up you are agreeing to receive emails according to our privacy policy. Home About wikiHow Experts Jobs Contact Us Site Map Terms of Use Privacy Policy Do Not Sell or Share My Info Not Selling Info Contribute Follow Us ×

Keep up with the latest tech with wikiHow's free Tech Help Newsletter Subscribe You're all set! X - - 715
