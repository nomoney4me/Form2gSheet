# Form2gSheet

//  Modified version of Martin Hawksey's Google Script

//  https://mashe.hawksey.info/2014/07/google-sheets-as-a-database-insert-with-apps-script-using-postget-methods-with-ajax-example/

//  1. Enter sheet name where data is to be written below
        var SHEET_NAME = "Sheet1";
         
//  2. Run > setup
//
//  3. Publish > Deploy as web app
//    - enter Project Version name and click 'Save New Version'
//    - set security level and enable service (most likely execute as 'me' and access 'anyone, even anonymously)
//
//  4. Copy the 'Current web app URL' and post this in your form/script action
//
//  5. Insert column names on your destination sheet matching the parameter names of the data you are passing in (exactly matching case)
//	  - (optional)
//	  - My script compares the header with the e.parameter
