triggers are first component which activates workflow types of triggers are : manual , on app event , schedule, on webhook and on form_submission  

scenerio 1 :  validate 2 numbers every 8:30 pm IST and send email if both are equal 


workflow diagram :

<img width="824" height="398" alt="image" src="https://github.com/user-attachments/assets/5d974cb9-0e52-4199-8139-d1f356370bd3" />

steps : 

1. initiated cron trigger ( trigger type is schedluled trigger )

2. fields value validated

3. value are sent to condition trigger, now tis values are compared using condition configured  if true sent to true mailbox else false mailbox

   <img width="664" height="175" alt="image" src="https://github.com/user-attachments/assets/5291f2fa-a1c4-4967-a1c0-8564bde09be9" />

   <img width="418" height="161" alt="image" src="https://github.com/user-attachments/assets/20a34f21-6640-4372-9a8f-86d7eefb595b" />

   since two values are same we recieved true mailbox message
   
   <img width="1052" height="212" alt="image" src="https://github.com/user-attachments/assets/fb721a5d-2884-4edd-89ed-5bae05285478" />


trigger type :  on app event 


<img width="803" height="420" alt="image" src="https://github.com/user-attachments/assets/f1c00ea3-af5e-456f-bef0-62df8b458cf5" />

