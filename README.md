**Simple Python Flask App hosted on Github. **
<br> Pushed using Github Action : https://github.com/sankeerthb/sample-docker-python-flask-app

**Run Local: **
<br> docker run --pull always -p 80:80 sankeerthboddu/python-flask:latest

**Sample Output :** 
<br> Unable to find image 'sankeerthboddu/python-flask:latest' locally latest: Pulling from sankeerthboddu/python-flask 9e3ea8720c6d: Pull complete fe9f5cfcf49b: Pull complete Digest: sha256:a10b7138728dca5829ff36eb510aa414a1df56eaec623a9d47dd91fc63ee695b Status: Downloaded newer image for sankeerthboddu/python-flask:latest
Serving Flask app 'python-flask-app'
<br> Debug mode: off WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
<br> Running on all addresses (0.0.0.0)
<br> Running on http://127.0.0.1:80
<br> Running on http://172.17.0.2:80 Press CTRL+C to quit 172.17.0.1 - - [09/May/2023 01:11:35] "GET / HTTP/1.1" 200 - 172.17.0.1 - - [09/May/2023 01:11:36] "GET /favicon.ico HTTP/1.1" 404 -

**Sample UI: **
<br> Hello dfEnvName! Hostname: b332
