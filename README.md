# AWS

IAM = Identity and Access Management - Global services 
Root account created by default, shouldnt be used or shared 
users are people within your organisation, and can be grouped.
Users and Groups can be assigned by json documents called policies.
This policies define the permissions of the users. 
In aws we dont allow many user uses all services, It cost lot of money and security 
IAM Policies and permissions.


Creating Iam users and policies .

GO to nthe dashboard ... Search IAM 
I am is aglobal services.
go to users 
add a user.(Srikanth)
I wanted  to create an iam USER
Custom Password (Stark)...Next
create a group  (AdministraterAccess) ....create a user group
Add a user to group (Admin)...Next
Add Tags  .. If needed 
Create User. 
Change Alisa name /.


IAM Password Policy


cloud shell .......is Aws cli.

Roles .. Create a role.
AWS Services
EC2....next
next we need lo assign policies
Examplew : IAMREADONLYPOLICY....NExt
ROle name 


access key and secret key never share 


EC2 Budgets Alerts (Email )

Instance types :

General purpose -------- greate for webservers or code repositiries, Blc B/w compute, memory, networking.
compute optimised ------ greate for tasks that requiured high performances or dedicated gaming servers 
memory optimised -------  for large data sets in memory, databases, performing unstructed data, for business inteligence 
acclerated computing --- storage-intensive tasks that requir high read and write access to larger data sets on local storages 
storage optimized 
instance feature 
measuring instance performance 


security groups --- control traffic in and out from the instances by ip address and security groups 
inbound rules ==== from other to the instances 
outbound rules === from instance to others.
access to ports 
authorised Ip Ranges.
Http , https , tcp, ssh , custom tcp 
