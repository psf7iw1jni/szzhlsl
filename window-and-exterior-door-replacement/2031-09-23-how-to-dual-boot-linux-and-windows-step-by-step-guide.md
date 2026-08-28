---
title: "How to Dual Boot Linux and Windows: Step-by-Step Guide"
date: 2031-09-23 10:52
author: Liam Connor
---

# How to Dual Boot Linux and Windows: Step-by-Step Guide

Skip to Content Quizzes PRO Courses Hot Guides  Tech Help Pro  Expert Videos  About wikiHow Pro  Upgrade  QUIZZES All Quizzes Hot Love Quizzes  Personality Quizzes  Trivia Quizzes  Taylor Swift Quizzes  EXPLORE

Tech Help ProAbout UsRandom ArticleQuizzes

Request a New ArticleCommunity DashboardTrendingForums

Arts and EntertainmentArtworkBooksMovies

Computers and ElectronicsComputersPhone SkillsTechnology Hacks

HealthMen's HealthMental HealthWomen's Health

RelationshipsDatingLoveRelationship Issues Hobbies and CraftsCraftsDrawingGames

Education & CommunicationCommunication SkillsPersonal DevelopmentStudying

Personal Care and StyleFashionHair CarePersonal Hygiene

QuizzesLove QuizzesPersonality QuizzesFun Games

Arts and EntertainmentFinance and BusinessHome and GardenRelationship Quizzes

Cars & Other VehiclesFood and EntertainingPersonal Care and StyleSports and Fitness

Computers and ElectronicsHealthPets and AnimalsTravel

Education & CommunicationHobbies and CraftsPhilosophy and ReligionWork World

Family LifeHolidays and TraditionsRelationshipsYouth LOG IN Log in

Social login does not work in incognito and private browsers. Please log in with your username or email to continue. Facebook Google wikiHow Account No account yet? Create an account RANDOM Home Random Browse Articles TrendingNew Quizzes & Games All QuizzesHot Love Quizzes Personality Quizzes Fun Games Dating Simulator Learn Something New Forums Courses Happiness Hub Explore More Support wikiHow About wikiHow Log in / Sign up Terms of Use

wikiHow is where trusted research and expert knowledge come together. Learn why people trust wikiHow Categories Computers and Electronics Operating Systems Windows

How Dual Boot Windows & Linux on Your Computer Download Article

Easily install Linux on your Windows PC with this dual-boot guide

Co-authored byNicole Levine, MFAReviewed byStan Kats

Last Updated: February 23, 2026Fact Checked Download Article Before You Begin | Create a Linux Install Drive | Shrink Your Windows Partition | Run the Linux Installer | Video |Show more|Show less X

This article was reviewed by Stan Kats and by wikiHow staff writer, Nicole Levine, MFA. Stan Kats is a Professional Technologist and the COO and Chief Technologist for The STG IT Consulting Group in West Hollywood, California. Stan provides comprehensive technology solutions to businesses through managed IT services, and for individuals through his consumer service business, Stan's Tech Garage. Stan holds a BA in International Relations from The University of Southern California. He began his career working in the Fortune 500 IT world. Stan founded his companies to offer an enterprise-level of expertise for small businesses and individuals. 

There are 8 references cited in this article, which can be found at the bottom of the page. 

This article has been fact-checked, ensuring the accuracy of any cited facts and confirming the authority of its sources. 

This article has been viewed 10,533 times. 

If you want to run Linux on your PC without getting rid of Windows, it's easy to set up a dual boot environment. Whether you want to dual boot Windows with Ubuntu, Linux Mint, or any other Linux distro, installing Linux on a Windows PC is easiler than ever, and totally beginner-friendly. We'll walk you through the process. Quick Steps Download a Linux installation ISO file.

Create a USB install drive from the ISO.

Boot from the install drive to start the Linux installer.

Choose the option to install Linux alongside Windows.

Click Install Now and follow the on-screen instructions.

When the installer finishes, reboot your PC.

When it comes back up, choose whether to boot into Linux or Windows. Steps Section 1 of 4: Before You Begin Download Article 1 What you'll need

A blank USB flash drive - You'll want one that's at least 8 GB.

At least 30 GB of disk space - That's at a minimum. If you plan to install and use software on Linux and want some wiggle room, aim for 50GB or more.[1]XResearch source

A Linux install image - There are more than 600 Linux distributions available, so you have a lot of options.[2]XResearch source If you're new to Linux, try Linux Mint or Ubuntu, as both are widely used, somewhat Windows-like, and have plenty of software, documentation, and user resources available. To create the installation drive, you'll need to download an ISO image of the installer media. Here are a few options: Ubuntu Linux Mint Debian Fedora CentOS openSUSE

Rufus - This is the tool you'll use to create the bootable USB flash drive you'll use to install Linux.

A Windows PC with a UEFI - A UEFI is a sort-of upgrade to a traditional BIOS, and fortunately, most motherboards have had them since 2007. To check, type system information into the Windows search bar and press Enter. If you see "UEFI" next to "BIOS Mode," you're good. If you see "Legacy," check your documentation to see if you can switch to UEFI mode. 2

Back up your PC While dual-booting Windows and Linux is safe, you'll want to make sure your PC is backed up before you begin. Check out our backup guide to learn how to back up your Windows PC. Advertisement Section 2 of 4: Create a Linux Install Drive Download Article 1

Insert your flash drive and open Rufus. If you haven't already downloaded Rufus, you can download it from rufus.ie/en/#download.

Make sure your flash drive is empty. Once you use Rufus to create the installation media, its contents will be erased.

Rufus doesn't need to be installed. Just double-click the downloaded file to run it. 2

Select your flash drive in Rufus. Click the "Device" menu, then select the name of your USB flash drive.[3]XResearch source 3

Click Select and select your Linux ISO. Navigate to the ISO image you downloaded and select it. Once selected, you'll see its name under "Boot selection." 4

Click Start. There's no need to change any of the default settings. When you click Start, you'll see a few prompts:

First, when prompted, choose "Write image in ISO mode" and click OK.

Then, you'll see a warning that the data on the flash drive will be erased. Click OK.

When Rufus is finished creating your install drive, you can close the program. Advertisement Section 3 of 4: Shrink Your Windows Partition Download Article 1

Open Disk Management. To do so, right-click the Start menu and select Disk Management. You'll be using Disk Management to allocate some space on your hard drive for Linux.[4]XResearch source

This section is not mandatory, as most Linux installers will prompt you to create a partition for Linux during the installation process. If you'd rather use Linux to shrink your partition, jump to Run the Linux Installer.

If you feel more comfortable managing partitions in Windows, continue with this section. 2

Shrink your primary drive to allow room for Linux. In most cases, your C drive will be your main drive, and it's usually dedicated to Windows. To install Linux on the same drive, you'll need to allocate some of that space to Linux by creating a partition–at least 30 GB (or more, if you want room to install more software). Here's how:[5]XResearch source

Right-click the drive with the space you want to use and select Shrink Volume.

Enter the desired size of your Linux partition in MB. For example, 40000 MB = 40 GB.

Keep in mind this will subtract the amount of space from your main Windows drive. Click Shrink.

When you're finished, you'll see "Unallocated space" the size of your future Linux partition. Instead of formatting the partition in Disk Management, you can close the program and instead use the Linux installer to format it. Advertisement Section 4 of 4: Run the Linux Installer Download Article 1

Boot your PC from the USB flash drive. Here's an easy way to do this without having to mess around in the BIOS/UEFI to change the boot order:

Right-click the Start button to open the Power User menu.

Hold down the Shift key as you select Shut down or sign out > Restart.

Continue holding down the Shift key until the "Choose an option" screen appears. Select Use a device. Click the name of your flash drive.

After a few moments, your PC will reboot from the flash drive. 2

Start the installer. The process to install Linux is going to be different for each distribution, but the steps will be similar. You'll typically be asked if you want to install Linux or "Start Linux," which will begin the process of guiding you through installation.

In Linux Mint (and some other OSes), booting from the installer will take you to the desktop instantly. On the desktop, you'll see the Install Linux Mint icon, which you'll need to double-click to start the installation.[6]XResearch source

If you're installing Ubuntu, you'll first be asked to choose your language, set up your keyboard, and connect to the internet. Then, you'll be asked if you want to install Ubuntu alongside your current operating system. Once you select the option, choose Interactive Installation to start the installer.[7]XResearch source 3

Choose the option to install Linux alongside Windows. The wording of this step will vary, but it'll usually be something like Install Linux Mint alongside Windows Boot Manager. When you choose this option, you will see a list of drives and partitions–including that unallocated space you got from shrinking your main drive.[8]XResearch source 4

Verify the partition and click Install Now. In the partition creator in most distros, including Linux Mint and Ubuntu, you'll see the partitions on your current drive, and Linux will ask you if you want to adjust the size of either partition. You shouldn't need to make any changes here unless you don't see a partition that's the size of the one you allocated for Linux.[9]XResearch source

[Boot Linux and Windows](https://boot-linux-and-windows.themaplelane.com/boot-linux-and-windows/20260826.html)

If you didn't shrink a larger drive or partition earlier, you can drag the bar to allocate more or less space for Linux. Remember, you'll want Linux to have at least 30 GB, but likely more if you plan to install a bunch of software. 5

Follow the on-screen instructions to install. During installation, you'll be asked to create a user account for Linux–the password you create will also be the one you use to run sudo commands. 6

Restart your PC. When the installation is complete, you'll be prompted to restart your computer. Choose the option to do so, and you'll be presented with the option to boot into Windows or Linux. You are now dual-booting Linux and Windows!

Unplug the USB flash drive to prevent your PC from trying to boot from it. Advertisement

Want to save this article? Download it as a PDF. 

[How to](https://how-to.northlist.shop/how-to/20260826.html)

How Dual Boot Windows & Linux on Your Computer

Get the full formatted PDF you can save, print, or read offline. Anytime, anywhere. Download PDF for $2.99 One-time purchase Expert Q&A  Search Add New Question Ask a Question 200 characters left

Include your email address to get a message when this question is answered. Submit Advertisement Video Tips Submit a Tip 

All tip submissions are carefully reviewed before being published Name 

Please provide your name and last initial Submit Thanks for submitting a tip for review!  You Might Also Like How to Install Linux on Your Computer How to

Install Two OS on One Computer: Easy Dual Boot Guide How to Create a Bootable Linux USB: Windows 10 How to

[Boot Linux and Windows](https://boot-linux-and-windows.northlist.xyz/boot-linux-and-windows/20260826.html)

Install a Different Operating System on a PC How to

Install Ubuntu Linux: Dual Boot with Windows or macOS How to

Install Arch Linux Dual Boot on Any Computer Easy Debian Linux Installation Tutorial

Use Rufus to Create Bootable USB Drives: Guide + Fixes How to

Install Puppy Linux on a USB Drive or PC

Installing Windows 10 or 11 on Ubuntu: A Step-by-Step Guide How to Install Linux Mint How to Switch from Microsoft Windows to Linux Advertisement References

↑https://linuxnewbieguide.org/overview-of-chapters/chapter-4-preparing-to-install-linux/#Hard_Disk_Drive_HDD_Partitioning_your_disk_for_Linux

[to Dual](https://to-dual.curblist.xyz/to-dual/202608264238.html)

↑https://learn.microsoft.com/en-us/linux/install#step-2---choose-a-linux-distribution ↑https://rufus.ie/en/

↑https://opensource.com/article/19/5/dual-booting-windows-linux-uefi

↑https://learn.microsoft.com/en-us/windows-server/storage/disk-management/shrink-a-basic-volume

↑https://youtu.be/mbgWdI6Cfqo?si=TSaRuuZztnMDxWei&t=860

[How to Dual Boot](https://how-to-dual-boot.curblist.xyz/how-to-dual-boot/2026082611.html)

↑https://ubuntu.com/tutorials/install-ubuntu-desktop#4-boot-from-usb-flash-drive

[How to Change Your Style: 12 Steps (with Pictures) - wikiHow](https://github.com/rsigvmi4oq/kqiwdrb/blob/main/mobile-tire-service/2030-12-10-how-to-change-your-style-12-steps-with-pictures-wikihow.md)

↑https://ubuntu.com/tutorials/install-ubuntu-desktop#6-type-of-installation

↑https://ubuntu.com/tutorials/install-ubuntu-desktop#6-type-of-installation About This Article Reviewed by:  Stan Kats Professional Technologist

This article was reviewed by Stan Kats and by wikiHow staff writer, Nicole Levine, MFA. Stan Kats is a Professional Technologist and the COO and Chief Technologist for The STG IT Consulting Group in West Hollywood, California. Stan provides comprehensive technology solutions to businesses through managed IT services, and for individuals through his consumer service business, Stan's Tech Garage. Stan holds a BA in International Relations from The University of Southern California. He began his career working in the Fortune 500 IT world. Stan founded his companies to offer an enterprise-level of expertise for small businesses and individuals. This article has been viewed 10,533 times.  How helpful is this? Co-authors: 3 Updated: February 23, 2026 Views: 10,533 Categories: Windows | Linux In other languages Spanish Japanese Print Send fan mail to authors

Thanks to all authors for creating a page that has been read 10,533 times. Is this article up to date? YesNo Advertisement

Cookies make wikiHow better. By continuing to use our site, you agree to our cookie policy. Reviewed by:  Stan Kats Professional Technologist Click a star to vote Co-authors: 3 Updated: February 23, 2026 Views: 10,533 Quizzes & Games

What Do I Want in a Weight Loss Program Quiz Take Quiz What's My Religion Quiz Take Quiz

What Kind of Video Game Should I Play Quiz Take Quiz What Language Should I Learn Quiz Take Quiz You Might Also Like How to Install Linux on Your Computer How to

Install Two OS on One Computer: Easy Dual Boot Guide How to Create a Bootable Linux USB: Windows 10 How to

Install a Different Operating System on a PC Trending Articles Am I Chopped Quiz Kiss, Marry, Kill Quiz What Type of Person Do I Attract Quiz Which World-Ending Catastrophe Are You? Trending Articles

Pick a Door and We'll Reveal What You're Missing What’s the Name of My Crush? Am I a Side Chick or a Main Chick Quiz What Kind of Doomed Am I? Take the Quiz. Face the Truth. 🔥 Am I Gay Quiz Do I Have a Type? Am I Hard to Love? Am I a Spoiled Brat? 🤔 Are You More... 🤔 How Tuff Am I? What Kind of Wolf Is My Personality?

Am I More Golden Retriever or Black Cat? Villain or Hero Quiz Featured Videos How to Create a Cone from Paper: 2 DIY Methods How to

[Linux and Windows Step-by-Step](https://linux-and-windows-step-by-step.northlist.xyz/linux-and-windows-step-by-step/20260826.html)

[and Windows Step-by-Step](https://and-windows-step-by-step.themaplelane.com/and-windows-step-by-step/2026082642.html)

Tell If Your Phone Is Tapped: Telltale Signs + Fixes

7 Ways to Know if You’re Addicted to Wearing Diapers A Beginner's Guide to Bullet Journaling Hot Takes Only 🔥

Do You Agree with These Hygiene Hot Takes?

Weird Would You Rather: What Do You Choose?

Do You Agree With These Spicy Hot Takes? Overrated or Underrated Game Your Daily Dose of Fun 🎉 Can We Guess Your Hair Color?

Can You Pull Off The Perfect Heist? Prove Yourself

Do You Agree with These Popular Hot Takes?

Let Us Guess Your Age Based On Video Game Nostalgia Categories Computers and Electronics Operating Systems Windows

© 2026 wikiHow, Inc. All rights reserved. Use of site content is subject to our Terms of Use. wikiHow Newsletter You're all set! Helpful how-tos delivered to your inbox every week! Sign me up!

By signing up you are agreeing to receive emails according to our privacy policy. Home About wikiHow Experts Jobs Contact Us Site Map Terms of Use Privacy Policy Do Not Sell or Share My Info Not Selling Info Contribute Follow Us × wikiHow Tech Help Pro:

Level up your tech skills and stay ahead of the curve Let's go! X - - 682
