# Workflow 4

- Start with “On Form Submission” – when someone fills and submits the form, the workflow begins.
- The submitted form data is added to your Google Sheet using the Append Row in Sheet node.
- The Google Sheets Trigger watches the sheet and detects whenever a new row is added.
- When a new row appears, the trigger sends that data to the Send a Message (Gmail) node.
- Gmail automatically sends you an email notifying that a new entry was added in your sheet.
- When you click Execute Workflow, you can test the entire flow and see the email instantly.

# Screenshot
<img width="1066" height="493" alt="Screenshot 2025-11-22 123608" src="https://github.com/user-attachments/assets/dae71da6-fa93-41a5-961f-9a6111a1f24f" />
