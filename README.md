# NEWS APPLICATION

## ITWS 2 Project by Ananya Arun

### Pre-requisites

 1. Python 3

	 `sudo apt-get install python3`

 2. Flask
 
	 `pip3 install flask`




### Steps To Run The News App:-

  1. git clone https://github.com/ananyaarun/News-App-in-Flask.git
  
  2. cd News-App-in-Flask/Project
  
  3. python3 app.py

The following files will currently work on http ,

To run the app with https make the following changes in app.py:-

  1. app.run(ssl_context=('cert.pem', 'key.pem'))
  
  2. make all the links from http to https
