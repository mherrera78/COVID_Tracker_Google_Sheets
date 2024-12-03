# COVID Tracker - Google Sheets / Google Forms

This repository showcases an application built with Google Script to manage a COVID tracker on Google Sheets.

**Context:** The following code is written in Google script. This code was seating behind a Google Sheet .
The purpose of this script is to validate, on a daily basis, the students whose parents had filled out a *“Covid health check”* form by a certain time of the day.

If a parent had not filled the form, he/she would receive an automatically generated email with a reminder, as well as the link to the form.

At the same time, this script would generate an email to the school nurse/registrar with a summary of parents who had not submit the form along with direct contact information, to facilitate the contact and minimize the time that the nurse/registrar would need to look for contact information on the school system.

Finally, it generates an executive summary to the principal with statistics and charts.

**Reporting:** 
To add value to the solution proposed, I generated a reporting layer using daily and historic data. 

Samples of these reports include:
- List of students who were reported as “covid positive” in the last 14 days.
- Contact trace report. When a student became positive, a report would generate a list of students who were exposed to the student infected based on Bus, classroom, clubs, etc.
