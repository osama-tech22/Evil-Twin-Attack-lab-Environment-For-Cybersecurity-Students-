# Evil-Twin-Attack-Environment--For-Cybersecurity-Students-
It is a great way to practice your cybersecurity skills and get some hands-on experience in the cybersecurity space.




### Materials you will need to do the project.
* ##### ESP32 CAM: (https://a.co/d/euru0Em)          
* ##### USB Cable
* ##### MicroSD Card

### Flashing the ESP32 cam and configure it to be the target Access point : 
* ##### I attached two files you will need for this step or you can download them from the links below 
* ##### Espressif Flash Tool: https://www.espressif.com/en/support/download/other-tools
* ##### Github Firmware: https://github.com/martin-ger/esp32_nat_router
* ##### [This video for the steps after you downlaod the files"How to Make a WiFi Repeater using ESP32 "](https://youtu.be/BP1Dz66faf4)
* ##### [For step by step written instructions](https://theiotprojects.com/portable-esp32-wifi-repeater/)

### Requirements for Evil Twin Attack: 
* ##### Kali Linux is preferred
* ##### wireless adapter : https://a.co/d/6eh2gOa
* ##### fluxion tool : https://github.com/FluxionNetwork/fluxion
* ##### airgeddon tool :https://github.com/v1s1t0r1sh3r3/airgeddon

### Will chose fluxion 
* #####  Install Fluxion
git clone https://github.com/FluxionNetwork/fluxion
* ##### Go to the folder, then list the contents to see the files in it.
cd fluxion
fluxion# ls
* ##### Then give executable permission to the fluxion.sh file
chmod +x fluxion.sh
* ##### Run the tool
./fluxion.sh
* ##### install all the missing packages type 
./fluxion.sh -i
* ##### Select your language 
* ##### Scan wifi hotspots "select the wireless attack for access point "
* [1] Captive Portal Create an "evil twin" access point.
* ##### select a wireless interface for target searching
choose your adpater
* ##### select channel to monitor 
* all channels 2.4GHZ 
* ##### choose your target AP 
* ##### get the handshake 
*  mdk4 deauthentication (aggressive)
* ##### Select a wireless interface for target searching
* (recommended the same interface you selected before)
* ##### select a method of verification for the hash
* Use cowpatty verification which is recommended. 
* ##### How often should the verifier check the handshake?
* #####  Select an access point service
* Rogue AP - hostapd (recommended)
* #####Select a password verification method
* [1] hash - cowpatty
* ##### Do you want to use this file?  
* Specific path for hash
* ##### Select a method of verification for the hash
* ##### cowpatty verification
* ##### Select SSL certificate source for captive portal
*  [1] Create a SSL certificate
* ##### Select an internet connectivity type for rogue network.
* Mostly disconnected is recommended.
* ##### Select the captive portal interface for the rough network.
* You just need to select the right language according to you or the router brand of the target Wi-Fi
* ##### Start the attack
* your attack will start automatically and six windows will pop up in front of you. 
* ##### As soon as the user connects with your fake one you will be able to see some information in those terminal windows which popped up in front of you. And in the users phone the browser will open which will say “Wi-Fi framework update” and asks the user to provide the password for the update. If the user enters the password this tool will verify the password with the hash you captured, if the password is wrong then it will say wrong password to the user and the attack will continue. When the user enters the correct password the user will see some framework updating and in your terminal you will see five of the pop up windows will close automatically and in one window you will see a message “The password was saved in/(path of the file)”.
* ##### 




### links to Documention and Videos

* ##### [ ]()

* ##### []())

* ##### [ ]())

