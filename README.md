# FAQ Medi Chatbot
FAQ Medi Chatbot is a chatbot that is used for frequently asked questions.   <br/> <br/>
   
You should use this type of chatbot when:
- your data is static
- when different users submit the same question, the same answer is returned.

Azure services needed:  
![image](https://github.com/Dacili/FAQ-Chatbot/assets/37112852/4cf74cb8-85a4-4b5c-958c-fafaf2d846e2)

Demo in Azure (deployed):  



https://github.com/Dacili/FAQ-Chatbot/assets/37112852/a17ec54d-35a1-44ea-b07f-f83219dd6a83   

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


 

