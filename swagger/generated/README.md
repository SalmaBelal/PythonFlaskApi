https://editor.swagger.io/

unzip python-flask-server-generated.zip -d python-flask-server-generated/

docker build . -t mynewserver

docker run -dp 8080:8080 mynewserver

