# How to Create Geo-Tagged QR Codes

1. Create your Google Doc

2. Click on < Script Editor > from the "..." dropdown
<img width="203" alt="Screenshot 2022-07-31 at 12 48 55 PM" src="https://user-images.githubusercontent.com/19563337/182014728-f198ec4e-bc38-47cb-9cd7-f8a297726d06.png">

3. Copy the "Code.gs" file(https://github.com/SVirat/Geolocation-Script-Google-Docs/blob/main/Code.gs) and the "Index.html" file (https://github.com/SVirat/Geolocation-Script-Google-Docs/blob/main/Index.html) into the two files on the now opened AppsScripts page.
<img width="1440" alt="Screenshot 2022-07-31 at 12 51 16 PM" src="https://user-images.githubusercontent.com/19563337/182014791-7e621e03-9571-46f3-93ef-62f08df1b42b.png">

4. Now, click on "Deploy" --> "New Deployment"
<img width="219" alt="Screenshot 2022-07-31 at 12 51 40 PM" src="https://user-images.githubusercontent.com/19563337/182014805-2b4faa1f-d85a-4fe8-a404-328eda024657.png">

5. Click on "Web app" in the pop-up
<img width="766" alt="Screenshot 2022-07-31 at 12 54 57 PM" src="https://user-images.githubusercontent.com/19563337/182014912-fea26283-a4d6-494f-9cab-93410cccd2c7.png"> 

6. In the pop-up, give a proper discription and make sure you click on "Anyone" under "Who has access", then click "Deploy"
<img width="766" alt="Screenshot 2022-07-31 at 12 52 16 PM" src="https://user-images.githubusercontent.com/19563337/182014821-baf485dd-316c-40d8-b37c-c643ac91b060.png"> 

7. Go through the prompts to request access. Just keep clicking allow. If a prompt shows up saying it's not safe, be assured that it is safe (Google just needs read/write access to your Form), and keep going until you see a "New Deployment" page.
<img width="766" alt="Screenshot 2022-07-31 at 12 57 14 PM" src="https://user-images.githubusercontent.com/19563337/182014990-8b1c3d9c-0160-4015-8a42-7a4c6e4da627.png">

8. Copy the "Webapp URL" here

9. Go back to the actual Google Form, go under "Presentation", and then paste this link under the "Confirmation Message" field (under "After Submission"). 
<img width="766" alt="Screenshot 2022-07-31 at 12 58 07 PM" src="https://user-images.githubusercontent.com/19563337/182015016-4b06055f-7bf7-4c9c-9c55-0fd7faf3f304.png">

10. The form itself is ready. Copy the link to it (under "Send").
<img width="593" alt="Screenshot 2022-07-31 at 12 59 30 PM" src="https://user-images.githubusercontent.com/19563337/182015065-636030ca-4261-4213-8bd0-d678c554fb63.png">

11. Go to https://www.the-qrcode-generator.com/ and paste the link to the form here. This will generate a QR code

12. This is the final QR code. Make sure users actually click the link after submission of the form, because this is how Google captures your geolocation. 
