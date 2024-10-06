Retention Data Generator
A simple, user-friendly web tool that helps you visualize and analyze attendee retention for webinars, online courses, or any timed sessions. By uploading your attendance data, you can generate insightful retention charts and tables without any technical setup.

Features
Easy Data Upload: Simply upload a CSV file with your attendance data.
Instant Processing: The tool processes your data directly in your browser.
Interactive Retention Chart: Visualize how attendee retention changes over time.
Summary Table: See retention percentages at key time intervals.
Detailed Data Table: Access minute-by-minute retention data.
Download Options:
Retention Data CSV: Download the processed data for further analysis.
Chart Image: Save the retention chart as an image file.
How It Works
1. Prepare Your Data
Create a CSV (Comma-Separated Values) file with two columns:

Person: A unique identifier for each attendee (e.g., name, email, or ID number).
Time Duration: The total time each person spent in the session, measured in minutes.
Example:

csv
Copy code
Person,Time Duration
Attendee 1,60
Attendee 2,45
Attendee 3,30
Attendee 4,15
2. Upload Your Data
Open the web page (index.html) in your preferred web browser.
Click on the "Choose File" button to select your CSV file.
Ensure that the file has the correct format and includes the required columns.
3. Process and Visualize
Click on the "Process CSV File" button.
The tool will process your data and generate:
An interactive Retention Curve Chart displaying retention percentage over time.
A Retention Summary Table showing retention at specific intervals (15, 30, 45, 60 minutes, and at the session's end).
A detailed Retention Data Table with minute-by-minute data.
4. Download Results
Retention Data CSV: Click on "Download Retention Data CSV" to save the processed data to your computer.
Chart Image: Click on "Download Chart Image" to save the retention chart as a PNG image.
Understanding the Outputs
Retention Curve Chart
Visual Representation: The chart shows how the retention percentage of attendees decreases over time.
Axes:
X-Axis: Time spent in the session (minutes).
Y-Axis: Retention percentage (%).
Interactive Features: Hover over data points to see exact retention percentages.
Retention Summary Table
Key Intervals: Displays retention percentages at 15, 30, 45, 60 minutes, and at the end of the session.
Quick Insights: Helps identify significant drop-off points during the session.
Retention Data Table
Detailed View: Provides the number of attendees remaining and retention percentage for each minute.
Data Columns:
Time Spent (Minutes): Each minute of the session.
Number of Attendees Remaining: How many attendees stayed for at least that many minutes.
Retention (%): The percentage of the original attendees remaining at each minute.
Benefits
No Technical Skills Required: User-friendly interface suitable for all experience levels.
Immediate Results: Get insights without waiting or using complex software.
Data Privacy: All processing is done locally in your browser; your data isn't uploaded or stored elsewhere.
Cross-Platform Compatibility: Works on all modern web browsers without the need for installation.
Usage Scenarios
Webinars and Online Events: Understand at which points attendees drop off to improve future sessions.
Educational Courses: Track student engagement over the duration of a lesson or lecture.
Presentations and Workshops: Optimize content by identifying when audience attention declines.
Getting Started
Download or Clone the Repository:

Visit the GitHub repository and download the code as a ZIP file or clone it using Git.
Open the Tool:

Locate the index.html file in the downloaded folder.
Double-click to open it in your default web browser.
Follow the On-Screen Instructions:

Upload your CSV file and process the data as described above.
Customization
Adjust Time Intervals:

Modify the time intervals in the summary table to suit your needs by editing the code (for advanced users).
Change Chart Appearance:

Customize colors, fonts, and styles in the chart by editing the configuration in the JavaScript code.
Enhance Functionality:

Developers can extend the tool's capabilities, such as adding new features or integrating additional data analysis.
Technical Overview (For Developers)
Technologies Used:

HTML: Structures the web page content.
CSS: Styles the visual appearance of the page.
JavaScript: Handles file processing, data calculations, and dynamic content updates.
Chart.js: A JavaScript library used to create the interactive chart.
Client-Side Processing:

All computations are performed in the user's browser using JavaScript.
No server-side code or external data transmissions are involved.
