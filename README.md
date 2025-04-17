# wifi-deauth-detector

Abstract
	For my final project, I’m building a tool that can detect Wi-Fi deauthentication attacks as they happen. These attacks are a type of denial-of-service where someone sends fake deauth packets to disconnect devices from the network. It’s surprisingly easy to launch this kind of attack using widely available tools, but without proper monitoring, it can go completely unnoticed. My tool will use Python and Scapy to monitor wireless traffic in real time and alert the user when a suspicious spike in deauthentication frames is detected. To test the system safely, I’ll simulate an attack using the aircrack-ng suite on my own Wi-Fi network inside a virtual Linux environment with a USB Wi-Fi adapter that supports monitor mode. This ties directly into the wireless protocol and security concepts we’ve discussed in class and could be useful in real-world environments like homes, campuses, or small businesses. If time allows, I’ll also add features like logging, alert notifications, and vendor lookups to improve usability.

Tools and Materials
Software:
  Python 3
  Scapy
  aircrack-ng (for simulating attacks)
  TShark (optional, for logging)
Hardware:
  USB Wi-Fi adapter that supports monitor mode (Alfa AWUS036ACH)
  MacBook running Ubuntu VM via VMware Fusion
