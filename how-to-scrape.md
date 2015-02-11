# How did I scrape

### Observe the flow

- Visit the page http://www.mapsofindia.com/delhi/information/mcd-circle-rates.html
- View page source
- See the drop down. See how it works or created
- The drop down came from http://www.mapsofindia.com/delhi/information/mcd-circle-rates.js
- See what happens when drop down value is changed and find button is clicked
- On click of the buttom calls a javascript function loadXMLDoc()
- What does loadXMLDoc() do?
- Function makes an AJAX request to get the values for example http://www.mapsofindia.com/delhi/information/next.php?q=Zindpur
- See what does http://www.mapsofindia.com/delhi/information/next.php?q=Zindpur return
- it returns a table with values

### Get ready with initial data
- Intial data which needs to be sent to AJAX request is Colony names
- Takes http://www.mapsofindia.com/delhi/information/mcd-circle-rates.js
- Open in a good text editor that supports good (regex) search replace 
- Notepad++, SublimeText, TextAdpet are good to work with
- Make an array of all the values using search replace in text editor

### Scrape it now
- Code in python or in any other way to send the request for each colony
- Parse the response
- Insert into DB
- Export the values into a csv using datafreeze


