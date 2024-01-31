What is the Remote Desktop Protocol (RDP)?
The Remote Desktop Protocol (RDP) is a protocol, or technical standard, for using a desktop computer remotely. Remote desktop software can use several different protocols, including RDP, Independent Computing Architecture (ICA), and virtual network computing (VNC), but RDP is the most commonly used protocol. RDP was initially released by Microsoft and is available for most Windows operating systems, but it can be used with Mac operating systems too.

What does 'remote desktop' mean?
Remote desktop is the ability to connect with and use a faraway desktop computer from a separate computer. Remote desktop users can access their desktop, open and edit files, and use applications as if they were actually sitting at their desktop computer. Employees often use remote desktop software to access their work computers when they are traveling or working from home.

Remote desktop access is very different from cloud computing, even though both allow employees to work remotely. In cloud computing, users access files and applications that are stored in the cloud — specifically, in cloud servers. In contrast, when using remote desktop software, users are actually accessing their physical desktop computer, and can only use files and applications saved locally on that desktop. Cloud computing is sometimes easier to use and more efficient to implement for remote workforces, but many companies have not migrated to the cloud, or cannot for security or regulatory reasons.

How does RDP work?
Think of a remote-controlled drone or toy car. The user presses buttons and steers the drone or car from afar, and their commands are transmitted to the vehicle. Using RDP is somewhat like that: the user's mouse movements and keystrokes are transmitted to their desktop computer remotely, but over the Internet instead of over radio waves. The user's desktop is displayed on the computer they are connecting from, just as if they were sitting in front of it.

The RDP protocol opens a dedicated network channel for sending data back and forth between the connected machines (the remote desktop and the computer currently in use). It always uses network port 3389 for this purpose. Mouse movements, keystrokes, the desktop display, and all other necessary data are sent over this channel via TCP/IP, which is the transport protocol used for most types of Internet traffic. RDP also encrypts all data so that connections over the public Internet are more secure.

Because keyboard and mouse activity has to be encrypted and transmitted over the Internet, which takes a few milliseconds, and because the desktop display has to be transmitted back to the user, slight delays often occur. For instance, if a user double-clicks on an application to open it, the "double click" may not take place for a few milliseconds as the user's action is transmitted to the desktop before being carried out. Then, when the application opens, there may be another short delay while the display is transmitted back to the user.

What are the pros and cons of using RDP?
There are several advantages to RDP. One advantage is that it does not require a VPN. It also keeps data stored securely on the user's desktop, instead of storing it on cloud servers or on the user's unsecured personal devices. Furthermore, RDP enables companies with a legacy on-premises IT setup to allow their employees to work from home.

However, RDP may cause users to experience lag, especially if their local Internet connection is slow. This can frustrate remote employees and cut down on their productivity. RDP also has some serious security vulnerabilities that leave it open to cyber attacks. (Learn more about RDP security.)

How does Cloudflare help accelerate and secure RDP?
Cloudflare Spectrum reduces network latency associated with long-distance RDP connections and other network issues. Cloudflare decreases the connection time for sessions and helps reduce overall network latency for a more real-time user experience by using smart routing. Cloudflare also offers Tunnel to prevent unauthorized port 3389 connections, making RDP more secure.

In addition, the Cloudflare Zero Trust platform helps keep remote teams secure and productive. By placing RDP-connected assets behind the Cloudflare network, companies can use SSO credentials to validate sessions, instead of relying on weak user passwords.
