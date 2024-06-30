<font face="Oswald, serif" size="4" color="black">
On a not-so-fine hot summer morning, I wanted to dual-boot my Windows laptop with Ubuntu because... why not? Is installing Ubuntu such a huge task? Nope, but I made it difficult with my unpreparedness. So, I want you guys to know the mistakes I did during installation so that you can have a smooth installation. Sounds awesome, right? Okay, let's dive into my Ubuntu installation experience.<br><br>

    <p>I followed every step in the tutorial. As a part of the next step, we needed an empty USB. Then I realized that my USB was full of files. I deleted all the files on my pendrive and inserted it into my PC. Ironically, my pendrive was not detected. I tried many times, but all attempts were in vain. Then I checked whether it was detected on another PC. Yes, it was detected on another PC. But what's the point when I have to install Ubuntu on MY laptop? So, I formatted my pendrive on another PC and tested my luck again. When I inserted it into my laptop, it was detected!!! gif: (yayy)</p><br>
<p>
We have to install Ubuntu on a pendrive using Rufus, which I did perfectly. It's all going well until I mistakenly assigned less space for the Ubuntu partition. I gave 30 GB for the new OS, and the worst thing is I didn't even realize it was insufficient. Now, when I restart my PC, Ubuntu is not showing up and I've come full circle back to where I started. It's a mess again!! I tried to shrink the disk space again. It is not working. Then I came to know about GParted, an official GNOME partition-editing application. I downloaded it again and with all my cleverness, I installed GParted on my pendrive. (gif: facepalm)</p><br>

<p>It's time to format again!! After formatting my pendrive, I wanted to try again to install Ubuntu and restarted my laptop. Ubuntu appeared on my screen!! Unexpected things happen when we least expect them. So, I opened it and followed the tutorial as it is. Then I came across a new term, 'BitLocker encryption.' We have to turn off BitLocker encryption in Windows so it allows changes for the new OS. I went to Windows, turned it off using the command-line prompt. I came back to Ubuntu and finally, I had dual-booted my laptop.</p><br>
It's a rollercoaster ride, but I learned many new things, terms, and got to know how to troubleshoot errors on my own, which can make things worse or more fun than they are.<br>
Mistakes I made:

    * Giving less disk space
    * Not having an empty USB ready
    * Installing GParted on my USB
    * Not Turning off BitLocker in Windows before installation

Things I learned:

    * Get to know more about the steps you are following in a tutorial. In simple terms, don't follow blindly without understanding.
    + Got to know the GParted application.
    - Can troubleshoot my own USB (just kidding).

Stay tuned if you want to hear about my experience with Ubuntu or how my Ubuntu is working with less disk space. </font>
