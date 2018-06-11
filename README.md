# macOS-zabbix_agentd
Zabbix Agent for macOS w/TLS encryption
Zabbix Agent for macOS w/TLS encryption

# Install HomeBrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# PCRE & OpenSSL provided by Brew
brew install pcre
brew install openssl@1.1



# Locations for Zabbix Agent files
/usr/local/sbin/zabbix_agentd
/usr/local/etc/zabbix_agentd.conf
/usr/local/etc/zabbix_agentd.conf.d/
/usr/local/bin/zabbix_get
/usr/local/bin/zabbix_sender
/usr/local/etc/startzabbix.sh
/LaunchDaemons/org.zabbix.zabbix_agent.plist
