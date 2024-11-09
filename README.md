This is used to create a ami and covert it to server and install whatever we need and then convert back as ami to use it in project

Workstation will create a ami
Called Golden Image Ami using packer

Then it is called server where we install ansible

Now this Golden image ami is used as AMI creation in roboshop project to
create different ami for each functionality like Cart, User etc

This is becoz to save time becoz this golden image ami comes with ANSIBLE installed
already