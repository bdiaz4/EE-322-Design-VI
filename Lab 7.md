# Lab 7 ThingSpeak and Google Sheets
## ThingSpeak
The directory iot/lesson7 was accessed
The following thingspeak account was created:
![image](https://github.com/user-attachments/assets/fd336e47-7514-4bc2-85da-0bfdd5cc53c3)\
A write API key was generated and added to the project using `python thingspeak_feed.py`
![image](https://github.com/user-attachments/assets/62d56a50-c0f3-4f9a-bf42-d74c4dbe245a)\
`python thingspeak_cpu_loop.py` connected to Thingspeak and began uploading cpu data

![image](https://github.com/user-attachments/assets/b74e7ac9-6049-4686-b4e3-862877283721)
## Googlesheets
![image](https://github.com/user-attachments/assets/6d0d82bb-f962-4c87-8c3d-644409e548aa)\
First, gspread oauth2client were installed.
A service acount for rpidata was created using google cloud services. The keys were then managed to make a JSON key and its file was downloaded. Cpu_spreadsheet.py was edited to add my JSON key after it was moved into its file directory. Finally a spreadsheet was made and shared with the service account.
![image](https://github.com/user-attachments/assets/e8863e79-8ba0-4797-a0a2-5fc161abd688)\
Running cpu_spreadsheet.py after these changes resulted in cpu data being collected and written to the googlesheet using the service account.
![image](https://github.com/user-attachments/assets/06427ec5-04dd-4fa6-ba22-a45fdb9d8d27)
