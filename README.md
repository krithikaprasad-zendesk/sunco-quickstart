# sunco-quickstart
First Sunco API Quickstart Example

Get started
For a detailed guide, see the Sunshine Conversations API Quickstart:

Node.js
Clone the repository
Go to the nodejs subdirectory
Update index.js to include your secret key and key ID from your Sunshine Conversations settings
Install dependencies (npm install)
Run the server (node index)
Use ngrok to create a secure tunnel to port 8000(ngrok http 8000 after ngrok is installed on your PC)
Create a Facebook page and connect it to Sunshine Conversations
Create a Webhook from your dashboard and point it at the full url for the /messages endpoint (e.g. https://MY-NGROK-DOMAIN.ngrok.io/messages )
Send messages to your Facebook page and watch the auto-replies roll in
