# Author: Emily Greason

## Lab 16 - AWS Cloud Servers

### Links

 Task 1: http://express-server-gui-env.eba-amxnnepi.us-west-2.elasticbeanstalk.com/ 

 Task 2: http://express-cli-env.eba-gpwkqnrd.us-west-2.elasticbeanstalk.com/

### Process Documentation

- install AWS and EB init

- Create an simple express server (I cloned a repo of a simple express server from John Cokos for this lab)

- To deploy via the AWS control panel, go to Amazon ElasticBeanstalk and create a web server environment - gui - and upload the code from the express server I created via a zip file

- To deploy client side, in the terminal do aws configure and make sure the AWS Access Key ID and AWS Secret Access Key are populating along with the default region and output format (JSON)

- To get these access keys, go to amazon and create a user in IAM (this is where we manage Amazon users), the access key pop up and a separate window will contain the secret access key (will only show once so need to save it somewhere)

- In terminal, eb init, choose region, create a new application (2) and name the app (cli), follow the prompt - enter yes, 1, no no to the questions that are asked

- In terminal, ev create new-app-name - wait for the status to be ready and health to be green (eb status to check)

- eb deploy will deploy the app from the client side
