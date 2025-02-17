This was a standard delivery delay scam solicting name, address, and phone number from victims for follow scamming. A txt message was recieved from:
  r29582666@gmail.com

 The message contained instructions to reply "Y" then exit txt message and open again to click the link or to copy it into safari browser. Mention of safari makes it appear iphone targeted, but may just be hoping an iPhone user is reciving it and then believes it's legit because USPS knows what type of phone they have.

  link was to:
  https://usps[.]com[.]packagesteis[.]com

  A curl to the address didn't return anything. After setting User-Agent to an iPhone user agent string I was able to get a ClientTag and PHPSessionID cookie. Using these I used burp repeater to pull the code from the pages and hit the redirects.

  nsloop for the domain reutrns IP:
  38.146.27.72

  whois on the IP returns:
  Cogentco
  UltaHost
  100 Delawanna
  Clifton
  NJ, 07014

  ![image](https://github.com/user-attachments/assets/a0e648f9-ca09-433b-8ee1-a97988bc06bd)

  ![image](https://github.com/user-attachments/assets/6d2b771f-6211-4328-bc27-ca9af984893d)

  ![image](https://github.com/user-attachments/assets/394b65ca-0cc4-4326-aaee-b674f6115e8e)


