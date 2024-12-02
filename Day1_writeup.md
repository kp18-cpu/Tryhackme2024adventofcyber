# Day 1 #
## Getting a Mp3 converter tasks which usually has lot of vulnerabilities like advare and phishing campaigns for claiming exciting offers (fake world). 

1. Try to convert a youtube file. It downloads a zip file.
2. Extract a zip file, two different files name with same .mp3 extension. Song.mp3 is legit but somg.mp3 is odd.
3. Let's analyse with exiftool in kali for knowing the metadata of the file for understanding the backend.
4. It seems like somg.mp3 has powershell script having the script downloaded from github repository and executing it without any system or user interference.
5. Analyse the github repository for seeing the powershell script in this folder and it sends the sensitive information to the C2 server.


Answer all the questions based on the github repo and easy exercise. 
Finding real name of MM is easy to average if you know the story well. (Lol which is the hint here).
