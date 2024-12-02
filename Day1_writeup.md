# Day 1 #
## Getting a Mp3 converter tasks which usually has lot of vulnerabilities like advare and phishing campaigns for claiming exciting offers (fake world). 

Learn about OPSSEC in this page, leaving behind the traces which we try to catch up using the forensics.

1. Try to convert a youtube file. It downloads a zip file.
2. Extract a zip file, two different files name with same .mp3 extension. Song.mp3 is legit but somg.mp3 is odd.
3. Let's analyse with exiftool in kali for knowing the metadata of the file for understanding the backend.
   <img width="603" alt="image" src="https://github.com/user-attachments/assets/b6dd7b4e-a223-4d46-95fc-f7e25deee83b">
   <img width="631" alt="image" src="https://github.com/user-attachments/assets/ccd212bd-7b7e-4e8c-a6c4-8c72c52a3129">
5. It seems like somg.mp3 has powershell script having the script downloaded from github repository and executing it without any system or user interference.
6. Analyse the github repository for seeing the powershell script in this folder and it sends the sensitive information to the C2 server.

Answer all the questions based on the github repo and easy exercise. 
Finding real name of MM is easy to average if you know the story well. (Lol which is the hint here).
<img width="1046" alt="image" src="https://github.com/user-attachments/assets/146a818a-b7e0-41e8-9830-32fd4b846a0b">

