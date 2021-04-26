## Module 01: User and group management


### Talking points

***Labs talking points***

Microsoft Online Services Sign-in Assistant


Recovery of deleted groups in powershell

```
Connect-AzureAD
Get-AzureADMSDeletedGroup
Restore-AzureADMSDeletedDirectoryObject -Id {objectId}
```




### Zero Trust

Zero-Trust overview (includes eBook) aka.ms/zero-trust
Zero-Trust device mgmt. overview aka.ms/zero-trust-device
How-To documentation #MSIntune aka.ms/device-security-docs


Supporting videos for instructor or student use:

Azure AD conditional access enabling Zero Trust networks
https://youtu.be/XruceejcCKQ?list=PLXtHYVsvn_b8dbRbnL19GUPcBH1UQ7c4x


 Let’s start with a few hard realities: 
Perimeter based networks only trust users INSIDE a network
Single point of attack can threaten the entire network.
Security and IT often use separate and disjointed tools. 

We need a new security model.

ENTER ZERO TRUST


### Plan identity

The Identity video below is highly recommended to explain the primary concepts of this lesson.Supporting videos for instructor or student use:

Identity models and authentication for Microsoft 365
https://www.microsoft.com/en-us/videoplayer/embed/RE2Pjwu


Azure Active Directory: Choosing the right authentication for your organization
https://youtu.be/oPeKXefxEgg


### User accounts and roles

Azure Active Directory explained
https://youtu.be/6MSrkUDOqsE

Identity models and authentication for Microsoft 365
https://www.microsoft.com/en-us/videoplayer/embed/RE2Pjwu

Add users in Office 365
https://youtu.be/zDs3VltTJps

Introducing Groups in Office 365
https://youtu.be/t3OLvYXepvE


### Password Management

https://aka.ms/gopasswordless

Demonstration: Implement Multi-factor authentication
https://youtu.be/SN-J7L1na34

How to set up self-service password reset for Microsoft 365
https://www.youtube.com/watch?v=Jppfvl95DvE


This recorded demo is provided to give learners a sense of the experience when a user sends and receives a protected message.

Follow the annotations and blinking circle for where to click.

Time required: 5 minutes
  
Guided demo link: https://aka.ms/AA6xlpx

Demonstration: Password-less Auth using Azure AD
https://youtu.be/YFvAbr-Qsm4?list=PLXtHYVsvn_b8dbRbnL19GUPcBH1UQ7c4x

Windows Hello Explained
https://youtu.be/ASe5HiCr71I

Demonstration: Windows Hello
https://youtu.be/NHPDj_eVCvs

Describing Smart Lockout
https://youtu.be/aeuFaG8ZJnY
