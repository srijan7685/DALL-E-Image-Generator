# DALL-E-Image-Generator
This project uses openai dall-e labs session key to get high resolution AI generated image.
# Setup
* To get the your unique session key you need to go to https://labs.openai.com/.
* Open the Network Tab in Developer Tools in your browser.
* Send an image request in the input box.
* In the network tab you'll find a POST request to https://labs.openai.com/api/labs/tasks.
* In the POST request headers you'll find your session key in the "Authorization" header, it'll look something like "sess-xxxxxxxxxxxxxxxxxxxxxxxxxxxx".
