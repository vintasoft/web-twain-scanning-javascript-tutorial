# Vintasoft Web TWAIN Scanning Tutorial for JavaScript

This HTML+JavaScript project uses <a href="https://www.vintasoft.com/vstwain-dotnet-index.html" target="_blank">VintaSoft TWAIN .NET SDK</a> and demonstrates how to:
* Get the list of TWAIN devices
* Select TWAIN device
* Acquire images from TWAIN device
* Preview scanned images

## Usage
If you want to read tutorial, which describes how to create this project from scratch, please read tutorial <a href="https://www.vintasoft.com/docs/vstwain-dotnet-web/Programming-Twain_Web-Tutorials-Acquire_images_from_TWAIN_scanner_in_JavaScript.html" target="_blank">Acquire images from TWAIN scanner in HTML+JavaScript application</a>.

If you want to use this ready-to-use project, please do the following steps:
1. Get the 30 day free evaluation license for <a href="https://www.vintasoft.com/vstwain-dotnet-index.html" target="_blank">VintaSoft TWAIN .NET SDK</a> as described here: <a href="https://www.vintasoft.com/docs/vstwain-dotnet-web/Licensing-Twain_Web-Evaluation.html" target="_blank">https://www.vintasoft.com/docs/vstwain-dotnet-web/Licensing-Twain_Web-Evaluation.html</a>

2. Update the evaluation license in "src\js\web-twain-scanning-javascript-tutorial" file:
   ```
   Vintasoft.Twain.WebTwainGlobalSettingsJS.register('REG_USER', 'REG_URL', 'REG_CODE', 'EXPIRATION_DATE');
   ```

3. Upload HTML+JavaScript application to web server.
Upload this application to a web server. This is obligatory step because VintaSoft Web TWAIN service does not work if HTML page is opened from file system, i.e. HTML page has URL "file:///somepath" and application is used as a desktop application.

4. Open HTML page in web browser and see the result.

5. If VintaSoft Web TWAIN service is not installed on your Windows computer:
* Click "Download installer of VintaSoft Web TWAIN service" link on web page, download the installer and install VintaSoft Web TWAIN service to your local computer. VintaSoft Web TWAIN service serves HTTP-requests from VintaSoft TWAIN JavaScript API and allows to work with local TWAIN scanners.
* Reload web page and try to work with local TWAIN scanners.
