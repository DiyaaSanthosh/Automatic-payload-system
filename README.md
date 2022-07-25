Payload system - Store feature validation Automation for Wheel loaders


One of feature in a wheel loader payload system is the store functionality where operator can press the
store button on a display to create Load record on completing a Pass count. When material is loaded in
the bucket, calculated bucket weight is shown on the display and pass count is incremented on
completing the loading state. These parameters are viewed on the display. For validating the store
feature in Display, Application is available to replicate the Display screen content in Desktop computer.
For this project, Automation script is required to validate the store feature. Loader parameters like
Bucket Weight, Truck Payload Weight, Pass count values are updated on UI screen. On completing a
cycle and correspondingly incrementing the Pass count value, a “Store button” visible on the UI screen
needs to be clicked in automated manner.


Deliverables:
Deliverable 1: Application to simulate Feature Payload system in a desktop environment.
• Application for Environment setup - Implement application to simulate application running on
Desktop environment – Payload UI Screen [preferably within UI screen limitations of 700 * 1000
pixels.]- periodically change the values for the following parameters in UI screen.
Pass count value range: 1 to 20
Bucket Weight value range: 0 to 100 Tons
Truck Payload Weight: 0 to 400 Tons
First part of the application to update the incremental values of Bucket Weight value range from
0 to 50 Tons and when the Bucket Weight value is more than equal to 40 Ton, Pass count value
is incremented by 1.
On completing the Store button functionality (refer deliverable 2), reset the value of Bucket
Weight to 0.

Deliverable 2: Script/application to detect pass count cycle completion & click the “store” button in an
automated manner.
• Considering the application simulate in deliverable 1 screen, having predefined dimension,
running on Desktop computer, scope of the work is to identify and develop an application/ script
to monitor and display the real time values [Bucket Weight, Truck Payload Weight, Pass count].
On certain conditions matching [see Conditions logic below], mouse click event for store button
needs to be automated such that functionality of store button placed in a predefined pixel
position range on the UI screen is executed.
When pass count value is incremented [indicating the completion of a pass of a loader] along with
increment of 40 Tons in bucket weight, conditions are satisfied to store the record. Option to
press Manual store button will be available in UI. However, triggering store button functionality
needs to be automated. Store button clicked event to be represented in any visible form like
output log or change in any UI format. On completing the Store button functionality, reset the
value of Bucket Weight to 0.
