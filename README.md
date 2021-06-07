## Welcome to baby195lxl's Pages


I use the github blog to write down some tips and ideas in my life.  
Actually,I am major in Civil Engineering--it means ***I'm a rookie***,so please don't be mad at me when I ask some dull question.  
THANKS!  

### Pack the OpenWrt for Phicomm-N1  
* Download the source code from [unifreq's repository](https://github.com/unifreq/openwrt_packit "unifreq's repository")   
![捕获](https://user-images.githubusercontent.com/48685934/120991819-93a46f80-c7b4-11eb-96a1-bd70c52b23c7.JPG)

-----------------------------------------------------------------------------------------------------------
* Download three components from [unifreq's telegram channel](https://t.me/openwrt_flippy "unifreq's telegram channel")  
![捕获](https://user-images.githubusercontent.com/48685934/120992194-f0078f00-c7b4-11eb-96a7-d3ae4afa5536.JPG)

----------------------------------------------------------------------------------------------------------
* Download the OpenWrt image from [OpenWrt_release](https://github.com/baby195lxl/OpenWrt_N1_Testing "OpenWrt_release")
![捕获](https://user-images.githubusercontent.com/48685934/121013178-1801ed00-c7cb-11eb-840e-133d319efa0d.JPG)  

**ATTENTION!!! CHOOSE THIS IAMGE!!**  
![捕获](https://user-images.githubusercontent.com/48685934/121013459-6e6f2b80-c7cb-11eb-929a-279aa4062f48.JPG)

-----------------------------------------------------------------------------------------------------------
* Create the /home/username/opt/kernel folder in Linux in VMware *(I recommand use Ubuntu)*   
use `sudo mkdir /home/username/opt/kernel`  
**ATTENTION!!! 'username' IS YOUR USERNAME!**

-----------------------------------------------------------------------------------------------------------
* Copy those files that we download to the  /home/username/opt/kernel folder and unzip the openwrt_packit-master.zip  
![捕获](https://user-images.githubusercontent.com/48685934/121016098-50ef9100-c7ce-11eb-9926-d6a3839b2bb3.JPG)


-----------------------------------------------------------------------------------------------------------
* Edit the make.env,make sure your version and path is right!
![捕获](https://user-images.githubusercontent.com/48685934/121018074-9745ef80-c7d0-11eb-87b7-210bfc99c082.JPG)

-----------------------------------------------------------------------------------------------------------
* Open the terminal,make sure the `pwd` is `/home/username/opt/kernel`,input the command  
`sudo bash mk_s905d_n1.sh`

-----------------------------------------------------------------------------------------------------------
* Input the  `sudo chmod -R 777 tmp`,the image is in the folder:***tmp***




