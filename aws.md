In this section we will be seting up aws. Please be aware that if you havent used aws before you will need a credit card.

Onced loged into the AWS Console and go into Lambda.

Choose your region as one of: US East (N. Virginia), EU (Ireland), US West (Oregon), Asia Pacific (Tokyo)

Then click Create Function. Select "Author From Scratch". Give your function a name. mine is called "YouTube".

Under Runtime, choose Python 2.7

Under Permissions, click "Choose or Create an Execution Role", then "Create a new role with basic lambda permissions".

When it has done the creation, on the new screen, under "Add Triggers", click "Alexa Skills Kit".

Down below select "Disable" on the Skill ID Verification.

