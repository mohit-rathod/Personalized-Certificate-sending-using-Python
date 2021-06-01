# Personalized-Certificate-sending-using-Python
You can send personalized e-mails and attach documents with it

I have created this project to send different individuals their respective certificates in one go using python. 

IMPORTANT - For this you must have filename of the certificates in a specific order. eg- cert001, cert002, cert003, etc
            Using a particular email id, gmail allows only 500 mails per day to be sent

You basically have to create two lists
1. List_1 should contain the email addresses of the recipients
2. List_2 must have the filename of certificates/files (with proper extension) corresponding to list_1

eg: 

    List_1 = ['abc@gmail.com', 'def@gmail.com', 'ghi@gmail.com']
    
    List_2 = ['file1.jpg', 'file2.jpg', 'file3.jpg']

Using this two lists, file1.jpg will be sent to abc@gmail.com, file2.jpg to def@gmail.com etc

In this code I have used a excel file to create these two lists

Also, in the google account settings you have to allow access to less secure apps 
