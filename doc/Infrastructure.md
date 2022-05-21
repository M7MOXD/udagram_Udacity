    Back-end API Environment:
        AWS Elastic Beanstalk Node.js 14 running on 64bit Amazon Linux Server
            URL - http://ebudacity-env.eba-zkfk7ndk.us-east-1.elasticbeanstalk.com/
            Environment includes Postgres database - endpoint: http://udacity.cpfetlctoywg.us-east-1.rds.amazonaws.com
            App name: ebudacity
            S3 bucket for uploading ebudacity app - elasticbeanstalk-us-east-1-779354412666

    Front-End:
        AWS S3 bucket: s3xudacity
            Configured for static website hosting: http://s3xudacity.s3-website-us-east-1.amazonaws.com/

    Deployment Pipeline:
        CircleCI connected to main branch of GitHub project - https://github.com/M7MOXD/udagramFullStackApp_Udacity
