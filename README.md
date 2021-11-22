# VocabulARy - XR Hackathon 2021

To run VocabulARy just load the apk to your Quest 2 and start the application.

The application uses Passthrough SDK, so make sure Experimental Features are enabled.

Because real object detection is not supported, there is a setup-mode at the beginning, where bounding boxes for a table, a phone and a picture can be placed over the corresponding real world objects. This is done via controller, by grabbing the objects with the index-trigger. You can see how this works in the video here: ???????

After clicking "start" (index trigger) the learning-mode starts. You can ask for the german translations of the three words (table, phone, picture) by asking "what is phone in german" or "translate phone to german". Some other utterances will also work.
The german translation will appear, and also a visualization that helps you remember the word. For example the german word for picture is "Bild" which sounds like "build". Therefore you will see some bricks, building a wall.

