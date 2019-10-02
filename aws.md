In this section we will be seting up aws. Please be aware that if you havent used aws before you will need a credit card.

Onced loged into the AWS Console and go into Lambda.

Choose your region as one of: US East (N. Virginia), EU (Ireland), US West (Oregon), Asia Pacific (Tokyo)

Then click Create Function. Select "Author From Scratch". Give your function a name. mine is called "YouTube".

Under Runtime, choose Python 2.7

Under Permissions, click "Choose or Create an Execution Role", then "Create a new role with basic lambda permissions".

When it has done the creation, on the new screen, under "Add Triggers", click "Alexa Skills Kit".

Down below select "Disable" on the Skill ID Verification.

Now you've got your basic Lambda Function setup. 👍

dowload  the code using this link https://github.com/andrewstech/youtube-for-alexa/blob/master/lamba2.zip

After you have it, let's upload that into your Lambda Function.

You need to add 2 environment variables. The first should be called "DEVELOPER_KEY" and value should be your Google YouTube API Key.

The second environment variable is"youtube_dl" and the value should be set to "true"

Also, make sure you update your Memory utilization to 512MB with a timeout of 10 seconds.

Hit SAVE to update your Function

Now up at the Top of the screen you will notice your ARN

Copy your ARN to your notepad as you will need this next.

To continue click the link bellow

https://github.com/andrewstech/youtube-for-alexa/blob/master/alexa-setup.md

