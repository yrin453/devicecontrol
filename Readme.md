# About the demo

This submission is in the form of a .maxpat file, which is an extension of a Max patch file. Max is a visual programming language that is used popularly amongst artists, educators, and researchers working with audio. Compared to other languages and packages such as JUCE on C++, Max provides a much larger bank of built-in functions designed specificly for music related programming.

This primary function of this Max patch is to provide an implementation of our recording assistant, which allows the triggering of playback controls on a MIDI controller without the use of a mouse. This implementation is created to test the effectiveness on this method of control within the process of music recording as well as identify problems and space for improvement in this implementation.

## Installation & setup instructions

* To be able to run this max patch, Max by Cycling '74 needs to be installed. A 30 day free trial is available at https://cycling74.com/downloads.
Alternatively, the program is installed on the computers in the University of Auckland School of Music if one has access to them. 

* When installed, the patch can be run by opening the 702705.maxpat file.

* When the file is opened, you will see the patch in its 'Patching Mode'. For the user studies, the patch needs to be in 'Presentation Mode'. This can be done by clicking the 'Presentation Mode' button on the bottom toolbar. (Alternatively, you can press Ctrl+Alt+E in Windows, or Option+Cmd+E for Mac users. This will bring you to 'Presentation Mode', where the user study will take part in.)

* Once you are in the 'Presentation Mode' make sure your patch is locked by clicking the lock/unlock button on the bottom left corner of the program (closed lock = locked, open lock = unlocked). This is very important since accidentally editing an unlocked patch could potentially stop it from working properly.

* The patch should already be setup to be able to work immediately. 
For some users, you may need to configure the MIDI input and Audio ouput by selecting the correct MIDI and audio devices in 'MIDI Setup...' and 'Audio Status...' under the 'Options' menu. Make sure the audio output is turned on, which is indicated by a blue speaker icon in the patch (grey indicates audio is off). 

##  Running the implementation

Once everything is setup, the program should respond and visualise the keys pressed on your MIDI keyboard. Adjust the volume slider next to the speaker icon to set the playback volume of the keyboard. 

To set the key combination that trigger each functionality (play/stop/pause), click the 'Locked' button on top of any of the functionality icons. The 'Locked' button will turn into a red 'Unlocked' button, which means that the key combination can be set. Simultaneously press all the keys of your desired combination and the entered key combination should show below the functionality icon. Once done, click the red 'Unlocked' button to lock the setup. Repeat this process for the other functionalities. 

Once finished setting up, the patch should act as a keyboard instrument, with the extra functionalities of record, play and stop, which can be triggered by key combinations on a MIDI controller without the need to interact with a mouse or computer keyboard.
