# Facebook Messenger bot using Node.js
Create a Facebook Messenger bot using Node.js. 
### Requirements:
   1. Install node and request.

         ```javascript
         npm install node
         ```
         ```javascript
         npm install request
         ```
   2. To run the server you will require [ngrok](https://ngrok.com/download).


### Steps to follow:
  1. Download the files and subsequent node modules. Open **index.js** on any source-code editor.
  2. Paste the access token:
  
  ![alt text](https://github.com/rushika99/Facebook-Messenger-Bot/blob/master/github.png)
  
  3. After you install ngrok, enter the following command:

      ```javascript
      ./ngrok http 5000
      ```
      
  ![alt text](https://github.com/rushika99/Facebook-Messenger-Bot/blob/master/fbdev.png)
  
  4. Run the file
      ```javascript
      node index.js
      ```
  5. Copy the URL generated above and append _/webhook_ and paste it in the 'Callback URL' of your Facebook App and set the            'Verify Token' as _hello_.
  
  ![alt text](https://github.com/rushika99/Facebook-Messenger-Bot/blob/master/callback.png)
  
  6. You're good to go!

  ![alt text](https://github.com/rushika99/Facebook-Messenger-Bot/blob/master/output.png)
      
