# Lab 10 — Blockchain
## Hash Introduction
The script `hash_value.py` was ran twice to see which variable types change value.
![image](https://github.com/user-attachments/assets/b490edef-5232-4a86-bbcb-1a27ee359537)
It was found that integers and decimals do not but variable types such as objects, tuples, and strings do randomly.
## Blockchain Introduction
Next, `snakecoin.py` outputed 20 blocks each with its own randomly assigned hash value. This was done by creating the first block based on the current date and time and recursively creating more blocks, getting the time again, and adding a random value to the hash via a string.
![image](https://github.com/user-attachments/assets/62ae2163-6a22-43bf-9c1b-561ae1e82225)
## Snakecoin Full Server
The full server was launched using the following python script.
![image](https://github.com/user-attachments/assets/a8c2c969-0ec2-4c69-8505-22743baeb37c)\
Accessing it brought it to this webpage.
![image](https://github.com/user-attachments/assets/166a384d-956e-4d52-b2e1-5ebf453ad4e1)
reading from webapage through terminal
![image](https://github.com/user-attachments/assets/b6539076-d58f-4dc8-b11a-607d7389ef55)
Page updated over time
![image](https://github.com/user-attachments/assets/3a7af86c-dfef-40c4-9c12-e22e65686b4e)
## Python Blockchain App
First the github for the app was cloned.
![image](https://github.com/user-attachments/assets/053d9f72-7d2f-4137-a368-7f49b72c8607)
From in the python_blockchain_app folder `node_server.py` was ran
![image](https://github.com/user-attachments/assets/e3d2f7de-fc8f-4052-ab07-b30a88d835a0)
Next `run_app.py` was executed in a different terminal and with both running resulted in this webpage
![image](https://github.com/user-attachments/assets/127bf89a-283c-4803-96f0-c5047e532a17)\
Messages can be written in the box and are visible by pressing resync
Pressing request to mine opens this page
![image](https://github.com/user-attachments/assets/7c7784d6-de01-4a84-8b2a-cefee9d720bc)
If no transaction is available on next request the page prompts the user
![image](https://github.com/user-attachments/assets/480911bd-b051-4581-965d-3c0596eb6a7b)
Creating a 2nd message results in another successful mine request
![image](https://github.com/user-attachments/assets/abeb1c50-7ce3-422a-a48b-c3f30cebe9d0)

