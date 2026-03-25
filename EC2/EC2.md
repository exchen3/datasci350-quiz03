#1 Connect to the server

ssh -i "qtm350.pem" ubuntu@ec2-3-16-214-59.us-east-2.compute.amazonaws.com

#2 Copy files from the github repository
git clone https://github.com/exchen3/datasci350-quiz03.git

#3 upload files to the terminal

scp -i qtm350.pem traffic_analysis.py website_traffic.txt ubuntu@ec2-3-16-214-59.us-east-2.compute.amazonaws.com:~

#4 Run the files

python traffic_analysis.py

#5 Create a os.txt

cat /etc/os-release > os.txt

#6 Download the files

scp -i qtm350.pem traffic_analysis.py website_traffic.txt ubuntu@ec2-3-16-214-59.us-east-2.compute.amazonaws.com:~


