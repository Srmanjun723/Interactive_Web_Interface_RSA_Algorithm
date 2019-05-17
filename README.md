# Interactive_Web_Interface_RSA_Algorithm

This Project is an Interactive Web Interface that shows the Working of RSA Algorithm making it simple for K-12 Students to understand the concept of secure communication in a more Simpler way.

This project involves HTML ,CSS ,Javascript and Bootstrap
There is no need to install any packages for this project

This project involves two demo steps namely RSA Demo and RSA Attack.

For RSA Demo part:
This part shows how the RSA algorithm works with 3 steps involved in it called as Key Generation ,Sender and Receiver steps.
Steps Involved:
1.There is a Zip Folder which needs to be extracted and then run the index.html file in the chrome browser which opens the web page on local host and then click on the courses tab, that gives instructions on the last slideshow as to how to play with the inputs for tab RSA Demo on the HTML Page. 

For RSA Attack part:
This part shows how an attack on the algorithm can reveal the original message to the third person or the middlemen.It shows the brute force attack on the private element 'd' due to which the attacker can guess the message from the list of messages.
Steps Involved:
1.After Extracting the Zip Folder, run the demo2.html file in the chrome browser.Sender part remains the same where you enter the prime numbers that generates the keys using which the message can be encrypted.
2.For middlemen, public key and encrypted message access is given using this and by changing the range of 'd' based on the 'n' value,the message can be guessed.

Where to change the range of d? Go to assests folder-> click on js folder->click on secureRSA_Modified.js file->then at line 92,range of d can be changed.//right now the value is set to 200.
