# Accessing-EC2-VM-through-MobaXterm
To connect with AWS ec2 instance with MobaXterm first go to MobaXterm settings and choose the persistent home directory path- the path should be where you kept them pem file.

Then to check if the Pem file is there or not use the command
Ls -l | grep filename.pem
![image](https://github.com/alekhyamarella194/Accessing-EC2-VM-through-MobaXterm/assets/148741290/348b6655-cc13-494a-a558-94dd9a42352b)

To connect with the EC2 instance command
Ssh -I “filename.pem” ubuntu@public ip address
![image](https://github.com/alekhyamarella194/Accessing-EC2-VM-through-MobaXterm/assets/148741290/7411e6b7-7950-4d6c-9820-777d38a58f6e)

Azure Virtual Machine
To connect Azure Virtual Machine from MobaXterm type below command
ssh vmname@publicipaddres

then type type the password you created while creating the vm , the password will be asked.
![image](https://github.com/alekhyamarella194/Accessing-EC2-VM-through-MobaXterm/assets/148741290/b2c383e9-eea6-4bab-b6b5-480e9fd08b68)

Azure Key
First change file permission to read only by command
Chmod 400 filepath
![image](https://github.com/alekhyamarella194/Accessing-EC2-VM-through-MobaXterm/assets/148741290/fed9584f-126f-4724-b428-75e92e44cbeb)

To look at file permission
![image](https://github.com/alekhyamarella194/Accessing-EC2-VM-through-MobaXterm/assets/148741290/730f99df-0863-41c0-be5f-40a8c0b9e1f2)

To make connection:
Ssh -I filepath vmusername@publicipaddress.
![image](https://github.com/alekhyamarella194/Accessing-EC2-VM-through-MobaXterm/assets/148741290/c03b1c24-a5fa-4d76-9465-d4831ad1f82d)

To do automation creating of virtual machines from AWS CLI
First install the AWS CLI
Then generate access key
Then open CLI PowerShell/MobaXtrem
![image](https://github.com/alekhyamarella194/Accessing-EC2-VM-through-MobaXterm/assets/148741290/ba93ec19-1961-4d21-809b-4616d3e81336)
![image](https://github.com/alekhyamarella194/Accessing-EC2-VM-through-MobaXterm/assets/148741290/97fe8e8b-8463-41e6-8d3d-4c67558c13bc)








