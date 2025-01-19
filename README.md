I created a directory named Marketpeak_Ecommerce using the bash terminal "mkdir Marketpeak_Ecommerce"
i changed directory into "Marketpeak_Ecommerce and i initialized a git repository 
i downloaded a template from the list made available to us "2130_waso_stategy", thereafter extracting  it to my directory s:::"Marketpeak_Ecommerce"
i set my git global configuration using username "spiffy 25" and e mail "spiffy.25@outlook.com"
staged ,commit, and pushed my template to github 

The second phase is to deploy "Marketpeak_Ecommerce and i started by setting up an Ec2 instance .
i created and launched an instance named Market peak using the Amazon linux AMI 
i created a pemkey when launching the instance and used it to connect to yhe instance using the command  ssh -i "marketpeak.pem" ec2-user@ec2-3-93-237-51.compute-1.amazonaws.com
i generated an SSH keypair using the command ssh-keygen , I named it "RSAKEY" and it generated a fingerprint key and also a randomart image 
i learnt what a passphrase was: used to add extr  a layer of security 
i cd into my .ssh , and i was able to dosplay and copy my public key .
i attached the ssh key to my github account 


i installed a  Apache HTTP server web server on my instance using the command "sudo yum update -y"
