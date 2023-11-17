In Zabbix the icons are stored in base64 encoding in the database. This simple script extracts icons from Zabbix and save files to local filesystem

**Required**

requests, configparser and pybase64 python3 modules

**Usage**
1) Edit hte config.ini file with your Zabbix APi URl and the API token;
2) Run the script

You can find the output files in the same directory af the script. The files uses the same name of images.
