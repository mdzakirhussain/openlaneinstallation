# openlane

<h4>All the below steps needs to be run in UBUNTU Machine's terminal. Following are the readily accessible resources. If you face any issues please contact me at</h4>

<ul><li>Email: zakir.hussain.work@gmail.com</li><b>OR</b><li>Mobile:+919949426362</li></ul>

<b>1. First Download Oracle VM Virtualbox</b>

<a href="https://drive.google.com/file/d/19xzfCOasAnaMo3Ko1gZnNpvf6HuQ2pyY/view">Download Oracle VM Virtualbox</a>

<b>2. Second Download this Virtual Machine</b>

<a href="https://drive.google.com/drive/folders/1AfyLbUMrOOjMRa-fI9xr9lEOX8y7B3S7?usp=sharing">Download Virtualmachine UBUNTU</a>

<b>3. Watch this video to open virtual machine</b>

<a href="https://drive.google.com/file/d/14smArs39XjfoQeWRvrB46SlOzfvrUlu5/view">Watch this video to open virtual machine</a>

<h4>Follow the following steps to install open source EDA tools</h4>

1. on your Desktop open the terminal and then type cd and then press enter
2. then type sudo apt-get clean
3. then type sudo apt-get update
4. then type sudo apt install git --assume-yes
5. then type git clone https://github.com/mdzakirhussain/openlaneinstallation.git
6. then type cd openlaneinstallation
7. then type chmod 777 toolsinstallation.sh
8. then type sudo ./toolsinstallation.sh

<h4>NOTE</h4><br>
If you are using your own installation of ubuntu virtual machine instead of provided ubuntu's virtual machine by me, then after step 6. in the above do the following<br>

Type in the terminal <b>gedit toolinstallation.sh &</b> <br>This will open the file toolinstallation.sh, in that replace "vvi" with your user name.<br> If you are in doubt of user name, then in the terminal type echo $USER, it will return user name.<br>

And then follow the above steps 7 and 8. That is it, you are done.
