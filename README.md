To run the server do the following:

pip install -r requirements.txt

In BASH: export FLASK_APP=sample
         export FLASK_ENV=development
         flask run (optional if you want a specific host and port) -h yourhost -p yourport

In PWS: $env:FLASK_APP = "flask_app"  
        $env:FLASK_ENV = "development"
        flask run (optional if you want a specific host and port) -h yourhost -p yourport

In CMD: set FLASK_APP = "flask_app"  
        set FLASK_ENV = "development"
        flask run (optional if you want a specific host and port) -h yourhost -p yourport