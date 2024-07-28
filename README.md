# time-caller
First login in VPS using SSH key and password
Use complete  name “ssh root@111.111.11.11”
And then toye yes
And then type password
And then enter  “sudo apt-get update” if the VPS is login first time
And then install git with this code “sudo apt-get install git”
And then install node js with this code “curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash”
And then set the source with this code “source ~/.bashrc”
And then enter  “node –v” to ckech visrsion ( it should be greater then 12)
If failed type code “apt install nodejs” to reinstall node ks properly
Again check node virsion with “node –v” and if it shows greater then 12 then proceed
And then type code “npm install pm2 –g” to install pm2 on server
If it ask to insatall “apt install npm” install it
And again try to install “npm install pm2 –g”
And then type “git clone https://github.com/lexeach/CloseRoundAutoCaller”	
After cloning the repository type “ls”
And type “cd CloseRoundAutoCaller”
And then type “nano .env”




