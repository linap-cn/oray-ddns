# Simple-ddns
## ��� ##
c����ʵ�ֵ�ͨ�ö�̬�������³���
-------------
## �÷� ##
Usage: ddns [options]  
  -f  --config file     Read config from file.  
  -h  --help            Display this usage information.  
  -u  --user username   User Name to login.  
  -p  --pass password   Password to login.  
  -H  --host hostname   Hostname of the ddns server.  
  -U  --url url         Url without hostname to send get request.  
  -t  --time [s]        Optional. Time between two request. Default:900.  
  -A  --agent [s]       Optional. User-Agent. Default:ddnsv0.1.  

  �����systemd������ʹ��# make install�Զ�����Ϊservice���޸������ļ�/etc/ddns.conf��ͨ��# systemctl start ddns����
-------------
## TODO�� ##
1.  �����ļ��п����滻[ip][user][pass]�Ȳ�����
2.  ���������汾ϵͳ��install-sh