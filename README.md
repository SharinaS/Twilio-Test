# Twilio-Test
A test on the use of Twilio to send text messages to a cell phone. 

## Built By: 
Sharina Stubbs

## To Use:
1. Git Clone this repo
2. Open app in IDE, such as IntelliJ
3. Consider refreshing Gradle.
4. Make a twilio account at Twilio.com, and go to your console
5. In class SmsSender.java, update the following with your Twilio Credentials:
* line 11 - ACCOUNT_SID
* line 13 - AUTH_TOKEN
* phone you are sending a text message to (your cell phone)
* phone number you are sending a message from, which is supplied by Twilio during signup.
6. Run main function in IntelliJ, or run from the terminal:
* Compile first - `javac -cp twilio-7.17.6-jar-with-dependencies.jar SmsSender.java`
* Run from Mac OS terminal: `java -cp .:twilio-7.17.6-jar-with-dependencies.jar SmsSender`
* Run on PC command-line: `java -cp .;twilio-7.17.6-jar-with-dependencies.jar SmsSender`
