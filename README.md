# LimeSurvey-5.4.15-Stored-XSS-in-surveytexts

**LimeSurvey-5.4.15 has Stored XSS in /index.php/surveyAdministration/rendersidemenulink?subaction=surveytexts**

**The Complete attack steps are as follows:**

1. Create a survey.
2. Choose this survey and find the Survey text elements.
![image](https://user-images.githubusercontent.com/71068573/209175988-3ae2f606-230e-4d03-8425-384ea6c7284f.png)

3. fill your XSS payload in the Description and Welcome-message box.
![image](https://user-images.githubusercontent.com/71068573/209176247-7856bb19-2d1d-4a4b-9115-d8ed973344ec.png)

4. Run this survey in website, then the sotred XSS payload will be triggered.
![image](https://user-images.githubusercontent.com/71068573/209176592-3c58862a-f8a6-43d3-a853-2dd4b8051b95.png)

![image](https://user-images.githubusercontent.com/71068573/209176630-d99567fd-4080-49ce-ae43-0feab36c1fe4.png)

