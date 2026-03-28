# AutomatedBugDetector


<h2>Description</h2>

A Python Program that utilizes Beautiful Soup to detect broken links, broken images, and measures response times for getting the web pages to load. 
It then automatically compiles all of these into a generated html report and sends the report to your email in both the body and as an attachment you can download.
Utilizes a Web crawler to go through as many links as you want on the page.

As an added bonus I dockerized the program and have a requirments.txt file with all external libraries needed to run.

To run it in Docker: docker run -it --rm automated-bug-detector

<h2>Tools</h2>

- Visual Studio Code
- Python
- Beautiful Soup
- Docker

Test Site Used: https://the-internet.herokuapp.com/

<h2>Demo</h2>
<img src="assets/automatedbugdetector.gif" width="600" alt="Demo GIF"/>

<h2>Docker Demo</h2>
<img src="assets/automatedbugdetectorDocker.gif" width="600" alt="Demo GIF"/>

<h2>Code Snippet of main.py</h2>
<img src="https://i.imgur.com/LLIpg1z.png" height="80%" width="80%" alt="AutoBugDetector"/>

<h2>File Structure</h2>
<img src="https://i.imgur.com/hWq0tpL.png" height="40%" width="40%" alt="AutoBugDetector"/>




<h2>Email Body Output</h2>

<img src="https://i.imgur.com/s9q2Fmv.png" height="40%" width="40%" alt="AutoBugDetector"/>
<img src="https://i.imgur.com/MQgQ8ZN.png" height="40%" width="40%" alt="AutoBugDetector"/>
<br/>
<br/>


<h2>Email Attachment Output</h2>

<img src="https://i.imgur.com/jzMVy1v.png" height="50%" width="50%" alt="AutoBugDetector"/>
<br/>
<br/>
<a href="C:\Users\DinkDink\Downloads\Bug_Report.html" download>Example Attached HTML Report</a>



