
# UP REPO DEBIAN
<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot</code></pre>

# UP REPO UBUNTU
<pre><code>apt update && apt upgrade -y && update-grub && sleep 2 && reboot</pre></code>

### INSTALL SCRIPT
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/okysmilee7/Safassh/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
</code></pre>

### UPDATE SCRIPT 
<pre><code>wget -q https://raw.githubusercontent.com/okysmilee7/Safassh/main/update.sh && chmod +x update.sh && ./update.sh
</code></pre>
