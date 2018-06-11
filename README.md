# macOS-zabbix_agentd
Zabbix Agent for macOS w/TLS encryption<br>
Zabbix Agent for macOS w/TLS encryption

# Install HomeBrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# PCRE & OpenSSL provided by Brew
brew install pcre<br>
brew install openssl@1.1

# Locations for Zabbix Agent files
/usr/local/sbin/zabbix_agentd<br>
/usr/local/etc/zabbix_agentd.conf<br>
/usr/local/etc/zabbix_agentd.conf.d/<br>
/usr/local/bin/zabbix_get<br>
/usr/local/bin/zabbix_sender<br>
/usr/local/etc/startzabbix.sh<br>
/LaunchDaemons/org.zabbix.zabbix_agent.plist
