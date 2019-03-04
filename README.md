## Blockchain + AI Security System
Our project for Hack Cambridge 2018

# What is it about?
In these time people pay more and more attention to their security, from their phones to their personal information. However most security systems in professional work environments and universities still rely on the traditional 'swipe card' where there is always the possibility of misplacing it and hence leaving a time windows for someone to gain unauthorized access. This project is a proposal for a better more secure alternative. 

The idea was to build a 2 step verification system that would be very secure, scalable and reliable. This system comprises of the following components:
* Camera: The camera is used to take a picture of the person trying to gain access. The picture is then passed through a trained Neural Network (using the Azure Cognitive Services API) which performs Facial recognition and compares the result against a database of authorized individuals. 

* Blockchain transaction : After the Facial recognition step was passed the person trying to gain entry would be prompted to make a 'transaction' to confirm his identity. The way this would work is the person would access a mobile 'blockchain token' application and via NFC make a 'transaction with the door'. The system would then check that the 'transaction' was made from an authorized account (i.e. the account corresponding to the person trying to gain access.

Additionally for demo purposes a website was built through which the system administrator could see the person trying to gain access and manually grant or deny access to him/her. 

