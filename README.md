# Retention Data Generator

A simple, user-friendly web tool that visualizes and analyzes attendee retention for webinars, online courses, or any timed sessions. By uploading your attendance data, you can generate insightful retention charts and tables without any technical setup.

## Features

- **Easy Data Upload**: Simply upload a CSV file with your attendance data.
- **Instant Processing**: The tool processes your data directly in your browser.
- **Interactive Retention Chart**: Visualize how attendee retention changes over time.
- **Summary Table**: See retention percentages at key time intervals.
- **Detailed Data Table**: Access minute-by-minute retention data.
- **Download Options**:
  - Retention Data CSV: Download the processed data for further analysis.
  - Chart Image: Save the retention chart as a PNG image.

## How It Works

### 1. Prepare Your Data

Create a CSV (Comma-Separated Values) file with two columns:

- `Person`: A unique identifier for each attendee (e.g., name, email, or ID number).
- `Time Duration`: The total time each person spent in the session, measured in minutes.

Example:

```csv
Person,Time Duration
Attendee 1,60
Attendee 2,45
Attendee 3,30
Attendee 4,15
