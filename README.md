# remote-ubuntu-desktop
If you want to control your Ubuntu desktop remotely from an Android phone, there are a few solid ways to do it depending on whether you want full desktop control, just terminal access, or file transfer.
Here’s a breakdown:

# 1. VNC (Full Desktop Control, Easy to Set Up)
# Install VNC Server on Ubuntu

      sudo apt update
   
      sudo apt install tigervnc-standalone-server tigervnc-viewer
   
# Set a password: 
    vncpasswd
# Start the server: 
    vncserver
# On Android:
Install VNC Viewer (RealVNC) or bVNC from Google Play, then connect to:

# makefile 
    <Ubuntu-IP>:5901
Pros: Works well over LAN/Wi-Fi, supports full desktop.

Cons: Not as fast as RDP; needs port forwarding for remote over internet.
