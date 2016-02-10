# sharex-upload-script
I wrote this after discovering a bit more of how image uploading works with ShareX from Aerouk's script.

##Installation

  1. Upload the files provided in the repo onto your website.
  2. Change the $uploadhost, and $redirect parts to fit your website.
  3. Change the $key part to a password of your choosing. Do not share this with anyone you do not trust or you could risk people using your site for illegal means, which could land you in trouble, whether you uploaded it or not.
  4. In ShareX, click Destinations > Destinations Settings and scroll down to Custom file uploader. Change the settings there to match the following image: http://i.imgur.com/6KaI8vn.png
  5. Press update and close the window and go back to the ShareX main window.
  6. Go to After Destinations > Image Uploading and select Custom image uploader. You can also do the same for File uploading. The script works for .webm and .mp4, sound is supported.

#Alternative
If you'd like to use this script on a website that already has a page, just put the script in upload.php and change the Request URL on ShareX to http://yourwebsite.com/upload.php.

#If you use 000webhost

If you plan on using 000webhost to host your domain, you'll have to go here to disable google analytics, otherwise the analytics code will show up in your image url after uploading.

https://members.000webhost.com/analytics.php
