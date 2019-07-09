Application Developer
=========================================

Hey there! Here will be guiding you on how to join as an Application Developer in Huron.

Account Setup
----------------

- Open up the URL https://fabric.huron-lab.com/login in your browser
- Fill in your Details and Click on Continue
- You will now Choose "I would like to use compute resources" and Click Sign Up
- You should be receiving a mail with an Email Verification link.
- Open the received email and verify your account by clicking on the Verify Email Address button.
- On verifying, we would be setting up your account.
- Once that is completed, Click on Login and login to the application with your credentials
- Hurray! You are done creating your Developer account.

Deploying your first applications
--------------------------------------

- In the Side Navigation Menu, Click Applications.
- Click on Add new application button.
- Enter your app details.
- Under Docker Configurations, enter your docker images in the format 'Repository/Image:Tag'.
- If your docker image is under a private docker-hub repo, Please select 'Private' and enter your docker credentials.
- If you have any environment variables, you can add it in Advanced Configurations.
- Once you have filled in all the details, Click on Save Application. 
- Now you need to pay a caution deposit which will be refunded, to run your application.
- Once Your balance is loaded Unlock button will be enabled. Please click Unlock.
- Cool! You are almost done. Your Payment will take some time to mine. 
- Once that is mined you will see the status of your application as 'Pending'/'Running'/'Unassigned'.
- Within sometime your application should start Running.
- You can check the logs of the application by clicking on the Logs button at the top right.
- In case if you want to delete your application. Click on Stop button. Once the application is stopped, you will have a button to delete your application.
- When your application is deleted, your initial deposit will be refunded to your wallet.


Deploying a public application
--------------------------------------

- Huron will provide public-facing URL for TCP and HTTP(s) ports
- To configure ports, start creating an application as mentioned in the above section.
- Under Advanced Configurations, you can add ports to expose your application to public face.
- Proceed with creating the application and initiating the payment.
- Once your application has started running, under Endpoints you can see the exposed DNS URL.


Configuring custom domain
--------------------------------------
- Purchase a domain in any of the domain name providers online like Godaddy.
- After configuring the ports and your application starts running, under Endpoints, you can see the exposed DNS URL.
- You can see the Map Domain button aside of the Endpoint URL
- Clicking Map Domain will show a popup with instructions.
- First map the CNAME provided in the popup to your domain address on your DNS provider.
- After Mapping, now enter the registered domain in the given input field provided in the second step.
- Once done, click on Map Domain.
- We will test your configurations and map your application to your domain.


Application Status
-------------------------
- 'CREATED'- Application details are added, Payment to be done.
- 'VERIFICATION_FAILED' - Your application configuration might be incorrect.
- 'PAYMENT_IN_PROGRESS' - Your transaction is yet to be mined.
- 'PAYMENT_FAILED' - Payment Failure may happen if insufficient balance or any network error. You can Retry it.
- 'PAYMENT_SUCCESS' - Payment is success, you can manually start the job.
- 'PENDING' - Your application is waiting for deployment
- 'UNASSIGNED' - Your job is waiting for a machine to be allocated.
- 'RUNNING' - Your job is Running.
- 'OFFLINE' - Your job has stopped running.
- 'REFUND_IN_PROGRESS' - Refund is in progress
- 'REFUND_FAILED' - Refund has failed. You can retry to initiate the refund.

