# interactive-dashboard-deb
Data used was from the study of different Bacteria by filterforge.com

Technologies Used
Frontend- Javscript,HTML,CSS(Plotly)
Backend- Python(Flask)
Database -MySQL

Step 1 - Plotly.js

We are tasked to use Plotly.js to build interactive charts for our dashboard.


1. Create a PIE chart that uses data from your samples route (/samples/<sample>) to display the top 10 samples.


Use sample_values as the values for the PIE chart
Use otu_ids as the labels for the pie chart
Use otu_labels as the hovertext for the chart




2. Create a Bubble Chart that uses data from your samples route (/samples/<sample>) to display each sample.


Use otu_ids for the x values
Use sample_values for the y values
Use sample_values for the marker size
Use otu_ids for the marker colors
Use otu_labels for the text values

Display the sample metadata from the route /metadata/<sample>


Display each key/value pair from the metadata JSON object somewhere on the page


3. Update all of the plots any time that a new sample is selected.
You are welcome to create any layout that you would like for your dashboard. An example dashboard page might look something like the following.

Step 2 - Heroku

Deploy this Flask app to Heroku.

Email : deborah.aina@outlook.com

Visit Appsite : https://interactive-dashboard-deb.herokuapp.com/



