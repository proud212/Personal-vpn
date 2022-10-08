
cd /tmp/ && yum install git -y && git clone https://github.com/proud212/Personal-vpn.git && cd Personal-vpn/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh 

دستورات زیر برای اضافه کردن کاربر به سرور:

useradd [username] - 
passwd [username]

