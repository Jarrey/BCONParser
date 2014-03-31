A custom configuration file reader/parser class: Call BCON configuration<br /\>
<br /\>
Example:<br /\>
<br /\>
\###############################################################################<br /\>
\# This is comment<br /\>
\###############################################################################<br /\>
<br /\>
\[Persons]<br /\>
Name=John William,Age=23,Country=US<br /\>
Name:Le Seng|Age=32|Country=CN,Company=MS<br /\>
<br /\>
\[Products]<br /\>
Office 2013<br /\>
Windows 8.1<br /\>
Windows Phone 8.1<br /\>
<br /\>
This class can parse it into two collections, Persons and Products. and line "Name=John William,Age=23,Country=US" can be parsed as one object with three properties: "Name", "Age" and "Country".