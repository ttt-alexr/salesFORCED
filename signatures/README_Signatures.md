# Use your HTML-formatted signature in Salesforce
![](SignatureExample.png)
1. Get your Profile Photo link
   1. Right-click your profile photo in your email or Zoho, click **Copy image link**
   2. If it's an absurdly long Mimecast link or similar, paste it into your browser address bar and press Enter
   3. It should start with "https://smart.trustedtechteam.com/photo"
2. Click the **View Profile** icon in Salesforce (top right)
3. Navigate to Settings > Email > My Email Settings
4. In the Email Signature box, paste the code found [here](ttt-sig-template.html)
5. Find and replace the text:
   1. Replace **PROFILE PHOTO URL** with your profile photo URL
   2. Replace **NAME** with your name
   3. Replace **JOB TITLE** with your job title
   4. Replace **CALENDLY URL** with your Calendly URL (or delete the line between `<a href...` and `</a>` if you don't want the link>)
6. Click **Save**
7. Open any case and create a new email to validate the appearance of the signature

> [!WARNING]
> The character limit is 1333 characters at this time!
> [!NOTE]
> You can modify the "Thanks," text or other properties of the template (Use your favorite AI tool if necessary), though the character limit is 1333 characters at this time so you may not have a lot of wiggle room. You may need to use a URL shortener on some of the links to buy more space, unless they expand the character limit at some point.