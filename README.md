# Udacity Full-Stack Application hosting (Udagram)


### **Project overview**

Udagram is provided bu Udacity as an alternative starter project. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

### **Dependencies**

```
- Node v14.15.1 (LTS)
- npm 6.14.8 (LTS)
- AWS CLI v2
- A RDS database running Postgres.
- A S3 bucket for hosting uploaded pictures.
```

### **Screenshots**

All requested screenshots included into this repo under `screenshots` directory.
You can preview some of them hereunder, click on below links to view:

- [CircleCI first build step.](http://zabuck012999.s3-website-us-east-1.amazonaws.com/screenshots/CircleCI-1.Build.jpg)
- [CircleCI second build step.](http://zabuck012999.s3-website-us-east-1.amazonaws.com/screenshots/CircleCI-2.Deploy.jpg)
- [CircleCI all steps completed.](http://zabuck012999.s3-website-us-east-1.amazonaws.com/screenshots/CircleCI-All_Steps.jpg)
- [RDS Overview.](http://zabuck012999.s3-website-us-east-1.amazonaws.com/screenshots/RDS-Overview.jpg)
- [S3 Bucket Overview.](http://zabuck012999.s3-website-us-east-1.amazonaws.com/screenshots/S3.jpg)
- [Elastic Beanstalk Overview.](http://zabuck012999.s3-website-us-east-1.amazonaws.com/screenshots/EB.jpg)

## Hosted production application

You can navigate to this application through this URL [Udagram](http://zabuck012999.s3-website-us-east-1.amazonaws.com)

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
