"# hosting-app" 
# File description:
## main.tf 
*We declare the bucket name as a variable ( as a rusult in this file we declare the name of our bucket),*
*the further steps which we see in this file are responsible for building the S3 bucket, and all rules allow us to access the bucket created above.Then using resource "aws_s3_object" "index" (index.html) we uploading our main website. Same thing we doing with two other files error.html and robert.jpg.*
## output.tf
*As a result of using our output file we see in command line the URL from which we can reach our website.*
## strona.tf
*In this file we adding our provider (AWS) to interact with the resources which we create in futher action.*
## variable.tf
*As mention before in this file we decalre name of our bucket.*
## Additional
*Other files which are not included in our description are creating automaticaly after iniziating terraform command.*

## Instruction:
*1.Run terraform init*

*2.Run terraform plan (showing us the resources which will be creating after apply option)*

*3.Run terraform apply (sometimes is required to run it twice)*

## Summary
*As a result of running terrafrom apply , you should see the website endpoint which will be your URL address from where you can admire your website.*

# Warning !
**To run this page you need to have install terraform and the configuration file should be on same path as you project which you want to run.**