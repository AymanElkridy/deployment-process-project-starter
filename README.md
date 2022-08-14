# Hosting a Full-Stack Application

## Infrastructure description

1. AWS RDS for hosting database.
2. AWS Elastic Beanstalk for hosting API.
3. AWS S3 for hosting frontend.

## App dependencies
### 1. Front-End
 1. Developmet
    - codelyzer
    - jasmine
    - karma
    - protractor
    - ts-node
    - tslint
    - typescript
    - @angular & @angular-devkit libraries
    - @ionic libraries
    - @types & @typescript libraries
 2. Production
    - core-js
    - rxjs
    - zone.js
    - @angular libraries
    - @ionic libraries
### 2. Back-End
 1. Developmet
    - chai
    - eslint
    - mocha
    - ts-node-env
    - typescript
    - @types & @typescript libraries
 2. Production
    - aws-sdk
    - bcryptjs
    - body-parser
    - cors
    - dotenv
    - email-validator
    - express
    - jsonwebtoken
    - pg
    - reflect-metadata
    - sequelize
    - sequelize-typescript

## Pipeline process
1. The project is pushed to it's GitHub branch.
2. CircleCi is triggered and a new workflow starts.
3. The workflow installs, builds & deploys the updated project.
4. The updated project is now hosted on our dedicated services (AWS).

## URL
Click [Here](http://udagram-frontend-bucket-1337.s3-website-us-east-1.amazonaws.com/) to go to the hosted website.
Or copy and paste this link:
```
http://udagram-frontend-bucket-1337.s3-website-us-east-1.amazonaws.com/
```

## Used Project
Udagram - provided app

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
