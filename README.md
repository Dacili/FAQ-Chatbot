# FAQ Medi Chatbot
FAQ Medi Chatbot is a chatbot that is used for frequently asked questions.   <br/> <br/>
   
You should use this type of chatbot when:
- your data is static
- when different users submit the same question, the same answer is returned.

Azure services needed:  
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/4cf74cb8-85a4-4b5c-958c-fafaf2d846e2)

Demo in Bot Framework Emulator (locally):   




https://github.com/Dacili/FAQ-Chatbot/assets/37112852/c06d32dd-0531-4330-afd2-74fe7296ff6a

### Create, test, and deploy a custom question answering project
1. Create **Language** service in Azure
2. Navigate to Language resource and open **Features**. In features check the checkbox, and create a new service for **Azure Cognitive Search service**:
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/877cf397-015d-427c-94e3-5083e51d6bbe)
3. Login with Azure creds in https://language.cognitive.azure.com/home
4. If you're using Language for the first time, follow the navigation like on image: 

 ![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/bc0e271b-7748-43cf-b070-ca217151a4c5)  
 if it's not your first time, you could easily click on Create new and then choose *Custom question answering*:     
 ![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/01ac83e0-0ca1-4aed-98fb-7c158be69457)  
5. Create a simple excel file, with a few questions and answers, like on the image:  
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/d959112a-94ab-461d-b5b2-af40da925e66)  
6. Click Add source -> Files, and then upload the excel file that you created.  
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/e27057d1-1656-49c4-8d40-3633d3a3b885)
7. After you're done, you should be able to see generated Knowledge base (KB), and click on it:  
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/17339c0c-9260-4e77-b104-97d624a8c767)
8. You will see on the left side different options such as editing and deploying KB. In the center you will see question-answer objects.  
You can add a new one, or edit an existing one. While editing you can add prompts (which are actually suggestions, shown like button to the user).  
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/8457913e-2d08-463d-8020-7700ea3051e7)
9. Once you're done with setting up a KB. Click on Deploy knowledge base, and deploy it.  
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/608411e7-21ad-4f3a-ba9a-ebf0b0de41fc)  
10. If you have not created a bot and app service already, click on Create a bot. It will actually navigate you to create both of these together, while also setting up the configuration for you, so you don't have to handle it manually. This is awesome if you don't want to see any code.  <br/> <br/>
But if you need to get the code, you will need to use FileZilla in order to get the code from the App service. The fields that you need for FileZilla you can found here:  
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/26ef0007-e519-42d6-a978-9dd0b2ba71a4)  
Once you're connected you will be able to download the code. Bear in mind that to make this work locally, you will need to update appsettings.json file with the configuration info needed. Some of these you will be able to find in App service -> Configuration.   
11. If you go to a newly created bot and go to Test in Web chat, you should be able to test it properly:
Demo in Azure (deployed):  



https://github.com/Dacili/FAQ-Chatbot/assets/37112852/a17ec54d-35a1-44ea-b07f-f83219dd6a83   

 

