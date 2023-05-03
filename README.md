Download Link: https://assignmentchef.com/product/solved-cpts479-assignment-9
<br>
For this homework you will write a standalone app, still called QuizApp, but allowing the user to generate questions and answers pertaining to nearby locations of interest. See screenshots below. Specifically,

<ol>

 <li>Add a Table View Controller embedded in a Navigation Controller to the app. The table view should have prompt “Quiz App” and title “Queries”. Add some queries to the table; at least the four shown in the screenshots, but you are welcome to add more.</li>

 <li>Add a Question View Controller to display the question, a button to get the answer, and a Map View. The prompt should be “Quiz App” and the title should be “Question”. When the user taps on a row in the table, the app should segue to the Question view and show the question “Where is the closest place for X?”, where X is the query selected from the table.</li>

 <li>The Map View should show the user’s current location. When the user taps the “Get Answer” button, the app should send the natural language query, and then the map should show the nearby places returned on the map. If no places are returned (e.g., for the “Stewed Gagh” query), then the app should show the error alert.</li>

 <li>Inside the Question View Controller, you will need to check for authorization to use location services and start updating location if authorized. If not available, or the user has disabled them, then the error alert should be displayed when you load the Question View and/or tap the “Get Answer” button. Be sure to add the “Privacy – Location When In Use Usage Description” to the Info property list.</li>

 <li>Be sure that auto layout constraints are set so that the view elements are appropriately displayed with no overlap regardless of device orientation.</li>

</ol>







StoryBoard:




Simulator:




Initial view                    After tapping any row             After tapping “Get for the first time.   Answer” and

zooming out a bit.




Error if no results                    User disables location                    Error for any query

returned.          services for app.          when location              services disabled.


