## AWS Data

CloudFront Adress 

[https://d1j0a2cxkc2yn9.cloudfront.net/](https://d1j0a2cxkc2yn9.cloudfront.net/)

## Tasks


- 1 - Dockerfile is prepared, image is building. Image size is minimised to be less than 500 MB. - done (105 MB)
- 2 - Dockerfile is optimized. Files that change more often and commands that depend on them should be included later, files and commands that change less should be at the top. - done
- 3 - Folders are added to .dockerignore, with explanations. At least 2 big directories should be excluded from build context. Elastic Beanstalk application is initialized. -done

.git - exclude git file
.gitignore exclude gitignore file
.prettier exclude prettier file
**/*.spec.ts - exclude all test files
test - exclude test folder
dist - exclude build folder if app was builded
.eslintrc.js - exclude lint file
README.MD - exclude readme file 
node_modules - exclude node moduler folder

- 4 - Environment is created and the app is deployed to the AWS cloud. You must provide a link to your GitHub repo with Cart API service or PR with created Dockerfile and related configurations. - done (watch current repo)

- 5 - FE application is updated with Cart API endpoint. You must provide a PR with updates in your FE repository and OPTIONALLY link to deployed front-end app which makes proper API calls to your Cart service. - done (if you want to check front-end application you have to allow mixed content at your browser)

FE repository
[https://github.com/Max-Korsakov/nodejs-aws-fe/](https://github.com/Max-Korsakov/nodejs-aws-fe/)