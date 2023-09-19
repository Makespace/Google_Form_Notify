The Google app script runs on this Google sheet: Trouble ticket (Responses), which holds the responses from the Trouble tickets form submissions.  The script editor can be found under the Extension/Apps Script menu.  The script extracts the name of the equipment then sends an email based on that value to the appropriate Owners teams.  e.g. CNC router to the CNC team, Markforge to the 3D printer team... 

Set up the Script:

The script should be placed in the Sheet's Apps Script which can be found under the Extension/Apps Script menu.  Copy the code to replace the default place holder script,

Set up the Trigger:

    Click on the clock icon in the toolbar of the Apps Script editor.
    Click on "+ Add Trigger" in the bottom right corner.
    Select onFormSubmit from the function dropdown.
    Choose From form > On form submit for the event source.
    Save the trigger.
