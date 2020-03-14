# PHP Custom runtime on Lambda

#Instructions
- 1 - Follow the commands listed in ec2-commands.txt:<br />
This will show you have to generate all the files on the EC2 or for a more detailed explanation<br />
- 2 - Follow the links below for a more detailed step-by-step guide:<br />

## Quick solution:
To get the example working:<br />
1 - Upload the runtime.zip file as layer 1 to Lambda<br />
2 - Upload the vendors.zip file as layer 2 to Lambda<br />
3 - Upload the hello.zip and goodbye.zip as individual functions to Lambda<br />
(remember to rename your functions to only `hello` instead of `hello.handler`)<br />

## Example based of these guides
https://aws.amazon.com/blogs/apn/aws-lambda-custom-runtime-for-php-a-practical-example/ <br />
https://aws.amazon.com/blogs/compute/scripting-languages-for-aws-lambda-running-php-ruby-and-go/ <br /> 
https://akrabat.com/serverless-php-on-aws-lamda/ <br />
