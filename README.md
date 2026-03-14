# 1403-Vision-Scouting-App
2026 scouting app for 1403. 

Currently deployed at: https://1403-vision-scouting-app.vercel.app/

Features:
* QR Code Generation: Encodes all scouting data as a tab-separated string so that scanning with a Bluetooth barcode scanner automatically distributes each value into its own column in Google Sheets, allowing for offline and quick data storage optimal for venues without internet. 
* Data/Form Validation: The Generate QR Code button is disabled until all required fields (Name, Match Number, Team Number) are filled in
* Collapsible Form: If "Showed Up?" is toggled off, the rest of the form collapses to reduce clutter for no-show entries
* Match Timer: Built-in stopwatch with start/pause and reset controls; can automatically timestamp robot events during the match (such as 
* Dependent Fields: Toggling "Died?" reveals timestamp stamp buttons for "Approx. Time Robot Died" and "Functioning Again"; both fields are always included in the QR output to prevent spreadsheet column offset errors
* Stepper Inputs: All integer fields use +/− stepper buttons for incremental, fast, and, accurate input with a minimum value of 0 to prevent offset errors if using spreadsheets
* Info Help: Every field has an ⓘ button that opens a description explaining what the field means in case scouters need clarification/refreshing
* Reset: Resets all match-specific fields after submission while preserving the scouter's name across matches
* Themes: Sleek Dark, Light, and Cute modes that can be easily toggled in the header
* Accessible Design: High contrast UI with large, finger-friendly buttons suitable for use on both mobile devices and computers
* Static Tapping: The "tap to zoom in" feature is disabled for mobile devices so that scouters can quickly spam increment fuel counts.
* Pre-Submission Verification: A table of all the data the scouter has input is available for view at the end so that scouters can verify that they have submitted all the correct information.
