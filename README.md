# Day-1-Vsd_tcl
Installed ubuntu 24.04 and virtual box and opened a VDI file in Ubuntu using VirtualBox.

Created a GitHub account by signing-up using this link https://github.com/

# VSD-TCL Environment (OpenTimer + Yosys)
This Codespace provides a ready-to-use synthesis and timing analysis setup on Ubuntu 22.04, with both terminal and GUI (noVNC) access.

## Step 1 – Open the Codespace
Go to the GitHub repository: https://github.com/vsdip/vsd-tcl
Click “Code” → “Open with Codespaces” to launch the environment in your browser.

<img width="882" height="648" alt="codespace" src="https://github.com/user-attachments/assets/2dc0342b-b433-494c-9b79-9b003002605e" />

# Option 1 - Use the terminal

Once the Codespace opens, go to the TERMINAL tab and run:

OpenTimer

<img width="685" height="268" alt="opentimer" src="https://github.com/user-attachments/assets/f6990f3b-0ad1-4d0c-b8a6-197a6d011c9d" />

Yosys

<img width="662" height="250" alt="yosys(1)" src="https://github.com/user-attachments/assets/8e5146c3-e6fe-454c-b1be-9af5fa9702dd" />

# Option 2 – Use the GUI (noVNC Desktop)

1.In your Codespace, open the PORTS tab.

2. Find the forwarded port named noVNC Desktop (6080).

<img width="715" height="130" alt="image" src="https://github.com/user-attachments/assets/3207b635-4515-4808-9641-37a1c19603f9" />

3. Click the forwarded URL.

4. On the web page, select vnc_lite.html to open the XFCE desktop.

<img width="831" height="450" alt="image" src="https://github.com/user-attachments/assets/23869528-7bc0-4e08-8980-cd7558539bfb" />

5. noVNC window opens:

<img width="1466" height="690" alt="image" src="https://github.com/user-attachments/assets/8e4dc7d2-6b16-447c-aae5-7e85cac7b156" />

6. The design files are available under the folder: /workspaces/vsd-tcl

   <img width="1062" height="323" alt="image" src="https://github.com/user-attachments/assets/4cf6140c-c8e2-4c11-a799-241a9c309ab7" />

7. Inside the desktop terminal, run:
   
   OpenTimer -h

   <img width="1162" height="797" alt="OpenTimer-h" src="https://github.com/user-attachments/assets/e65c61e8-018f-4f50-8db2-a1a96649ec29" />

   yosys -V

   <img width="1000" height="257" alt="yosys(option2)" src="https://github.com/user-attachments/assets/c365a549-39e1-4ef9-8b16-1fa12fe847d8" />


   




