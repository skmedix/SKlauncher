# SKlauncher

Useful links
---
* [Official SKlauncher website](https://skmedix.pl/sklauncher)
* [Languages Codes](https://minecraft.gamepedia.com/Language#Available_languages)
* [FAQ](#faq)

FAQ
---
Before you ask a question on [issues tab](https://github.com/skmedix/SKlauncher/issues) make sure that question you want to ask is not there.

* [When I try to join the server I'm getting the error "Invalid session"](#q-when-i-try-to-join-the-server-im-getting-the-error-invalid-session)
* [My cape doesn't work, what should I do?](#q-my-cape-doesnt-work-what-should-i-do)
* [I can't login into the launcher using account credentials from SKL website](#q-i-cant-login-into-the-launcher-using-account-credentials-from-skl-website)
* [When I'm trying to use Optifine for 1.13+ I have an error java.lang.NoClassDefFoundError: org/objectweb/asm/ClassVisitor.](#q-when-im-trying-to-use-optifine-for-113-i-have-an-error-javalangnoclassdeffounderror-orgobjectwebasmclassvisitor)
* [When I'm trying to launch the launcher I have an error Could not find or load main class pl.skmedix.bootstrap.Bootstrap](#q-when-im-trying-to-launch-the-launcher-i-have-an-error-could-not-find-or-load-main-class-plskmedixbootstrapbootstrap)
* [Our LAN server doesn't work/is not showing, what should we do?](#q-our-lan-server-doesnt-workis-not-showing-what-should-we-do)
* [Minecraft 1.13 and above doesn't launch on 32-bit Linux?](#q-minecraft-113-and-above-doesnt-launch-on-32-bit-linux)
* [After logging in to SKL I can only play the demo version](#q-after-logging-in-to-skl-i-can-only-play-the-demo-version)
* [I can't allocate more than 1 GB of RAM to Minecraft](#q-i-cant-allocate-more-than-1-gb-of-ram-to-minecraft)
* [Is it possible to use mods in SKlauncher?](#q-is-it-possible-to-use-mods-in-sklauncher)
* [Will Rift or Fabric etc. mods work too?](#q-will-rift-or-fabric-etc-mods-work-too)
* [Blazingpack does not work/Going into Friends tab on Hypixel hangs the game](#q-blazingpack-does-not-work)
* [Launcher doesn't start / Launcher is stuck on "Loading"](#q-launcher-doesnt-start--launcher-is-stuck-on-loading)
* [Skins are not working](#q-skins-are-not-working)

### **Q: When I try to join the server I'm getting the error "Invalid session"**
A: The server that you trying to join is in online-mode (premium) so you can't join it.
(If you're an admin of the server, change the option online-mode to false in file server.properties)

### **Q: My cape doesn't work, what should I do?**
A: If skins works for you, but cape doesn't. You're probably still using SKL 2.8 instead of 3.0.

### **Q: I can't login into the launcher using account credentials from SKL website**
A: The login screen in SKL 3.0 is for Mojang (Premium) Accounts. Just check the Offline box.
 
### **Q: When I'm trying to use Optifine for 1.13+ I have an error java.lang.NoClassDefFoundError: org/objectweb/asm/ClassVisitor.**
A: Delete versions directory from .minecraft, run Minecraft via SKL 3.0, then close both launcher and the game and try to install OptiFine again.

### **Q: When I'm trying to launch the launcher I have an error Could not find or load main class pl.skmedix.bootstrap.Bootstrap**
A: Install Oracle JDK8.

### **Q: Our LAN server doesn't work/is not showing, what should we do?**
A: https://www.howtogeek.com/242375/how-to-troubleshoot-minecraft-lan-game-problems/

### **Q: Minecraft 1.13 and above doesn't launch on 32-bit Linux?**
A: The engine Minecraft uses, LWJGL, have dropped support for 32-bit Linux in LWJGL 3

### **Q: After logging in to SKL I can only play the demo version**
A: The login screen in SKL 3.0 is for Mojang (Premium) Accounts. Just check the Offline box.

### **Q: I can't allocate more than 1 GB of RAM to Minecraft**
A: Install Java 64-bit

### **Q: Is it possible to use mods in SKlauncher?**
A: Yes, you require Forge for the modifications, as well as 2 or more RAM to work it clean. When you will install the Forge as a Client, change version in profile settings to Forge and launch the game. When you will be in menu in Minecraft (after the forge will install) close Minecraft and head to .minecraft folder > profiles > Forge (Version), you should have there folder called Mods, (if you dont have it, create that folder) put there your mods. Remember to have them up to date and they are correct with the Forge version

### **Q: Will Rift or Fabric etc. mods work too?**
A: Yes, they will also work.

### **Q: Blazingpack does not work / Going into Friends tab on Hypixel hangs the game**
A: Turn on compatibility mode in profle settings (Game Settings - > Compatibility mode)

### **Q: Launcher doesn't start / Launcher is stuck on "Loading"**
A: Try to delete folders from other launchers in .minecraft folder,
Other solution is to delete sklauncher folder in .minecraft and install it again,
If the solutions above doesnt work, check Firewall or your Anti-virus program, it might block Java from running.

### **Q: Skins are not working**
Skins are **DISABLED** due to high traffic and **WILL STAY DISABLED** until further notice. Asking the question "When skins will be enabled" over and over will get you no response other than this one.
