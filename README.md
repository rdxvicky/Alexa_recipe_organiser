# Alexa_recipe_organiser

<b>1</b>. create new folder somewhere and open it in your favorite JavaScript IDE. I am going to be using Visual Studio Code, which is free to download.
<br />
<b>2</b>. Add an index.js file to the folder.
<br />
<b>3</b>.Open a terminal and cd to the folder you created. Type npm init in your terminal. Answer the questions that NPM asks you with whatever you like.
<br />
<b>4</b>.Type npm i alexa-sdk aws-sdk es6-promisify --save in your terminal. This will add the Alexa SDK and AWS SDK to your project. The AWS SDK is only necessary because we are going to be using DynamoDB. I’ve also added the es6-promisify library because the AWS SDK’s DynamoDB client uses a callback-style API and I wanted my code to be a little cleaner.
<br />
<b>5</b>.Add the following code to index.js:
