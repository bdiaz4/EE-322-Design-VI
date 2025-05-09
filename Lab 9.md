# Lab 9 — YANG
## Installs
First, both pyang and plantuml were installed
![image](https://github.com/user-attachments/assets/f4f94632-ac2d-4340-8cd2-b9c31c311c76)\
## File creation
A yin file associated with intrusiondetection.yang was created in lesson 9 with the following command.
`pyang -f yin -o intrusiondetection.yin intrusiondetection.yang`
a uml file was created using the command.
`pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef`
Finally the uml file was ran using plantuml
`python3 -m plantuml intrusiondetection.uml`
## Results
A png file was then outputed in the lesson9 directory
![intrusiondetection](https://github.com/user-attachments/assets/7050fb94-cfc9-48ed-8508-53e26c79feb4)
