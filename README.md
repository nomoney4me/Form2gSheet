# Form2gSheet

Modified version of Martin Hawksey's Google Script
<p>https://mashe.hawksey.info/2014/07/google-sheets-as-a-database-insert-with-apps-script-using-postget-methods-with-ajax-example/

1. Enter sheet name where data is to be written below<br>
        var SHEET_NAME = "Sheet1";
2. Run > setup<br>
3. Publish > Deploy as web app<br>
        - enter Project Version name and click 'Save New Version'<br>
        - set security level and enable service (most likely execute as 'me' and access 'anyone, even anonymously)<br>
4. Copy the 'Current web app URL' and post this in your form/script action<br>
5. Insert column names on your destination sheet matching the parameter names of the data you are passing in (exactly matching case)<br>
        - Now optional<br>
        - My changes to the script compares the header with the e.parameter and create any new headers<br>
