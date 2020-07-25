# Ghost Framework
A brief review about the ghost framework


**Ghost Framework disclaimer:**
Usage of the Ghost Framework for attacking targets without prior mutual consent is illegal.
It is the end user's responsibility to obey all applicable local, state, federal, and international laws.
Developers assume no liability and are not responsible for any misuse or damage caused by this program.

**Shodan Disclaimer:**
Disclaimer: Please use Shodan responsibly. Manipulating any system that you do not own is illegal.
This is meant to be a research tool, and please be sure to put on your white hat before walking out into the cyber world.
**Shodan is just used as an example, using this to hack into private networks and servers is a punishable offense and I'm strictly against the use of this**

**I am not responsible for any of the issues caused by this, anything do it at your own risk**

**It involves huge risk, and one can be considered as trying to hack into it. And its a punishable offence**


Ghost Framework is an Android post-exploitation framework that exploits the
Android Debug Bridge to remotely access an Android device. Ghost Framework
gives you the power and convenience of remote Android device administration.

*This is what entynetproject tells us about the ghost framework.*

# Prerequisites

* Kali Linux (Main Os/Running a VM)
* Basic navigation using linux terminal.
* Internet Connectivity.
* Free space on Hard disk to install the required packages.(Jk)


I've recently come across the ghost framework, 
and It can be used by anyone with a mere knowledge about cybersecurity.

# Advantages of the Ghost Framework
* It can be used to access the device shell.
* It has a simple user interface and is user-interface.
* It can be used to remove the device password.

https://github.com/entynetproject/ghost

*This is the link to the ghost framework.*

# Ghost Installation
```
git clone https://github.com/entynetproject/ghost.git
```
And then using the following commands from Linux command line
```
cd ghost
chmod +x install.sh
./install.sh
```
Basically, it allows us to connect through Android Debug Bridge, 
and then we can access the device by using some commands.

So after the installation is done successfully,

# Ghost Framework execution
We first navigate into the ghost directory
```
cd ghost/
```
And now we list the files and folders,
```
ls -l
```
Then we get the following menu
<insert img>
Now we must convert it into an excutable 
```
chmod +x install.sh
```
Now since its in the excutable we install it using,
```
./install.sh
```
**This will initialize the installation of ghost framework and the dependencies.**

# Ghost Framework execution
To run the ghost framework, it needs superuser privileges in order to run it.
```
sudo ghost
```
Like any other sudo command, kali will ask us to authenticate using password.
After sucessful authentication we are into the ghost framework,
<img2>

Now to list all the commands we run the following command
```
help
```
<img3>

This menu displays few core ghost commands like,
# Core Commands
* clear
* connect
* disconnect
* exit
* help
* update


The terms are all self-explainatory, Make sure you have the latest version of the ghost framework running bu using the update command.

Now we use the delivery mechanism, and we can use many mechanisms like,
USBs, wireless, android debug bridge, and also we can use it as an email payload, so when the victim clicks on the link,
we can gain access into the target device.

# Getting the IP
IoT crawler like Shodan, which finds vulnerable devices connected like cameras, phones, and smart home devices 
like a smart speaker connected to the internet.

We can search for databases, servers, and many other similar things.
And now, with few keywords, we can find the Ip addresses of various vulnerable devices.
<img4>
Now again back to the ghost framework,
```
connect (IP of target)
```
This command will send the payload to the target device and
when the victim clicks the payload the following menu appears
<img5>
Now the device is in our control, there are many commands to expliot the target.

# Ghost uninstallation:
```
cd ghost
chmod +x uninstall.sh
./uninstall.sh
```
This will remove all the ghost framework packages.






