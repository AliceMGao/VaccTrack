# VaccTrack
This web application and database project was geared towards healthcare workers in a series of clinics who needed to keep track of new vaccinations they’d be delivering as part of Covid-19 relief efforts, and also beyond that in the future. In this repository you can find the zip version of the project for SQLite and a MySQL database version, both can be launched on any computer running Python, Flask, and either or SQL application.
The project went through several iterations as new functionalities were added, with heavy coding in HTML and Python as well as the use of Flask, JavaScript, and CSS for Web structure and UI rendering.
Functionalities included during the dev process:
*	Creation of new patient records
*	The ability of existing healthcare workers to add New Accounts for their fellow Health Care Workers
* Password encryption to protect these accounts.
* Patient records search
* Creation of new vaccination records with detailing of:
  * Type of vaccination
  * Date time of administration
  * Dose number
  * Administering healthcare worker
  * Clinic location
* Adding notes on the presence of vaccination reactions or absence of such
<img src='VaccTrackSlow.gif' width='1220'>
The Gif above shows an overview of the application. From being launched in the local computer, entering the page of the VaccTrack web application on Internet Explorer, login in as an admin/ healthcare worker, searching up a patient, adding a vaccination record to their file, additional notes on any reactions, and showing the database view where the same information appears on refresh.
This project was an endeavor, but ultimately rewarding to me in developing a thorough understanding of creating an easily expandable web interface to match the data collection that happens in a clinical setting. There’s baseline importance in gearing any such project to the clinical perspective where there is ease for health information input and collection, as well from the decision support angle with ease of data extraction for longer-term trends analysis and reporting.

# Disclaimer
All data have been fictional for the use of the project, and no identifying information is available through the Web UI interface or database access.
