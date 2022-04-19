##Install SSL Centos##  

1. SSLCertificateFile

2. SSLCertificateKeyFile
**IMPORTANT: This must be the key generated with original CSR, that request the WildCard**

3. SSLCACertificateFile
**Install Apache and mod_ssl on centos 7**  

sudo yum install httpd
sudo systemctl enable httpd.service

sudo yum install mod_ssl

sudo mkdir /etc/ssl/private
sudo chmod 700 /etc/ssl/private

**Set Up the Certificate**

/etc/ssl/private/__stcenter_net_cert.cer
/etc/ssl/private/star_stcenter_net.key
/etc/ssl/private/__stcenter_net_interm.cer

sudo apachectl configtest

sudo systemctl restart httpd.service

**Set a A record in Godaddy, point to public IP and the ServerName:**


**WordPress install SSL.**
Virtualhost: DocumentRood “/var/www/html/wordpress”

Godaddy A-record point to ServerName

Use IP to test

https://pd.stcenter.net


**Install Plug-Ins**
https://pd.stcenter.net/wp-admin

Tools » Better Search Replace

Setting - General

But still need fix mixed contents.

Finished:
