# blogengine

This is back end of a website for programmers, it allows to register account, post your articles, comment and like others posts

## Technologies
Java, Sping Boot, Maven

## Getting Started

to start on local machine: clone repository, add to application.yml you database url, user name, password and email adress and password for mail sender

to start on heroku add to config vars you database url (ex JAWSDB_URL)

### Cloud Storage

you can use Amazonas S3 to store you static asssets 

for that need to add S3 config, S3 storage url, S3 credentials

deployed on heroku with s3 storage project:

https://git.heroku.com/uploadamazonass3.git

https://uploadamazonass3.herokuapp.com/
