# Proxy Client Executable

Install
----------------------
# 1. Get the installation package
# wget https://github.com/s31b18/proxy_client_runtime/raw/master/proxy_client.tar.gz
# 2. Decompress the installation package
# tar zxvf proxy_client.tar.gz 
# 3. Go to the decompressed directory
# cd afs_pclient_r
# 4. Run install.sh
# sudo sh install.sh
----------------------
Use
----------------------
# 1. Start the service
# service pclient start
# 2. Check the service has started
# service pclient status
# 3. Stop the service 
# service pclient stop
# 4. Check the public url
# go to afs_pclient_r
# cat ngrok/bin/host_url.txt
