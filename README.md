# How-to-DIIT

[Digital Invisible Ink Toolkit](https://diit.sourceforge.net/index.html) is a steganography toolkit that NCL often uses. Its use is straightforward, but installing it can be difficult for beginners. 

I recommend using Linux for this tool, there is a Windows version, but it's easier on Linux.

## How to install

Due to DIIT being a .jar file, we have to install Java 1.5 or higher on our machine, which can be done in a Linux command line like this.

```
sudo apt install default-jre
```
This will install the default Java version and settings, allowing us to run DIIT.

Now install DIIT. You can download the jar by visiting this link: [HERE](https://sourceforge.net/projects/diit/files/diit/1.5/diit-1.5.jar/download?use_mirror=phoenixnap)

Now all you have to do is navigate to your Downloads folder and run this command.

```
java -jar diit-1.5.jar
```

You will now be met with the DIIT GUI. 

![image](https://github.com/JoshuaHartz/How-to-DIIT/assets/102620766/df64b5d9-bab7-4d76-bd4c-35630cc0a6b4)




There are 4 tabs, but we will need the decode tab. This tab will allow us to take an image and run it through 6 potential algorithms to see if we can find hidden text. We have:

1. BattleSteg (a fan favorite)
2. BlindHide
3. DynamicBattleSteg
4. DynamicFilterFirst
5. FilterFirst
6. HideSeek

You may not end up using all of these, but it doesn't take too long to try them, so there is no harm in giving each a shot until you find the encoded information you need. Also, I strongly recommend setting a designated text file to write so you can store the output somewhere. A standard text file will do; you can specify it using the "Set Message" button in the last row. 
