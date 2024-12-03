## **WR11. Unable to Login Web-based Interface**

【Troubleshooting】  
**1\.** Ensure your client is connected to your TP-Link Router’s network, via wired or wireless connection  🠊   
**2\.** Ensure the IP address or domain name is input in the address bar, not the search bar  🠊   
**3\.** Confirm the error message or clues that appeared on the website

**Case 1: The page cannot be reached/We couldn't find the page/Trying to configure...**   
**1\.** Disable firewall or anti-virus software on the PC or smartphone  🠊   
**2\.** Try different web browsers.  🠊   
**3\.** Try different end devices, such as smartphones or tablets  🠊   
**4\.** Browse the web privately in Incognito mode  🠊   
[https://support.google.com/chrome/answer/95464?hl=en\&co=GENIE.Platform%3DDesktop](https://support.google.com/chrome/answer/95464?hl=en&co=GENIE.Platform%3DDesktop)）  
**5\.** Turn off mobile data and VPN service on the device. Ensure the clients are truly connected to the router（If convenient, it is recommended to check if the device gets the IP address from TP-Link. ([FAQ838](https://www.tp-link.com/us/support/faq/838/))🠊   
**6\.** Turn off and turn back on the WiFi on your phone/laptop; reconnect to TP-Link Wi-Fi🠊   
**7\.** Try different Ethernet cables and Ethernet ports for PC🠊   
**8\.** Reboot router🠊   
In the Advanced-\>System-\>Administrator page, if the user sets the local managers, only the specific device selected can visit the admin web UI, other device will be unable to reach the page, the user needs to use this device to see the admin web UI. 

**Case 2: Your connection is not private...**  
[FAQ3344](https://www.tp-link.com/us/support/faq/3344/)

**Case 3: The web page shows ISP or other router brands' Web UI**  
This means the device may connect to the frontier device such as a modem router/router.  
**1\.** Disconnect the TP-Link product from the front-end device by unplugging the cable from the WAN port and trying to log in via the domain name/IP again 🠊   
**2\.** If still fails, check the error message again and follow the troubleshooting steps🠊 

## **WR12. How to Set up WiFi Router**

Web UI: [FAQ3841](https://www.tp-link.com/us/support/faq/3841/)  
Tether App: [FAQ2564](https://www.tp-link.com/us/support/faq/2564/)

## **WR13. No Internet after Setup (internet light is red)** 

【Troubleshooting Step】  
**1\.** Ensure the WAN port of the router is connected to the modem, and only the wireless router is connected to the modem's Ethernet port🠊  
Note: Please ensure your router is connected to the correct internet port on your ISP modem. Avoid using ports designated for IPTV or VoIP, as they won't provide internet access.   
**2\.** Check the Internet LED of the router.

 **\*\*\*\*\*\*Red/orange\*\*\*\*\*\***   
**FOR DYNAMIC IP**  
**1\.** Restart your modem by turning it off, unplugging the coaxial cable, waiting 2-3 minutes, turning it back on, ensuring it restarts correctly, and then plugging the cable back in🠊  
**2\.** Check if a PC or an old router can get online directly from the modem. If not, contact your ISP to check the modem. If yes, perform a MAC clone (refer to [FAQ68](https://www.tp-link.com/us/support/faq/68/) or [FAQ2264](https://www.tp-link.com/us/support/faq/2264/)). Record the following for the MAC clone:   
**a.** The IP, gateway, DNS, and subnet mask obtained by the PC or old router when connected to the modem🠊  
**b.** The MAC addresses of the TP-Link router before and after the MAC clone🠊  
**Notes:**  
**1\.** If you don't have a PC or an old router, check the modem's LED indicators to see if it's working. If it seems fine, turn it off and wait 20 minutes before restarting it. (Schedule a callback after this time.) 🠊  
**2\.** If you have an old router that works with the modem, set it up in a chain: modem → old router → TP-Link router. If this setup works, it indicates no hardware issue with the TP-Link router. Check the internet connection type or contact the ISP to verify or resolve any MAC binding issues🠊

**FOR PPPOE/STATIC IP**  
**1\)** Reboot the modem and wait to check if the internet is working. If not, it's suggested to contact the ISP to confirm the internet parameters such as username, password, and VLAN ID🠊  
Note: For UK ISP Vodafone, a VLAN ID is needed in most cases. CityFibre: VLAN will be 911; Openreach: VLAN will be 101Ireland ISP Vodafone: VLAN should be 10  
[https://whirlpool.net.au/wiki/vdsl2\_modem\_routers\_isp\_settin](https://whirlpool.net.au/wiki/vdsl2_modem_routers_isp_settin)

**If the above suggestion is not helpful, please collect information and escalate to SE**  
【Information collection】  
**1\.** Troubleshooting results  
**2\.** Model number, hardware, firmware version of the router🠊  
**3\.** ISP, model No. of the modem🠊  
**4\.** the screenshot of PC's IP address, GW, DNS, and Mac address when connected to the modem🠊  
**5\.** the screenshot of the router's Mac address after Mac Clone done🠊  
**6\.** System log🠊

## **WR14. No Internet after Setup (internet light is green)**

【Troubleshooting Step】  
**1\.** Ensure the WAN port of the router is connected to the modem, and only the wireless router is connected to the modem's Ethernet port🠊  
Note: Please ensure your router is connected to the correct internet port on your ISP modem. Avoid using ports designated for IPTV or VoIP, as they won't provide internet access.  
**2\.** Check the Internet LED of the router.

**\*\*\*\*\*Green\*\*\*\*\*\***   
**1\.** Make sure the user has logged into the Web UI. If not, follow FAQ 87 to log in first🠊  
**2\.** Change the WAN DNS into 8.8.8.8 and 8.8.4.4 ([FAQ1712](https://www.tp-link.com/us/support/faq/1712/)) 🠊

If the above suggestion is not helpful, please collect information and escalate to SE  
【Information collection】  
**1\.** Troubleshooting results  
**2\.** Model number, hardware, firmware version of the router  
**3\.** ISP, model No. of the modem  
**4\.** System log

## **WR15. No Internet after Setup (internet light is off)**  

【Troubleshooting Step】  
**1\.** Ensure the WAN port of the router is connected to the modem, and only the wireless router is connected to the modem's Ethernet port🠊  
Note: Please ensure your router is connected to the correct internet port on your ISP modem. Avoid using ports designated for IPTV or VoIP, as they won't provide internet access.  
**2\.** Check the Internet LED of the router 🠊

  **\---OFF---**    
Please refer to [FAQ2982](https://www.tp-link.com/us/support/faq/2982/) \---  
For models support combo WAN ports or selecting WAN ports, please login admin web UI and go to the Advanced-》Network-》Internet page to double check the Internet port in use is the same as the port connected to modem by cable. Like Archer AX90/GX90/AXE200/AXE300/BE550/BE800/BE805/BE900

## **WR16. No Internet after Setup（Wi-Fi 7 routers)**

For WiFi7 models, please login the admin web UI to check the Internet status and WAN IP. Some WiFi 7 models use the LED Screen to determine the Internet status, and there is no separate Internet LED.

**Case 1: WAN IP is 0.0.0.0** \- please refer to WR13 (No Internet after Setup (internet light is red)  
**Case 2: WAN IP is NOT 0.0.0.0** \-  please refer to WR14(No Internet after Setup (internet light is green)  
**Case 3: Internet status shows WAN port unplugged** \- please refer to WR15 (No Internet after Setup (internet light is off)

## **WR17. AP Mode Setup**

Please refer to [FAQ1384](https://www.tp-link.com/us/support/faq/1384/)

## **WR21. Cannot See WiFi Signal**

【Troubleshooting Steps】  
Note: If the user cannot see a **6ghz Wi-Fi signal only**, please refer to [FAQ3092](https://www.tp-link.com/us/support/faq/3092/)\---

**1\.** Make sure you are within the signal coverage range of the router, and try to get closer to it to check the Wi-Fi signal🠊  
**2\.** Check if the Wi-Fi name includes special characters "," "\!", and "%", and try to remove the special characters for a try🠊  
**3\.** Try rebooting the router🠊  
**4\.** Confirm that the router's WiFi function is enabled and that the network name (SSID) and password are correctly set, not hidden🠊  
**5\.** Try changing the wireless router's 2.4ghz or 5ghz channel🠊  
**6\.** Reset the wireless router🠊  
**7\.** If the wireless settings are gray, or the wireless settings disappear in the admin web UI, please RMA and consult senior if need to collect the unit🠊  
Note: Only Wi-Fi6E (IEE802.11 AXE) /Wi-Fi7 IEE802.11BE support 6G band, only when both the client device and the router support 6G band, the client device can see the 6G Wi-Fi network of the router🠊

【Information collection】  
**1\.** Troubleshooting results🠊  
**2\.** TP-Link device Model, HW, FW🠊  
**3\.** When does the issue happen🠊  
**4\.** The model of the Devices has issues🠊

## **WR22. Unable to Connect WiFi**

【Troubleshooting Steps】  
Note: If the user cannot see a **6ghz wifi signal only,** please refer to [FAQ3092](https://www.tp-link.com/us/support/faq/3092/)

**1\.** Enable a Guest network with no security using only the 2.4Ghz band and check whether the device can connect to the network🠊  
**2\.** Confirm that you are trying to connect to the correct network and are using the correct password🠊  
**3\.** Ensure there are no special characters in the SSID and wireless password, such as apostrophes or other characters mentioned here: Special Characters are not suitable as Wi-Fi Name and Password🠊  
**4\.** Change the wireless security of your network to WPA2 (Some Devices Have Difficulty with Newer Standards such as WPA 3, or may not be compatible at all) 🠊  
**5\.** Confirm the Device is not listed in the parental control or access control list 🠊  
**6\.** If the problem persists, collect information and forward it to SE🠊

【Information collection】  
**1** . Troubleshooting results 🠊  
**2\.** TP-Link device Model, HW, FW 🠊  
**3\.** When does the issue happen 🠊  
**4\.** The model of the Devices has issues 🠊

## **WR24. Poor Wi-Fi Range**

**【Troubleshooting Steps】**  
**Step 1:**  Ensure your router is placed in a central location in your home or office to maximize coverage. Avoid placing it near thick walls, metal objects, or appliances that can interfere with the signal🠊  
**Step 2:** Adjust antennas for optimal signal distribution. Position them vertically for a more balanced coverage🠊  
**Step 3:** Make sure your router's firmware is up to date. Check the manufacturer's website for the latest firmware updates and install them to potentially improve performance🠊

**Case1: The client can't connect or see the wireless network if the distance is more than 10 feet without any obstacles**, RMA and consult senior if need to collect unit  
**Case2: Users complain that the product is not as good as advertised, and some rooms have dead spots, but most areas can be covered**. Please refer to the following texts to reply the user:  
*''The router's signal strength is related to the transmission power, which is limited by the legal. We strictly adhere to local laws and regulations regarding the transmission power of routers to ensure that our devices operate within legal limits. Moreover, we recognize the importance of bidirectional signal transmission in wireless communication for establishing a good connection. Even if the router emits a strong signal, communication quality can be compromised if the client cannot receive the signal.*  
*Regarding the issue of insufficient wireless coverage, especially when poor communication occurs in dead zones, I suggest you can consider adding a Range Extender between the dead zone and the router can effectively expand the wireless coverage, improve communication quality, and ensure that signals reach a broader area. If you need advice on selecting a Range Extender or any other technical support, please feel free to contact our customer service team. We are here to assist you.''*

## **WR31. The Internet Stopped Working suddenly (internet light is red)**

**【Troubleshooting Step】**  
**1\.**  Ensure the WAN port of the router is connected to the modem, and only the wireless router is connected to the modem's Ethernet port🠊  
Note: Please ensure your router is connected to the correct internet port on your ISP modem. Avoid using ports designated for IPTV or VoIP, as they won't provide internet access.   
**2\.** Check the Internet LED of the router🠊

**\*\*\*\*\*\*RED/ORANGE\*\*\*\*\*\***  
**FOR DYNAMIC IP**  
**1\.** Restart your modem by turning it off, unplugging the coaxial cable, waiting 2-3 minutes, turning it back on, ensuring it restarts correctly, and then plugging the cable back in🠊  
**2\.** Check if a PC or an old router can get online directly from the modem. If not, contact your ISP to check the modem. If yes, perform a MAC clone (refer to [FAQ68](https://www.tp-link.com/us/support/faq/68/) or [FAQ2264](https://www.tp-link.com/us/support/faq/2264/)). Record the following for the MAC clone:   
**a.** The IP, gateway, DNS, and subnet mask obtained by the PC or old router when connected to the modem🠊  
**b.** The MAC addresses of the TP-Link router before and after the MAC clone🠊  
Notes:  
**1\.** If you don't have a PC or an old router, check the modem's LED indicators to see if it's working. If it seems fine, turn it off and wait 20 minutes before restarting it. (Schedule a callback after this time.) 🠊  
**2\.** If you have an old router that works with the modem, set it up in a chain: modem → old router → TP-Link router. If this setup works, it indicates no hardware issue with the TP-Link router. Check the internet connection type or contact the ISP to verify or resolve any MAC binding issues🠊

**FOR PPPOE/STATIC IP**  
**1\)**  Reboot the modem and wait to check if the internet is working. If not, it's suggested to contact the ISP to confirm the internet parameters such as username, password, and VLAN ID🠊  
Note: For UK ISP Vodafone, a VLAN ID is needed in most cases. CityFibre: VLAN will be 911; Openreach: VLAN will be 101Ireland ISP Vodafone: VLAN should be 10  
[https://whirlpool.net.au/wiki/vdsl2\_modem\_routers\_isp\_settin](https://whirlpool.net.au/wiki/vdsl2_modem_routers_isp_settin)

If the above suggestion is not helpful, please collect information and escalate to SE  
【Information collection】  
**1\.** Troubleshooting results  
**2\.** Model number, hardware, firmware version of the router🠊  
**3\.** ISP, model No. of the modem🠊  
**4\.** the screenshot of PC's IP address, GW, DNS, and Mac address when connected to the modem🠊  
**5\.** the screenshot of the router's Mac address after Mac Clone done🠊  
**6\.** System log🠊

## **WR32. The Internet Stopped Working suddenly(internet light is green)**

【Troubleshooting Step】  
**1\.** Ensure the WAN port of the router is connected to the modem, and only the wireless router is connected to the modem's Ethernet port🠊  
Note: Please ensure your router is connected to the correct internet port on your ISP modem. Avoid using ports designated for IPTV or VoIP, as they won't provide internet access.  
**2\.** Check the Internet LED of the router.

**\*\*\*\*\*Green\*\*\*\*\*\***   
**1\.** Make sure the user has logged into the Web UI. If not, follow [FAQ 87](https://www.tp-link.com/us/support/faq/87/) to log in first🠊  
**2\.** Change the WAN DNS into 8.8.8.8 and 8.8.4.4 ([FAQ1712](https://www.tp-link.com/us/support/faq/1712/)) 🠊

If the above suggestion is not helpful, please collect information and escalate to SE  
【Information collection】  
**1\.** Troubleshooting results  
**2\.** Model number, hardware, firmware version of the router  
**3\.** ISP, model No. of the modem  
**4\.** System log

## **WR33.The Internet Stopped Working suddenly(internet light is off)**

【Troubleshooting Step】  
**1\.** Ensure the WAN port of the router is connected to the modem, and only the wireless router is connected to the modem's Ethernet port🠊  
Note: Please ensure your router is connected to the correct internet port on your ISP modem. Avoid using ports designated for IPTV or VoIP, as they won't provide internet access.  
**2\.**  Check the Internet LED of the router.

 **\---OFF---**   
Please refer to [FAQ2982](https://www.tp-link.com/us/support/faq/2982/) \---  
For models support combo WAN ports or selecting WAN ports, please login admin web UI and go to the Advanced-》Network-》Internet page to double check the Internet port in use is the same as the port connected to modem by cable. Like Archer AX90/GX90/AXE200/AXE300/BE550/BE800/BE805/BE900

## **WR34. The Internet Stopped Working suddenly( Wi-Fi 7 routers)**

For WiFi7 models, please login the admin web UI to check the Internet status and WAN IP. Some WiFi 7 models use the LED Screen to determine the Internet status, and there is no separate Internet LED.

**Case 1: WAN IP is 0.0.0.0**, please refer to WH13(No Internet after Setup (internet light is red）  
**Case 2: WAN IP is not 0.0.0.0**, please refer to WH14(No Internet after Setup (internet light is green）  
**Case 3: Internet status shows WAN port unplugged**, please refer to WH15 (No Internet after Setup（internet light is off）

## **WR35. The Internet LED turns red intermittently (multiple times a day or once every few days)**

Note: If the user only encounters wireless unstable issues, please refer to WR34

【Troubleshooting Steps】  
**Step1:** Change the Ethernet cable between the ISP modem and router🠊  
**Step2:** Please change the WAN DNS to 8.8.8.8 or 8.8.4.4🠊  
**Step3:** Ensure the router updated the latest firmware version🠊  
**Step4:** Observe for a few days, if the issue happens again, please ask the user to save the system logs. 🠊  
**Step5:** If the user has another old router, please connect it to ISP modem and connect TP router behind the old router for a test, like this🠊  
Internet—ISP modem—old router—TP router

If other devices have the same issue when connected to the ISP modem directly, please suggest contacting the ISP for further help🠊  
If there is no other routers or other routers work well with ISP network, please collect the information and escalate to SE.

【Information Collection】  
**1\.** Troubleshooting results of each step 🠊  
**2\.** Dropping frequency of the clients. 2\. ISP name and connection type 🠊  
**3\.** FW version(upgrade the FW first if it's not up to date) 🠊  
**4\.**  System log and double confirm the network stability of the frontier modem/router🠊  
Note: The system log will be cleared if the router restarted, so please collect the logs before restarting the router to restore Internet.  
**5\.** Can it restore the connect automatically after a few minutes? Or the restart is necessary? 🠊

## **WR36. Unstable Wireless Connection**

【Troubleshooting Steps】  
**1\.** Update the firmware of the wireless router to the latest version🠊  
**2\.** Make sure the router is away from wireless interference sources. Keep the router away from microwave ovens and other interference sources (refrigerators, ovens, Bluetooth devices, etc.)🠊  
**3\.** Reduce the number of wireless clients and optimize the router’s position🠊  
**4\.** Set different wifi names for 2.4gzh and 5gha bands and disable smart connect if the router supports it.🠊  
**5\.** Change 2.4ghz channel(1/6/11) and channel width(20Mhz). Change 5ghz channel(band 1/4) and channel width(40Mhz) 🠊  
**6\.** If the above steps are not helpful, please collect information and escalate to SE or arrange an RMA🠊

【Information Collection】  
**1\.** When does the issue start and how frequent is it? 🠊  
**2\.** How many devices experience unstable wireless connection issues and what are they?🠊  
**3\.** Which band has a dropping issue (2.4G or 5G)? 🠊  
**4\.** Led status on the router when the internet drops? 🠊  
**5\.** How do clients reconnect after a disconnection? Will they automatically reconnect or do we need to reboot the router?🠊  
**6\.** Does the Wireless Network name disappear when dropping?🠊

## **WR37. Slow Loading of Websites and Video Content video** 

【Troubleshooting Steps】  
**1\.** Please change the DNS server on the router to 8.8.8.8/8.8.4.4 for a test🠊  
**2\.** Please ensure the clients are connected to router directly🠊  
**3\.** Please turn off Qos/VPN clients on the routers for a test🠊  
**4\.** If there is other network extenders, such as WiFi extender/managed switch, please suggest unplugging them for a test🠊  
Note: If the user has other network extenders but refuse to unplug them for a test. Please check the Ethernet cable connection to avoid network loops.  
**5\.** Please confirm whether the issue only occurs in wireless or in both wired and wireless.  
**a. Wireless only:**  
Please change the wireless channel for a test. 2.4G channel 2/6/10, channel width 20MHz, 5G switch a different band, change to 80MHz🠊  
**b. Both wired and wireless.**  
Please connect the wired computer to the ISP modem for a test🠊  
If the ISP modem has the same issue, please suggest contacting ISP for further help🠊  
If the ISP modem is the normal, please record the IP address and mac address on the computer when connected to the modem. Then do a Mac Clone on the router for a test🠊  
**6\.** Restart the router for a test🠊

If the issue remains or issue still happens intermittently, please collect the information and escalate to SE.  
【information collection】  
**1\.** Troubleshooting steps results  
**2\.** The frequency of the issue.  
**3\.** TP-Link device Model, HW, FW:  
**4\.** The devices affected.

## **WR38. Live steam/real-time video conferences unstable**

【Troubleshooting Steps】  
**1\.**  Make sure the router updated to the latest firmware 🠊  
**2\.** Make sure the affected device is not in Parental Control/VPN client profile 🠊  
**3\.** Please change the WAN DNS to 8.8.8.8 or 8.8.4.4 🠊  
**4\.** Change 2.4ghz channel (1/6/11) and channel width(20Mhz). Change 5ghz channel (band 1/4) and channel width(80Mhz) 🠊  
**5\.**  If the affected clients are wireless and support 5G, please connect the clients to 5G for a test🠊  
**6\.** Adjust the router's location and antenna. Refer to [FAQ 455](https://www.tp-link.com/us/support/faq/455/) 🠊  
**7\.** If possible, please move the clients closer to the router for a test. 🠊

Suggest the user observe the issue for a few days after the above troubleshooting. If the issue remains, please collect the information and escalate to SE.  
【Information Collection】  
**1\.** Troubleshooting results of each step 🠊  
**2\.** FW version (upgrade the FW first if it's not up to date) 🠊  
**3\.** Is the video conference/live stream just lagging or disconnecting completely? How about the frequency?  🠊  
**4\.** The model of the clients 🠊

## **WR39. The router's power light flashes and restarts automatically**

【Troubleshooting Steps】  
**Case1: Loop restart/Can't power on/Stuck in starting up**   
**1\.** Unplug the power adapter and all wired devices/USB devices, wait for 5 minutes, then power on the router again 🠊  
**2\.** If the issue remains, press the reset button for 5 seconds and see if the router responds. If it works, please guide the user to set up the router again 🠊  
**3\.** If reset no response, please try the firmware recovery. Refer to [FAQ1482](https://www.tp-link.com/us/support/faq/1482/) 🠊  
**4\.** (Option): If the user has an extra power adapter that has the same specification, please change the power adapter for a test. The user can find the specifications from the label on the power adapter 🠊

If the issue remains, please help RMA and ask senior if need to collect defective unit🠊

**Case2: Restart Intermittently (Every few days or multiple times a day)**  
**1\.** Make sure the router updated to the latest firmware🠊  
**2\.** If KMS has no Problem Notification, please collect the information and escalate to SE🠊

【Information Collection】  
**1\.** The frequency of restarting🠊  
**2\.** The model of clients. Is the USB connected? 🠊  
**3\.** FW version🠊

## **WR3A. No Internet on Some Clients Only**

【Troubleshooting Step】  
**1\.** Check if the router has configured a parental control profile/VPN client Profile for the device🠊  
**2\.** Check the IP address and gateway, and ensure the IP address is distributed by the wireless router🠊  
**3\.** Please turn off VPN or antivirus on the client device🠊  
**4\.** Determine the type of unstable clients who have stopped working🠊

**For wired devices.**  
**a.** Confirm if the device is connected to an IPTV port configured on the wireless router🠊  
**b.**Change the ethernet cable🠊  
**c.**Change the ethernet port on the wireless router and the device🠊

**For wireless devices.**  
**a.** Enable the guest network and connect the device to the guest network to have a comparison🠊  
**b.** Enable a hotspot Wi-Fi on a phone and connect the device to the hotspot Wi-Fi. If not working, contact the device's support.

**5\.** If the problem persists, collect information and forward it to SE

【Information collection】  
**1\.** Troubleshooting results  
**2\.** TP-Link device Model, HW, FW  
**3\.** When does the issue happen  
**4\.** The model of the Devices has issues

## **WR41. Slow Speed on Wired and Wireless Connections**

【Troubleshooting Steps】  
Wired or both wired and wireless speeds are low or not what was expected  
**Step 1:** Please identify the Ethernet port of the wireless router as 100Mbps or above. If it’s 100Mbps, the Speed test result would not exceed 100 Mbps. Please suggest changing the router to a Gigabit router 🠊  
**Step 2:** Check the WAN/LAN negotiation speed on the wireless router🠊  
**a.** WAN negotiation speed is abnormal (less than 1000Mbps):  
**1\.** Change Ethernet cable(above cat5e) between modem and router. Change the Ethernet port on the modem🠊  
**2\.** Force the WAN negotiation speed to 1000Mbps for a test on the Advanced-\>Network\>Internet page. (If the Internet drop after fixing the negotiation speed to 1000Mbps, please change it back to auto to restore the connection) 🠊  
**b.** WAN negotiation speed is normal(1000Mbps), but LAN negotiation speed is abnormal(less than 1000Mbps):  
**1\.** Change the Ethernet cable (above cat5e) between modem and PC🠊  
**2\.** Use another PC to test the speed again in case it's the PC's issue. Please make sure the PC is connected to the router directly🠊  
**Step 3:** Try to turn off the Qos and VPN client feature (For WiFi7 models, please change the Qos status for a test, if the user turned off the Qos, please set a Qos according to the Internet bandwidth and add tested device as high priority. If the Qos is turned on, please turn it off for a test) 🠊  
**Step 4:** Connect the PC directly to the modem and bypass the wireless router. Run a speed test using speedtest.net and record the link speed and download speed. (If the speed from the modem is closer to the TP router provided, suggest the user to contact the ISP) 🠊  
**Step 5:** Connect the wireless router back to the modem and connect the PC directly to the wireless router. Run a speed test using speedtest.net and record link speed and download speed🠊  
Please compare the speeds obtained in step 4 and step 5 (usually, the main deco’s wired speed should be 90%-100% of the modem’s)🠊  
**Step 6:** If the above steps are not helpful, please collect information and escalate to SE or arrange an RMA🠊

【Information collection】  
**1\.** Troubleshooting steps results 🠊  
**2\.**  ISP bandwidth 🠊  
**3\.** Are all devices affected? What are they and how are they connected to the router? 🠊  
**4\.** The download speed and link speed the PC gets when directly connected to the modem🠊  
**5\.** The download speed and link speed the PC gets when directly connected to the wireless router🠊  
**6\.** Screenshot of negotiation WAN/LAN speed of the router 🠊  
**7\.** QoS settings screenshots🠊

## **WR42. Slow Speed on Wireless Connection**

These troubleshooting steps are only suitable for wireless low speed. If the wired connection has slow speed as well, please refer to WR41.

**【Troubleshooting Steps】**  
**1\.** Please identify the Ethernet port of the wireless router as 100Mbps or above. If it’s 100Mbps, the Speed test result would not exceed 100 Mbps. Please suggest changing the router to a Gigabit router🠊  
**2\.** Check and disable QOS🠊  
**3\.** Change 6ghs channel width 320Mhz. Change 5ghz channel width 80MHz/160Mhz. Change 2.4ghz channel width 40Mhz.  Note: Unless users report that 2G speed is slow, there is no need to test 2G speed🠊  
**4\.** Adjust antennas and router's location, refer to [FAQ 455](https://www.tp-link.com/us/support/faq/455/)🠊  
**5\.** Locate a smartphone/laptop 2-3 meters away from the router and connect to the router's 5ghz or 6ghz wifi to run a speed test. Record the speed test result and link speed.(For PC/some Android smartphone, please refer the [FAQ 2265](https://www.tp-link.com/us/support/faq/2265/) to check the speed)🠊  
**6\.** Compare the actual download speed and link speed, and confirm if the download speed is normal. (Note: Actual download speed should be 40%-50% of link speed on 5ghz and 30%-50% on 2.4ghz)🠊  
For iPhone smartphone, please refer to [KMS](https://kms.tplink.com/kms/multidoc/kms_multidoc_knowledge/kmsMultidocKnowledge.do?method=view&fdId=191c207bb1670494c220dee4dc48070d) to check the max link speed, then judge if the actual speed is normal or not🠊  
(If there is a new model that can't check link speed, please feedback to senior)  
**7\.** If the download speed is normal, please explain to the user. If the download speed is abnormal, please refer to the below methods  
  **a.** Change 5ghz channel(band 1/4), Change 2.4ghz channel(1/6/11)🠊  
  **b.** Suggest update FW🠊  
**8\.** If the above steps are not helpful, please collect information and escalate to SE or arrange an RMA.

【Information collection】  
**1\.** Troubleshooting steps results🠊  
**2\.**  ISP bandwidth🠊  
**3\.** Are all devices affected? What are they and how are they connected to the router?🠊  
**4\.** The download speed and link speed of 2.4ghz the phone/laptop gets when directly connected to the router's 2.4gzh wifi🠊  
**5\.** The download speed and link speed of 2.4ghz the phone/laptop gets when directly connected to the router's 5gzh wifi🠊  
**6\.** How many speed the wired devices can get from the router?🠊  
**7\.** The screenshot about QoS setting🠊

## **WR43. Slow speed on EasyMesh Satellite devices**

【Troubleshooting Steps】  
Before testing the speed near the satellite devices (such as range extender, easymesh routers), please ensure the main router provides normal speed. If main router's speed is slow, please refer to WR41Low Speed on Wired and Wireless Connections  
**Case 1: Easymesh satellite devices connect to main router via wireless connection.**  
**Step 1:** Power off all satellite devices. Put a laptop/smartphone at the location of issue satellite deco, and connect it to the main router's Wi-Fi. Do a speed test and record the download speed and link speed🠊  
**Step 2:** Power on the issue satellite devices, connect the same Laptop/smartphone to its Wi-Fi, do a speed test, and record the download speed and link speed🠊  
**Step 3:** Compare the speed result in step1 and step2. If the download speed of step2 is higher than 50% of that in Step 1, the speed is normal🠊  
**If satellite device speed is normal, please explain to the user:**  
*The Easymesh Satellite units need to transfer the Wi-Fi signal from the main unit, and transformation would make the speed slower, so, normally, the slave unit speed is not as fast as the main. The Satellite units play the role of a range extender to kill the dead-end of your house. However, since it needs to get the receiving signal from the main unit, the speed depends on the quality of the receiving signal.*  
**If satellite Deco speed is abnormal, please try the below methods.**  
**1\)** Check signal strength. Go to Advanced \>Easymesh \>  check the signal strength and link speed of satellite devices🠊  
If signal strength is weak: Suggest moving closer to the main router, and place it at the same height as the main router if they are on the same floor or wired connection🠊  
**2\)** Move the issue satellite device to an open position without any household appliances or metal products around it, and test speed again🠊  
**Step 4:** If still abnormal, collect and forward to SE.

**Case 2: Easymesh satellite devices connect to main router via wired connection**  
**Step1:** Please check the ethernet status on the main router, if the wired link speed of the port connected to satellite device is only 100Mbps, please change a different cable for a test🠊  
**Step2:** Adjust antennas and satellite device's location, refer to [FAQ 455](https://www.tp-link.com/us/support/faq/455/) 🠊  
**Step3:** Locate a smartphone/laptop 2-3 meters away from the router and connect to the satellite device's 5ghz wifi to run a speed test. Record the speed test result and link speed.(For PC/some Android smartphone, please refer the [FAQ 2265](https://www.tp-link.com/us/support/faq/2265/) to check the speed)  
**Step4:** Compare the actual download speed and link speed, and confirm if the download speed is normal. (Note: Actual download speed should be 40%-50% of link speed on 5ghz and 30%-50% on 2.4ghz) 🠊  
For iPhone smartphones, please refer to the [KMS](http://kms.tplink.com/kms/multidoc/kms_multidoc_knowledge/kmsMultidocKnowledge.do?method=view&fdId=191c207bb1670494c220dee4dc48070d) to check the max link speed, then judge if the actual speed is normal or not. 

 (If there is a new model can't check the link speed, please give feedback to senior )  
 If the above steps are not helpful, please collect information and escalate to SE or arrange an RMA.  
【information collection】  
**1\.** Actual speed and link speed when clients are connected to the satellite deco🠊  
**2\.** Distance, obstacle between main and satellite🠊  
**3\.** how many units in total🠊  
**4\.** network topology🠊  
**5\.** Screenshots of signal strength/link speed on Advanced-\>Easymesh page🠊

## **WR44. Slow speed on specific devices**

【Troubleshooting Steps】

**Step1:** Please check the VPN clients/Parental Control/Speed limits settings on the router. Ensure no limits for this clients. 🠊  
Note: You can find the speed limits settings in the client list page🠊  
**Step2:** Please turn off VPN software on the clients🠊  
**Step3:** Please confirm the wireless band of the client speed test, and test the speed in the 5G or 6G band if possible🠊  
**Step4:** Please ensure the driver version/Phone OS is the latest one🠊  
**Step5:** If the issue remains, please suggest the user comparing the speed with other routers.🠊

If this device has the same speed with other routers, please suggest contacting device support🠊

If this device can obtain normal speed with other routers, but the speed is abnormal when connected to TP routers, please collect the information and escalate to SE.  
【information collection】

**1\.** Troubleshooting steps results🠊  
**2\.**  ISP bandwidth. And the normal speed of other clients🠊  
**3\.** Actual speed and link speed of clients🠊  
**4\.** The model of this devices🠊

## **WR54. Port Forwarding**

【Collecting the following info before configuration or troubleshooting】  
**1\)** The reason why cx wants to open ports🠊  
**2\)** For what device, software, or game🠊  
**3\)** What's the port number cx wants to open🠊  
  \-\>if cx has no idea about port info, ask cx to contact device support.  
  \-\>if cx has this info, follow up by email 

For configuration, refer to [FAQ1379](https://www.tp-link.com/us/support/faq/1379/)  
**\--**If there is any stuck when set up, collect screenshots.

If cx finished the configuration but failed to access the server，  
**1\)** Check if cx can access that server in the local network via IP address and port number  
**\--No**, follow via email and collect the screenshot of the settings  
**\--yes**, go to step 2\)  
**2\)** What's the WAN IP of the router, refer to [FAQ785](https://www.tp-link.com/us/support/faq/785/) Tip1🠊  
**\--private IP**, suggest cx contact ISP or open the ports on the front-end router🠊  
**\--public IP**, check the IP settings on the client🠊  
(The IP should be the same subnet as the router, and the gateway on the client's setting should be the router's LAN IP address)  
**3\)** If cx used the Windows PC to access, disable the PC's firewall (refer to [FAQ785](https://www.tp-link.com/us/support/faq/785/) Tip2)🠊  
**4\)** Collect info and then escalate:  
\>the topology of the internet, ISP info  
\>screenshots of WAN IP address and settings  
\>screenshots when failed to access the server

## **WR56.IPv6 Setup**

**1\)** If CX has activated IPv6 service from ISP 🠊  
**2\)** Check IPv6 WAN connection type 🠊  
   \-\> If it is static IP, escalate to VIP  
**3\)** check if IPv4 internet is working and IPv4 WAN IP address 🠊  
**4\)** follow up by email, refer to [KMS 000526](https://kms.tp-link.com/kms/multidoc/kms_multidoc_knowledge/kmsMultidocKnowledge.do?method=view&fdId=187c5ed436f235d5c83f7dd41f4b91ae)

## **WR57. VPN Related**

Not configured yet or already configured? 

**1\.** Not configured, ask CX want VPN Server or VPN Client?  
\*\*Confirmed the model support VPN feature first: SOHO: per UG.  
\*\* The model CX has doesn't support the VPN CX need, tell CX online.

\*\* When the model supports VPN:  
**1.1** For【VPN server】   
\>\> Follow by email-Ticket Marco 【Tem1-Setup VPN Server】  
\>\> TK ID:

**1.2** For【VPN Client】   
\>\> Record the VPN server name (Nord/Express etc.)  
\>\> Follow by email-Ticket Marco 【Tem2- Setup VPN Client】  
\>\> TK ID:

**1.3** If CX not sure which VPN is needed   
\>\> Follow by email-Ticket Marco 【Tem3-Need VPN Connection but not sure server or client】  
\>\> TK ID:

**2\.** Already configured: Collect info and follow by email  
【Collect info】refer to KMS【[VPN SOP](https://kms.tp-link.com/sys/attachment/sys_att_main/sysAttMain.do?method=view&fdId=1910bd2f04dfd903cd334ae41ffb6deb)】  
**2.1** Describe user demands (VPN server or VPN client);  
**2.2** Record the Problem phenomenon;  
**2.3** Where the user based;  
\>TK ID:

## **WR5A. Block/Unblock Device**

**【HDD Cannot Be Recognized】**   
**1\)** Check if the HDD can work with computer 🠊  
**2\)** Does it work fine with other HDD 🠊  
**3\)** It used to work fine? 🠊  
   \-\>If yes, format the HDD and check again 🠊  
     If it still does not work, escalate to HQ with model of the HDD  
**4\)** Check the capacity and format type of the HDD 🠊  
**5\)** Does the HDD need an external power supply 🠊  
Follow up by email, Collect HDD details and escalate to VIP. [FAQ2289](https://www.tp-link.com/us/support/faq/2289/) or [KMS000528](https://kms.tp-link.com/kms/multidoc/kms_multidoc_knowledge/kmsMultidocKnowledge.do?method=view&fdId=187c5efa1793badf6f2a6bf4976b3bbe)

**【Some files on HDD cannot be recognized】**   
How to access those files 🠊

**Case 1: Via SMB** (\\\\192.168.0.1) or FTP (ftp://192.168.0.1)  
**a)** Check capacity of HDD 🠊  
**b)** Is the partition encrypted? 🠊  
**c)** Are there any specific files canot be accessed 🠊  
**d)** Collect info and escalate by referring [KMS000528](https://kms.tp-link.com/kms/multidoc/kms_multidoc_knowledge/kmsMultidocKnowledge.do?method=view&fdId=187c5efa1793badf6f2a6bf4976b3bbe)

**Case 2: Via Media Server on computer**  
**a)** Confirm if the lost file are media files?  
\-\>Media Server can only recognize media files and the maximum number of media file is 10000\. Please suggest cx to access files Via SMB{Samba) (\\\\192.168.0.1) with [FAQ 253](https://www.tp-link.com/us/support/faq/253/) If the media server cannot access the whole media file.

## **WR71. Cannot Receive Activation Email**

Please refer to [FAQ1127](https://www.tp-link.com/us/support/faq/1127/)  
**Note:**  
Avoid suggesting cx to delete their TP-Link ID actively, as it could easily lead to cx complaints when they find all metadate no longer accessible anymore after deleting TP-Link ID.  
When cx delete their cloud account (e.g. Tether, Deco, Kasa, Tapo, tpCamera, www.tplinkcloud.com, Forum ID, etc.), they will permanently lose all metadata that is associated with the cloud resources, and they will no longer be able to revert them or restore any cloud-specific metadata even if they re-register the cloud again with the same cloud account credentials.  

## **WR73. Reset Password of TP-Link ID**

Please refer to [FAQ1442](https://www.tp-link.com/us/support/faq/1442/)  
**Note:**  
Avoid suggesting cx to delete their TP-Link ID actively, as it could easily lead to cx complaints when they find all metadate no longer accessible anymore after deleting TP-Link ID.  
When cx delete their cloud account (e.g. Tether, Deco, Kasa, Tapo, tpCamera, www.tplinkcloud.com, Forum ID, etc.), they will permanently lose all metadata that is associated with the cloud resources, and they will no longer be able to revert them or restore any cloud-specific metadata even if they re-register the cloud again with the same cloud account credentials.  

## **WR74. Change TP-Link ID**

Currently, only Deco App supports changing owner TP-Link ID [FAQ2957](https://www.tp-link.com/us/support/faq/2957/).  
For other products, to change the TP-Link ID bound to your device, please hard reset your device to factory defaults and then set it up again to bind it to your new TP-Link ID.

**Note:**  
Avoid suggesting cx to delete their TP-Link ID actively, as it could easily lead to cx complaints when they find all metadate no longer accessible anymore after deleting TP-Link ID.  
When cx delete their cloud account (e.g. Tether, Deco, Kasa, Tapo, tpCamera, www.tplinkcloud.com, Forum ID, etc.), they will permanently lose all metadata that is associated with the cloud resources, and they will no longer be able to revert them or restore any cloud-specific metadata even if they re-register the cloud again with the same cloud account credentials.  

## **WR75. Delete TP-Link ID**

Delete TP-Link ID  
Please refer to: [FAQ2629](https://www.tp-link.com/us/support/faq/2629/)  
**Note:**  
Avoid suggesting cx to delete their TP-Link ID actively, as it could easily lead to cx complaints when they find all metadate no longer accessible anymore after deleting TP-Link ID.  
When cx delete their cloud account (e.g. Tether, Deco, Kasa, Tapo, tpCamera, www.tplinkcloud.com, Forum ID, etc.), they will permanently lose all metadata that is associated with the cloud resources, and they will no longer be able to revert them or restore any cloud-specific metadata even if they re-register the cloud again with the same cloud account credentials. 

## **WR81. Tether App Cannot Find TP-Link Device**

【Troubleshooting Steps】

**Step 1:** Upgrade the firmware of the device and make sure the Tether App is the latest version🠊  
**Step 2:** Ensure the smartphone is connected to wireless router's Wi-Fi correctly and get IP address from the router🠊  
**Step 3:** Disable mobile data and VPN connection on the phone if any🠊  
**Step 4**: Check the compatibility list. Tether does not support all TP-Link devices. Some devices need to open some ports to be [compatible with Tether](http://www.tp-link.com/tether_compatibility_list/).   
**Step 5:** Reboot the device and Tether🠊  
**Step 6:**  If the above steps are not helpful, please collect information and escalate to SE🠊

【Information collection】  
**1\.** Model of the router and APP version 🠊  
**2\.** Troubleshooting steps results🠊  
**3\.** Can the admin web UI work properly?🠊  
**4\.** Follow the FAQ 3916 to collect the APP logs🠊

## **WR82. Incorrect Password When Logging in Device**

【Troubleshooting Steps】

**Case 1: The user can login the admin web UI via the same admin password, but fail to login in the Tether APP**  
**Step 1:** Double check the password, make sure the password is correct. Ensure the smartphone is connected to wireless router's Wi-Fi correctly and get IP address from the router🠊  
**Step 2:** Disable antivirus /VPN software on the phone🠊  
**Step 3:** Change a different smartphone for a test if possible🠊  
**Step 4:** Reboot the device and Tether🠊  
**Step 5:** If the above steps are not helpful, please collect information and escalate to SE🠊

【Information collection】  
**1\.** Model of the router and APP version🠊  
**2\.** Troubleshooting steps results🠊  
**3\.** Follow the [FAQ 3916](https://www.tp-link.com/us/support/faq/3916/) to collect the APP logs🠊

**Case 2: The user forget the admin password, he can't login admin web UI and Tether APP.**  
The administrator password is the password that the user sets the router for the first time. If the user forgets it, the user can only Factory Reset the router, and then set a new password

## **WR84. Client List Displays Wrong Client Number**

【Troubleshooting Steps】

**Step 1:** Please update the latest firmware for router and latest APP version🠊  
**Step 2:**  Connect the smartphone to the router's wireless for a test🠊  
**Step 3:** Reboot the router and Tether APP🠊  
**Step 4:** If the above steps are not helpful, please collect information and escalate to SE🠊

【Information collection】  
**1\.** How many clients does the user have? How many clients does the APP display?🠊  
**2\.** Can the admin web UI display the correct client number?🠊  
**3\.**Are there any other network extenders? Like RE, managed switch. How they are connected?🠊  
**4\.** Model of the router and APP version🠊  
**5\.** Troubleshooting steps results🠊  
**6\.** Follow the [FAQ 3916](https://www.tp-link.com/us/support/faq/3916/) to collect the APP logs🠊

## **WR85. Failed to Block Unknown Clients**

【Troubleshooting Steps】

**Step 1:** Double check the Mac address in the block list and unknow device, make sure the Mac address is the same🠊  
**Step 2:**  Added the devices in the admin web UI's access control for a test🠊  
**Step 3:** Please unplug other network extender for a test, like range extender🠊  
**Step 4:** If the above steps are not helpful, please collect information and escalate to SE🠊

## **WRA1. No Power**

\* Check if there is LED Button (If yes, press it)🠊  
\* Is the ORIG ADAPTER that comes with router being used? 🠊  
\* Is it plugged Surge Protector? (if so,plug to wall outlet) 🠊  
\* Plugged in different Power Outlet? 🠊  
\* Tried different Power Adapter if there's any 🠊  
\* Hard Reset 🠊  
\* Remove everything that is plugged to the device, then reboot/reset 🠊

Ask if there are any instances that will disqualify from RMA?  
\* Storm/Lightning 🠊  
\* Recent Power Outage? 🠊  
\* Any recent Failed FW update 🠊

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **WRA2. Bad Ports/buttons**

**Case 1: Bad Buttons**  
No need to do TS; provide RMA if qualified.

**Case 2: Bad Port**  
**1\.** If the bad port is a LAN port, please try the following steps to troubleshoot:  
   **1\)** Try to use another Ethernet cable to test if the issue is with the Ethernet cable  
   **2\)** If the issue is still the same with another Ethernet cable, please connect your client device to another LAN port on the TP-Link device to do a comparative test. If another LAN port works fine with the same Ethernet cable and the same client device, that means this specific LAN port is broken.  
**2\.** If the bad port is a WAN port, refer to [FAQ2982](https://www.tp-link.com/support/faq/2982/) to troubleshoot:

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **WRA3. Broken Parts(Antenna etc.)**

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **WRA4. Abnormal LEDs/No respond to reset**

\*Record the status or changes of the LED on TP-Link device  
Note:if all the lights are off, refer to "no power" issue to troubleshoot🠊  
\*unplug all the Ethernet cable from TP-Link device🠊  
\*try to reboot🠊  
\*follow the user guide to reset the TP-Link device🠊

**\-Ask if there are any instances that will disqualify from RMA?**  
\* Storm 🠊  
\* Recent Power Outage? 🠊  
\* Any recent Failed FW update 🠊

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **WRA5. WiFi Broken**

**1\.** Check if all of the clients can’t see the SSID or only some certain devices can’t see the SSID🠊  
**2\.** If only some certain devices can’t see the SSID, please follow [FAQ2597](https://www.tp-link.com/support/faq/2597/) to troubleshoot🠊  
**3\.** If all clients cannot see the SSID of TP-Link device, check if Wi-Fi lights on TP-Link device are on🠊  
**4\.** If Wi-Fi lights are off, follow the User Guide to press the Wi-Fi button to enable the Wi-Fi radio🠊  
**5\.** If Wi-Fi lights are on, follow the User Guide to Hard Reset the device🠊

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **WRA6. Random Auto Reboot/Reset**

\* Is the ORIG ADAPTER that comes with router being used? 🠊  
\* Is it plugged Surge Protector? (if so,plug to wall outlet) 🠊  
\* Plugged in different Power Outlet? 🠊  
\* Tried different Power Adapter if there's any 🠊  
\* Hard Reset 🠊  
\* Remove everything that is plugged to the device, then reboot/reset 🠊

**Ask if there are any instances that will disqualify from RMA?**  
\* Storm/Lightning 🠊  
\* Recent Power Outage? 🠊  
\* Any recent Failed FW update 🠊

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **WRA7. Overheating**

**If the device can still work normally when overheated?**  
**1\.** Yes, the device is still working fine🠊  
**1.1** Provide explanation via email, using Ticket Marco【Overheated 1-Device works fine】🠊

**1.2** If CX insists that the device is very hot and is seriously worried about the device safety, can provide RMA accordingly.

**2\. No, router is having issue when overheated:**  
**2.1** Collect the following info:  
\* What’s the issue ( low speed, unstable/no internet, or others) 🠊  
\* DOP and When issue starts 🠊  
\* Using original power adapter?🠊   
\* Where the device was used (in the kitchen, bedroom, living room, etc.) 🠊

**2.2** Provide suggestions via email, using using Ticket Marco【Overheated 2-Device has issue】🠊

**2.3** If device still have issue when overheated and working properly when cooling down, can provide RMA under warranty.

\*\*\*RMA If Qualified \*\*\*Record information below:  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **WRA8. Other Hardware Issue**

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## ***Unstable Wired and Wireless Connections***

***Probing questions:***  
***1\)** Was the router working fine before 🠊*  
***2\)** Date of Purchased and When the Issue started? 🠊*  
***3\)** Is it happening on both wired and wireless devices? 🠊*  
*If wireless only follows **WR34.Unstable Wireless Connection,***  
*if wired and wireless or cx is not sure , **PROCEED***

***4\)** Do you have internet access right now? 🠊*

***4a)If CX has internet right now** \> follow by email and collect the info below when the issue happens. Consult Sup/L2 after collecting the info below.*

*【Collect info】*  
***A.Does the modem has a stable connection?🠊***  
*Did you test it by connecting your computer directly to the modem via an Ethernet cable for a while?🠊*  
*If not, how can you say that the modem is working properly?**🠊***  
*(If cx does not have a way on connecting to the modem directly,you can skip it)*

***B. What devices experience unstable connection issues? (Collect the model, brand, OS version, and Driver version for desktop and laptop)🠊***  
*Do all 2.4G, 5G and the wired connection have issues?🠊*  
***C. How often does the dropping of internet connection happen?🠊***  
   *Is there any large program running when the internet drops?🠊*  
***D. How about the internet LED status of the router when drops out?🠊***  
*\---Internet led is on green🠊*  
*\---Internet led is on orange/red🠊*  
*\---Internet led is off🠊*  
***E. How do you recover the internet connection? 🠊***  
  *Do you need to reboot the router?🠊*

***\-ˋˏ✄┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈***  
***4b)If CX has no internet now, try to log into the web interface***  
   ***4ba. able to log in to web UI, check the WAN IP, DNS, GW🠊***  
   *\> if Public WAN IP, change DNS on the router**🠊***  
   *\> if No WAN IP/private IP, save the sys log after the router runs for a while**🠊***  
   *\> Upgrade FW**🠊***  
   *\> Brand new\>Escalte VIP Ticket ID XXX*  
    *otherwise， consult L2* 

   ***4bb.Unable to log in to web UI, check all lights status-\>check hardware connection***  
    *\> disconnect the modem from the router**🠊***  
    *\> Check Ip/GW on end-device**🠊***  
    *\> Ping router's IP/GW**🠊***  
    *\> if ping failed or obtains invalid IP, Brand new\> Escalate*  
     *otherwise，consult L2*

## **RE11. Unable to Login Web-based Interface**

Please Refer to [FAQ1398](https://www.tp-link.com/us/support/faq/1398/) and [FAQ673](https://www.tp-link.com/us/support/faq/673/) \~

## **RE12. How to Set up Range Extender?**

Refer to Video /[FAQ 1400](https://www.tp-link.com/us/support/faq/1400/)/[874](https://www.tp-link.com/us/support/faq/874/)/[1373](https://www.tp-link.com/us/support/faq/1373/)

**Note:** If the App says "No Host Connection", it's probably because the router's 5G is using the DFS channel, follow up via e-mail and suggest the cx to disable Band Steering on the router, change 5G channel to Band 1(36, 40, 44, 48). If still the same, collect the router's model, system log, and escalate.

## **RE13. Cannot See Router's WiFi When Settings up Extender**

【Troubleshooting Steps】

**Step 1：** Ensure all Wi-Fi bands (2.4Ghz&5Ghz&6Ghz) of the home router are turned on and broadcast normally. Make sure a smartphone or laptop can detect the home router signal🠊

**Step 2:**  Click on retry on the Wi-Fi connection page🠊

**Step3:** Reset the range extender and use WPS to configure🠊

**Step 4:** Confirm which bands cannot be detected🠊  
**a. 2.4Ghz:** Change the router's wireless channel into 1/6/11  
**b. 5Ghz:** Ensure the wireless router is not working on the DFS channel. Fix the 5Ghz channel into band 1(32-48)  
**c. 6Ghz:** The discovery of the 6G signal is influenced by local 6G policies and the country code set on 6G devices. If the user's other devices can detect a 6GHz WiFi signal, kindly escalate the issue to SE (Support Engineer) while gathering details such as the ISP, router model, phone/laptop model capable of detecting the router's 6GHz signal, and the information label from the range extender.

**Step 5:** Confirm if the range extender can detect other wifi signals such as the phone hotspot. If there is no wifi signal detected at all, please arrange RMA🠊

## **RE14. RE Light is off after Setup**

(All 2.4G,5G,6G are off）

【Troubleshooting Steps】  
**Step 1:** Verify the user selects and correctly enters the Home WiFi name and password on the range extender🠊  
**a.** By forgetting Wi-Fi and reconnecting to the home Wi-Fi, enter the password again.  
**b.** On iPhone, go to WLAN-\> highlight the connected network name, and enter the iPhone's password to see the password.

**Step 2:** Confirm no settings on the router to block/pause the internet of the Extender, such as Parent Control, Mac Filtering, or Access Control🠊

**Step 3:** Suggest modifying the following wireless setting on the Main router if possible. It will help us to locate which band has a connection issue with the router🠊  
**a.** give different names for 2.4G and 5G Wi-Fi on the Main router🠊  
**b.** fix the 2.4G channel to channel 1, 5G to channel 36.🠊

**Step 4:** Guide to locate the Extender close to the Router, in the same room as the router🠊

**Step 5:**  Reset the Extender🠊

**Step 6:** Re-configure the Extender again. Use different method to set up, such as QS or WPS🠊

If the above methods are not helpful, please collect information and escalate to SE or arrange an RMA.

**【Information Collecion】**  
Where the Extender is placed. And where the main router is placed？🠊  
The LED status on the Extender🠊  
Above troubleshooting results🠊  
Log into the Extender with the Tether APP. Get and record the FW version🠊  
Get the Router's Model, better to have a Picture of the Label on the router/modem router🠊

## **RE15. RE Light is on but No Internet after Setup**

(If only whether it's 2.4G, 5G, 6G, or both, depending on the band the user is concerned about)

**Note:**  When dual-band RE establishes EasyMesh with VX1800v, TP3 Router, and other brand Router, only one band will connect to the router, which means 2.4G or 5G LED is off after setup.

【Troubleshooting Steps】

**Step 1\.** Check if the router has internet🠊  
**Step 2\.** Confirm no settings on the router to block the internet of the Extender, such as Parent Control, Mac Filtering, or Access Control🠊  
**Step 3\.** Connect a laptop/phone to the main router. Check the IP and default gateway addresses on the laptop/phone. (such as IP 192.168.X.100, GW192.168.X.1)🠊  
**Step 4\.** Refer to [FAQ2965](https://www.tp-link.com/en/support/faq/2965/) to set static IP and DHCP server on the Extender 🠊  
**Step 5\.** Restart the main router and the extender. Wait 1-2min. （RE605X V3/ RE700X V1 /RE705 V1 /RE715X V1 may take 3-4Min.）🠊

If the above methods are not helpful, please collect information and escalate to SE or arrange an RMA🠊  
**【Information Collecion】**  
1\. Where the Extender is placed. And where the main router is placed？🠊  
2\. The LED status on the Extender🠊  
3\. Above troubleshooting results🠊  
4\. Log into the Extender with the Tether APP. Get and record the FW version🠊  
5\. Get the Router's Model, better to have a Picture of the Label on the router/modem router🠊

## **RE16. AP Mode Setup**

RE will transform the wired network into a wireless one in AP mode.

Refer to [FAQ1401](https://www.tp-link.com/us/support/faq/1401/) to set up an Access Point for RE.

## **RE18. No Internet on Some Clients Only**

Only one device cannot connect to RE

**1\. If RE has same name as router**  
\>suggest re-install with different SSID 🠊

**2\. RE has a different wifi name as a router**  
\>Check signal strength🠊  
\>forget RE's WIFI and reconnect it🠊  
\>Check if the device works with main router or other wifi🠊  
\>suggest locating the device closer to RE🠊  
\>Check the IP address and default gateway🠊  
\>Collect Model of the device🠊  
If the device works with other wifi, not work with us,cx has contacted device's support🠊  
\*firmware should be latest-xxx  
\*escalate VIP Ticket ID XXX-

## **RE21. Cannot See WiFi Signal**

Please refer to [FAQ3586](https://www.tp-link.com/us/support/faq/3586/)

## **RE22. Unable to Connect WiFi**

No Internet on some Clients Only, please refer to RE32

No internet on all clients, please refer to RE15

## **RE24. Poor WiFi Range**

Please refer to [FAQ3103](https://www.tp-link.com/en/support/faq/3103/)

【Troubleshooting Steps】  
**Step 1:**  Ensure your range extender is placed in a central location in your home or office to maximize coverage. Avoid placing it near thick walls, metal objects, or appliances that can interfere with the signal🠊  
**Step 2:** Adjust antennas for optimal signal distribution. Position them vertically for a more balanced coverage🠊  
**Step 3:** Make sure your range extender's firmware is up to date. Check the manufacturer's website for the latest firmware updates and install them to potentially improve performance🠊

【Information collection】  
**1\.** Collect the floor plan， mark the positions of the RE and router, and take a photo of the area around the RE location🠊  
**2\.** Troubleshooting results🠊

## **RE31. Extender Stopped Working (Was Working Before)**

【Troubleshooting Steps】

**Step 1\.** Ensure the wireless signal LED (2.4G/5G/6G) on RE is on. if only the power LED is OFF, please refer to RE14🠊  
**Step 2\.** Check if the router has internet🠊  
**Step 3\.** Confirm no settings on the router to block the internet of the Extender, such as Parent Control, Mac Filtering, or Access Control🠊  
**Step 4\.** Restart the main router and the extender. Wait 1-2min. （RE605X V3/ RE700X V1 /RE705 V1 /RE715X V1 may take 3-4Min.）🠊  
**Step5.** Reset and reconnect the extender to the router🠊

If the above methods are not helpful, please collect information and escalate to SE or arrange an RMA.  
【Information Collecion】  
**1\.** The LED status on the Extender🠊  
**2\.** The screenshot of the status page on the range extender's Web UI  
The IP address, Gateway, and DNS information on the wireless device connected to range extender wifi🠊  
**3\.** The IP address, Gateway, and DNS information on the wireless device connected to the wireless router🠊  
**4\.** Above troubleshooting results🠊  
**5\.** Log into the Extender with the Tether APP. Get and record the FW version🠊

## **RE32. Unstable Wired and Wireless Connections (RE light turns off )**

Recommended settings on the host router to work well with TP-Link Range Extenders: [https://community.tp-link.com/en/home/stories/detail/501914](https://community.tp-link.com/en/home/stories/detail/501914)

【Troubleshooting Steps】

**Step1.** Ensure the SSID of the range extender is different from the router's. If it's the same, suggest the user reset and reconfigure, and change the SSID of the range extender🠊

**Step2.** Check the signal light on the range extender🠊  
 **a. GREEN**, and the 5ghz or 2.4Ghz RE light is off, suggest the user fix the 5ghz channel(band 1\) and 2.4ghz channel(1/6/11) on the router🠊  
 **b. RED** , move the range extender closer to the router 🠊  
 **c. OFF** , suggest the user fix the 2.4ghz channel into 1/6/11 and the 5ghz channel into band1🠊

**Step3.** Make sure the firmware of the range extender is up to date🠊  
**Step 4\.** Reset and reconfigure the range extender🠊

If the above steps are not helpful, please collect information and escalate to SE or arrange an RMA。

【Information collection】

**1\)** Troubleshooting result🠊  
**2\)** The model of the main Router🠊  
**3\)** When does the issue start?🠊  
**4\)** How often does it happen?🠊  
**5\)** If the issue ever self-recovers🠊

## **RE33. Unstable Wired and Wireless Connection (RE light stays on)**

Recommended settings on the host router to work well with TP-Link Range Extenders: [https://community.tp-link.com/en/home/stories/detail/501914](https://community.tp-link.com/en/home/stories/detail/501914)

【Troubleshooting Steps】

**Step1.** Suggest upgrading FW to the latest one, and configuring different wifi names from the router on RE🠊  
**Step2.** Ensure the router is stable when the end devices connect to it by passing the RE🠊  
**Step3.** Check the IP address when the Client is connected to RE but no internet🠊

**1\)** The Gateway is not the same as the home router's: please refer to [FAQ2965](https://www.tp-link.com/en/support/faq/2965/) to set static IP and DHCP server on the Extender:   
**Note:** You can connect the same device to the router's wifi to check the gateway of it.

**2\)** Otherwise, collect information and escalate to SE 

【Information collection】  
**1\.** The screenshot of the status page on the range extender's Web UI🠊  
**2\.** The IP address, Gateway, and DNS information on the wireless device connected to range extender wifi🠊  
**3\.** The IP address, Gateway, and DNS information on the wireless device connected to the wireless router🠊  
**4\.** When does the issue start?🠊  
**5\.** What devices experience unstable issues?🠊  
**6\.** How often does it happen?🠊  
**7\.** Any error like "connected but no internet" ?🠊

## **RE34. Unstable Wireless Connection**

This troubleshooting is for unstable wireless connections. For wired connection issues, refer to Low Speed on Wired and Wireless Connections.

【Troubleshooting Steps】

**Step1.** Suggest upgrading FW to the latest one, and configuring different 2.4gzh and 5ghz wifi names from the router on RE🠊  
**Step2.** Make sure the range extender is away from wireless interference sources. Keep the router away from microwave ovens and other interference sources (refrigerators, ovens, Bluetooth devices, etc.)🠊  
**Step3.** Confirm only specific devices or all devices encounter unstable wireless connection. If only a specific one, please connect it to another wifi for a test🠊

【Information collection】  
**1\)** When does the issue start?🠊  
**2\)** What devices experience unstable wireless connection issues?🠊  
**3\)** Which band has issue(2.4G or 5G)?🠊  
**4\)** How often does it happen?🠊  
**5\)** Did you check the LED status when it dropped out signal? 🠊  
**6\)** Any error like "connected but no internet" ?🠊  
**7\)** Is the RE configured same wifi name as your main router?🠊

## **RE35. No Internet on Some Clients Only**

【Troubleshooting Step】

**Step1.** Check if the range extender has configured access control for the device or if the router set parental control/VPN for the device🠊  
**Step2.** Check the IP address and gateway, and ensure the wireless router distributes the IP address🠊  
**Step3.** Please turn off VPN or antivirus on the client device🠊  
**Step4.** Determine the type of unstable clients who have stopped working🠊

**For wired devices,** change the ethernet cable🠊

**For wireless devices.**  
**a.** Enable the guest network and connect the device to the guest network to have a comparison🠊  
**b.** Enable a hotspot Wi-Fi on a phone and connect the device to the hotspot Wi-Fi. If not working, contact the device's support.🠊

**Step5.** If the problem persists, collect information and forward it to SE

【Information collection】  
**1\.** Troubleshooting results🠊  
**2\.** TP-Link device Model, HW, FW🠊  
**3\.** When does the issue happen🠊  
**4\.** The model of the Devices has issues🠊

## **RE41. Slow Speed on Wired and Wireless Connections**

【Troubleshooting Steps】

**Step1.** Set a different 2.4ghz and 5ghz SSID from routers ([FAQ2540](https://www.tp-link.com/us/support/faq/2540/)&[FAQ1412](https://www.tp-link.com/us/support/faq/1412/))🠊  
**Step2.** check the status of the RE light. If the LED indicates poor signal quality, move the range extender closer to the router🠊  
**Step3.** Simplify network topology by connecting one end device to the RE, and do the speed test without doing any high bandwidth behaviors🠊  
**a.** In the RE's position, check the wireless speed of the phone connected to the router's 5G🠊  
**b.** In the RE's position, check the wired speed of a PC connected to RE's Ethernet port🠊  
**Step4.** Compare the speed in a and b🠊

If the speed in b is about 90%-100% of the speed in a, then the wired speed on the range extender is normal. Please explain to the user.

If the speed in b is less than 90% of the speed in a, please try to change the Ethernet cable for the PC or try another wired device to test the speed again.

(Note: please make sure the Ethernet port on the range extender supports 1Gbps)

**【Information collection】**  
**1\)** Troubleshooting results of all steps🠊  
**2\)** When does the issue start?🠊  
**3\)** How much speed is provided by the ISP?🠊  
**4\)** Download speed and link speed of the PC  when connected to the range extender🠊  
**5\)** Download speed and link speed of the phone when connected to the router's 5ghz wifi at the range extender's location🠊  
**6\)** What's the LED status on RE?🠊

## **RE42. Slow Speed on Wireless Connection**

【Troubleshooting Steps】

**Step1.** Set a different 2.4ghz and 5ghz SSID from routers ([FAQ2540](https://www.tp-link.com/us/support/faq/2540/)&[FAQ1412](https://www.tp-link.com/us/support/faq/1412/))🠊  
**Step2.** check the status of the RE light. If the LED indicates poor signal quality, move the range extender closer to the router🠊  
**Step3.** Simplify network topology by connecting one end device to the RE, and do the speed test without doing any high bandwidth behaviors🠊  
**a.** In the RE's position, check the wireless speed of the phone connected to the router's 5G🠊  
**b.**  In the RE's position, check the wireless speed of the phone connected to RE's 5G 🠊

**Step4.** Compare the speed in a and b🠊

**If the Download speed of b is around 40-50% of a**, Explain to cx referring:  
*A Range Extender extends WiFi coverage rather than enhancing speed. When the extender mediates communication between a router and devices, wireless speed decreases due to interferences. Performance is constrained by factors like size and antenna direction, with side signals weaker than front/back. Devices connected to the extender experience about a 50% decrease in wireless speed compared to a direct router connection, as data passes through two wireless segments: clients ↔ extender ↔ router.*

**If the Download speed of b is not around 40-50% of a**, please collect information and escalate to SE or arrange RMA

**【Information collection】**  
**1\.** Troubleshooting results of all steps🠊  
**2\.** Signal rate of the RE and the router🠊  
**3\.** Model number of the router and clients, the spec of the clients' adapter🠊  
**4\.** Download speed and link speed of the phone when connected to the range extender's 5ghz wifi at the RE's location🠊  
**5\.** Download speed and link speed of the phone when connected to the router's 5ghz wifi at the range extender's location🠊  
**6\.** ISP bandwidth🠊  
\*If cx has trouble finding link speed, all the above info collected can also be escalated

## **RE61. Cannot Receive Activation Email**

Please refer to [FAQ1127](https://www.tp-link.com/us/support/faq/1127/)  
**Note:**  
Avoid suggesting cx to delete their TP-Link ID actively, as it could easily lead to cx complaints when they find all metadate no longer accessible anymore after deleting TP-Link ID.  
When cx delete their cloud account (e.g. Tether, Deco, Kasa, Tapo, tpCamera, www.tplinkcloud.com, Forum ID, etc.), they will permanently lose all metadata that is associated with the cloud resources, and they will no longer be able to revert them or restore any cloud-specific metadata even if they re-register the cloud again with the same cloud account credentials.  

## **RE63. Reset Password of TP-Link ID**

Please refer to [FAQ1442](https://www.tp-link.com/us/support/faq/1442/)  
**Note:**  
Avoid suggesting cx to delete their TP-Link ID actively, as it could easily lead to cx complaints when they find all metadate no longer accessible anymore after deleting TP-Link ID.  
When cx delete their cloud account (e.g. Tether, Deco, Kasa, Tapo, tpCamera, www.tplinkcloud.com, Forum ID, etc.), they will permanently lose all metadata that is associated with the cloud resources, and they will no longer be able to revert them or restore any cloud-specific metadata even if they re-register the cloud again with the same cloud account credentials.  

## **RE64. Change TP-Link ID**

Currently, only Deco App supports changing owner TP-Link ID [FAQ2957](https://www.tp-link.com/us/support/faq/2957/).  
For other products, to change the TP-Link ID bound to your device, please hard reset your device to factory defaults and then set it up again to bind it to your new TP-Link ID.  
**Note:**  
Avoid suggesting cx to delete their TP-Link ID actively, as it could easily lead to cx complaints when they find all metadate no longer accessible anymore after deleting TP-Link ID.  
When cx delete their cloud account (e.g. Tether, Deco, Kasa, Tapo, tpCamera, www.tplinkcloud.com, Forum ID, etc.), they will permanently lose all metadata that is associated with the cloud resources, and they will no longer be able to revert them or restore any cloud-specific metadata even if they re-register the cloud again with the same cloud account credentials.  

## **RE65. Delete TP-Link ID**

Please refer to: [FAQ2629](https://www.tp-link.com/us/support/faq/2629/)  
**Note:**  
Avoid suggesting cx to delete their TP-Link ID actively, as it could easily lead to cx complaints when they find all metadate no longer accessible anymore after deleting TP-Link ID.  
When cx delete their cloud account (e.g. Tether, Deco, Kasa, Tapo, tpCamera, www.tplinkcloud.com, Forum ID, etc.), they will permanently lose all metadata that is associated with the cloud resources, and they will no longer be able to revert them or restore any cloud-specific metadata even if they re-register the cloud again with the same cloud account credentials. 

## **RE91. No Power**

\* Is power Button Pressed In? 🠊  
\* Check if there is LED Button (If yes, press it)🠊  
\* Is the ORIG ADAPTER that comes with router being used? 🠊  
\* Is it plugged Surge Protector? (if so,plug to wall outlet) 🠊  
\* Plugged in different Power Outlet? 🠊  
\* Tried different Power Adapter if there's any 🠊  
\* Hard Reset 🠊  
\* Remove everything that is plugged to the device, then reboot/reset 🠊

Ask if there are any instances that will disqualify from RMA?  
\* Storm/Lightning 🠊  
\* Recent Power Outage? 🠊  
\* Any recent Failed FW update 🠊

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **RE92. Bad Ports/buttons**

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **RE93. Abnormal LEDs/No respond to reset**

\*record the status or changes of the LED on TP-Link device🠊  
Note:if all the lights are off, refer to "no power" issue to troubleshoot  
\*unplug all the Ethernet cable from TP-Link device🠊  
\*try to reboot🠊  
\*follow the user guide to reset the TP-Link device🠊  
Note: for deco abnormal LED issue, can try firmware recovery [FAQ2958](https://www.tp-link.com/us/support/faq/2958/) according to user’s willingness and ability

**\-Ask if there are any instances that will disqualify from RMA?**  
\* Storm 🠊  
\* Recent Power Outage? 🠊  
\* Any recent Failed FW update 🠊

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **RE94. WiFi Broken**

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **RE95. Random Auto Reboot/Reset**

\* Is the ORIG ADAPTER that comes with router being used? 🠊  
\* Is it plugged Surge Protector? (if so,plug to wall outlet) 🠊  
\* Plugged in different Power Outlet? 🠊  
\* Tried different Power Adapter if there's any 🠊  
\* Hard Reset 🠊  
\* Remove everything that is plugged to the device, then reboot/reset 🠊

Ask if there are any instances that will disqualify from RMA?  
\* Storm/Lightning 🠊  
\* Recent Power Outage? 🠊  
\* Any recent Failed FW update 🠊

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **RE96. Overheating**

If the device can still work normally when overheated?  
**1\. YES,** the device is still working fine  
**1.1** Provide explanation via email, using Ticket Marco【Overheated 1-Device works fine】  
**1.2** If CX insists that the device is very hot and is seriously worried about the device safety, can provide RMA accordingly.

**2\. NO**, router is having issue when overheated:  
**2.1** Collect the following info:  
\* What’s the issue ( low speed, unstable/no internet, or others) 🠊  
\* DOP and When issue starts 🠊  
\* Using original power adapter? 🠊  
\* Where the device was used (in the kitchen, bedroom, living room, etc.) 🠊

**2.2** Provide suggestions via email, using using Ticket Marco【Overheated 2-Device has issue】  
**2.3** If device still have issue when overheated and working properly when cooling down, can provide RMA under warranty.

\*\*\*RMA If Qualified \*\*\*Record information below:  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **RE97. Other Hardware Issue**

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does SN exist in System?\]

## **RE98. Safety issue**

**If the customer describe the issue as below:**  
**1\.** Device blow up/burnt/melted/fire, and traces like burnt marks can be seen on the device.  
**2\.** Device smells or smokes, although no signs of damage on the device.

Please handle the case as safety issue and follow the case by email. 

For PH team:  
Collect information according to [KMS002127](https://kms.tp-link.com/kms/multidoc/kms_multidoc_knowledge/kmsMultidocKnowledge.do?method=view&fdId=18fce419dec816784e7d84842b997c42) and Escalate to HQ Tier 3 team  
Ticket department: SMB service  
Ticket status: open  
Ticket owner: Unassigned  
Ticket note: product label and POP, image of the damage on device, how cx use the device (collect with the temple below)  
Escalate template: PH to HQ Tier 3 Escalation

**\*\*\*RMA If Qualified \*\*\*Record information below:**  
\[Approved by\]  
\[If Kit/Pack, How many defective?\]  
\[S/N of defective unit(s)\]  
\[Does S/N exist in System?\]

