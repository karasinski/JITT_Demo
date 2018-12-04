# JITT-Procedure-Viewer

A fine, open source, and brittle expandable procedure viewer which only works in Google Chrome.

### Notes
- A subject can be shown the interface and interact with it for as long as they like without fear.
- Pressing the `w` key moves the marker up, pressing the `s` key moves the marker down.
- Procedures can be expanded/collapsed by using the markers on the left, or the buttons `a` and `d`.

### Experiment Instructions
- Once the subject is acquainted with the system, the experimenter should type a subject number into the input box (this subject number may not contain the letters `wspdat`).
- The marker should be placed at the first step.
- The experimenter should press the `Start` button, which will hide the top buttons for the duration of the experiment.
- The subject should then use the `w` and `s` keys to move up and down through the procedures, which allows the experimenter to track the time at each step.
- When the subject is done, the experimenter should push the `p` button on the keyboard, which will hide all the steps.
- A file is asynchronously created in the base directory of the project with all of the data from the experiment. The file should be backed up.
