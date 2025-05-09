# Lab 8 — Data Analysis
## Setup
numpy scipy scikit-learn matplotlib pandas keras were installed.
Tensorflow did not work with python 3.13 so python was reverted to 3.11.
In order to use plt_final.py, the csv file for lab 7 was downloaded and saved to lesson 8. Then plt_final.py was updated to 
data = read_csv('cpudata - Sheet1.csv')
x = data['CPU Usage %']
y = data[' Temperature C (or Memory Available GB for cpudata)']
to match the headers and name of the file exactly.
## Graphs
The following graphs were outputed running `plt_final.py`
![image](https://github.com/user-attachments/assets/5c114fa8-936d-4966-9890-fdb17ad1b904)
![image](https://github.com/user-attachments/assets/2adf4d23-ade2-4c73-843b-edddbab09078)
![image](https://github.com/user-attachments/assets/19db2ac1-ebf5-41b9-b374-18f577a8545b)
![image](https://github.com/user-attachments/assets/ff2772e4-13df-4080-8762-44e154fc4c05)
![image](https://github.com/user-attachments/assets/1cb0d40f-1a8d-4158-a465-9737e8e5126b)
![image](https://github.com/user-attachments/assets/cfcaac33-e9bb-4780-be2a-762dbba37528)
For `plt_cv2.py`
At first I got the following error
![image](https://github.com/user-attachments/assets/aa713445-0e49-4bb1-861b-9f0abc5f31ec)\
Therefore, the program was updated to have cv=4 instead of 10. To have more accurate results a longer data sample should be used in the future.
![image](https://github.com/user-attachments/assets/0122dfa0-1aba-4ee9-ab59-c3a048260a9e)
