# RedMicro
RedMicro Android Ransomware

# Warning
This project is developed solely for educational, security research, and authorized penetration testing purposes. Using this code for any malicious activity, ransomware, unauthorized encryption, sabotage, or harassment of others is strictly prohibited and illegal. 

· This tool should only be run on devices that you personally own or have received express written permission from the owner. 

· Any misuse, legal, criminal, and civil consequences will be directly attributed to the user. 

· The developer(s) are not responsible for any improper or illegal use of this code. 

By downloading, copying, or using this code, you agree that you will use it only for legal and ethical purposes.

# Description of this ransomware 
Let me start by saying this: I built this project using AI. I was familiar with Sketchware Pro, but I was weak — or honestly, I just didn't know — Java. So I turned to AI for help and built my own project. But what's wrong with that? AI is just a tool, right? So we can definitely use it.

Anyway, putting that aside — please use this project only and only for legal purposes and in your own lab environment. If you use this app for unethical purposes, it carries serious criminal charges.

Now, stick with me as I explain exactly how to set this tool up in your own lab. But first, let me tell you what this tool actually does. Stay with me.

Alright, so as soon as this tool runs on your lab environment and test phone, it will ask for a permission — you have to grant it. After that, a screen will appear on your phone that you can't get rid of no matter what. It only goes away when you enter the password. But let me warn you: this tool only gives you 10 minutes to enter the password. After entering the password, you only have 10 seconds to uninstall the app, otherwise it locks again. And if you don't unlock it, after 10 minutes your phone will be factory reset.

But stick with me — I promise I'll show you how to change the password and how to increase or decrease that countdown timer later on.

# How do I edit the file?
That was a good question, you install the apk editor.apk program that I gave you in the apk editor folder and then install the RedMicro.apk program, but do not run the program under any circumstances. Enter the apk editor program and select the program. Open the entire program source. Activate the Smail option at the top of the page so that the entire program source is opened for you. Then type and search for the following word in the program source:
```
10000
```
This number in the Java file called OverlayService.java at line 187 determines how many milliseconds your test phone has to uninstall the app after entering the password. The lower the number, the faster the app reactivates after the password is entered — it's totally up to you. If you can't figure it out in the app, or if you can't find this number by searching inside an APK editor, just open the project I've placed in Sketchware Pro. In the Java/Kotlin section, you can open the OverlayService.java file and increase or decrease the duration at line 187, then rebuild the project and get the APK output.

Note: The app also plays a funny Iranian song with SpongeBob's voice when it runs — I just put it there for the humor of it. Enjoy 😂

And that's it, that was my project. I hope you like it.

But remember this: time is extremely important in this project. Watch yourself and use the time wisely so you don't get hurt.

# last word
This project is for legal purposes only. Any misuse of this project will result in legal and criminal prosecution and is considered a crime. So use it properly.

# Creator
An 18-year-old Iranian kid who loves the world of computers, security, and programming ♥️(:
