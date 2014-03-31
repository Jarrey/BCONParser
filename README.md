A custom configuration file reader/parser class: Call BCON configuration

Example:

###############################################################################
# This is comment
###############################################################################

[Persons]
Name=John William,Age=23,Country=US
Name:Le Seng|Age=32|Country=CN,Company=MS

[Products]
Office 2013
Windows 8.1
Windows Phone 8.1

This class can parse it into two collections, Persons and Products. and line "Name=John William,Age=23,Country=US" can be parsed as one object with three properties: "Name", "Age" and "Country".