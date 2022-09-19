
# Light switch control in browser 

This practise project learned me how to connect external device (in this case microbit) via serial and change something on web page. 


### How I started:

* Make code for microbit, basic serial connection, sending only two letters aa or bb.
* test connection with external device with minicom program in ubuntu if it receives those letters, it did.
* Then python writes the data into json file (ref:time aa:time bb:time ) with timestamp that shows the latest stamp so I could code the program to know which button was pressed latest. 
* those conditions were made in html page in json query.
* Html reads the json file in loop, and updates that into browser page. 


* script file (.py) must be in gci folder and executable
* file permissions are important


### Executing program

* Ubuntu 
* Apache2
* Ajax
* Json
* Python
* minicom useful to test serial connection

