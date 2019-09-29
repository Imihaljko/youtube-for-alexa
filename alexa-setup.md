start by heading to https://developer.amazon.com/alexa/console/ask

sign in with your amazon account.

click on Create skill

enter a name for your skill & make sure that Custom and Provision your own, are selected

On the next screen select start from scratch and click the choose button.

scrole down and click on the Interfaces button.

enable the audio Interface, video Interface and the display Interface.

click the save Interfaces button.

look on the left for a button called JSON Editor, click it.

remove all text from the box.

navigate to https://raw.githubusercontent.com/Livegamingshorts/youtube-for-alexa/master/InteractionModel_en.json

copy all the text from here and paste it in the box.

click on save model then click build model.

now look for the endpoint page. (located on the left)

select AWS Lambda ARN and in the Default Region box enter your ARN 

leave the other boxes blank. click on save model then build model.

now navigate to the test page(at the top)

next to where it says Test is disabled for this skill. click on the dropdown menu and choose development.

You now have a working skill just say alexa launch youtube.

If you like this project consider donating https://paypal.me/andrewstechshow

if you have any issues please post them in the issues.
