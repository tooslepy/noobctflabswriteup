# Noob CTF Labs Writeup 
 ---
 Lets get started
 ### CTF1
 So the first CTF is just looking at the source code of the site (hinted by the pun on the page). 
 ![CTF 1 Screenshot](CTF1.png)
 infosec_flagis_welcome is the flag
 
  ### CTF2
  The second CTF has a broken image file that we have to check. Save the file and open the file in a hex editor. 
   ![CTF 2.1 Screenshot](CTF2.1.png)
   Looks like we have a base64 string. So go to www.base64decode.net or decode it in terminal, whatever suits you best, and we have the second flag.
   ![CTF 2.2 Screenshot](CTF2.2.png)
   The base64 string decodes to be infosec_flagis_wearejuststarting
                                                                          
