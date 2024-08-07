# API-Set-Up
Quick tutorial on how to set up easily an API.

Make sure you have Node and NPM installed.
```bash
$ npm install -g dredd
```

Initialize Dredd. Mind the privacy of API key.
```bash
$ dredd init -r apiary -j apiaryApiKey:49a5672f93821bd24c80b89ff1a82e31 -j apiaryApiName:acrossow
```
Run the test, reports appear here.
```bash
$ dredd
```
