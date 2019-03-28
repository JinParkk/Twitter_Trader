# Twitter_Trader
William &amp; Mary Cypher V Submission (Hackathon)
This Hackathon code was completed by Jin Park, Edward Lee, Harrison Lee, and Oliver Shen

Function of our code:

People with many followers have power to influence the price of the stock. Our code is designed
to target these users and analyze whether a they are endorsing or critizing a certain company. 
If a stock is not mentioned in their tweet, the post will be disregarded and will not be sent to the 
personal email, alerting the user.

These are the following instructions and important details to run the code TribeHacks.py:

- Make sure all python packages are downloaded
- Make sure all files in the zip folder are in the same folder
- Check if consumer/access keys and tokens are filled out

To run the project...

1) Modify the config.txt file.

     - Make sure to input personal email to recieve a notification from our company
     - Leave ONE space after "Personal_Email:" and type user email

     - Input a twitter account name WITHOUT @ symbol to track their tweets
     - Leave One space after "Twitter_Users_to_Track:" and type targeted twitter account

     * It is recommended to use "realHarryRhee" as Twitter user to track, since our code does not send any 
       email to the personal email, unless a stock is mentioned in their tweet. "realHarryRhee" is a test
       account with many opinion about financial stocks. 

2) Run TribeHacks.py from terminals

     - Once you run this program, you will recieve an email from our company, with the evaluation of the tweet.
     
     * If you want to input certain tweet into this code, input your personal twitter account in the config.txt file (without @ symbol)
       and post a tweet about a stock while TribeHacks.py is runnning in the background (from command prompt). You will recieve a email
       shortly after you tweet about a stock.  

     * It is also recommended that you post about a large, well-known company, such as Google, Netflix, Tesla, etc. 
