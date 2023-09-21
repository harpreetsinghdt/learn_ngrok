# Learn ngrok

1. Unzip to install
On Linux or Mac OS X you can unzip ngrok from a terminal with the following command. On Windows, just double click ngrok.zip to extract it.

https://ngrok.com/download

=> unzip /path/to/ngrok.zip


2. Connect your account

Running this command will add your authtoken to the default ngrok.yml configuration file. This will grant you access to more features and longer session times. Running tunnels will be listed on the endpoints page of the dashboard.

=> ngrok config add-authtoken 2VipY0pD7GCBMi6MtSdX5SoPYnA_6Fwqfaca8Y4eqYSkQ1LZk


3. Fire it up

Read the documentation on how to use ngrok. Try it out by running it from the command line:
=> ngrok help

To start a HTTP tunnel forwarding to your local port 80, run this next:
=> ngrok http 80



Error Solutions:
how to solve the error" Your account is limited to 1 simultaneous ngrok agent session"? (https://stackoverflow.com/questions/76423423/how-to-solve-the-error-your-account-is-limited-to-1-simultaneous-ngrok-agent-se)
Use the following command:

=> taskkill /f /im ngrok.exe
