# Metasploit Modules

- auxiliary/scanner/ssh/ssh_version
- auxiliary/scanner/ssh/ssh_login

Use /usr/share/metasploit-framework/data/wordlists/common_users.txt username dictionary
Use /usr/share/metasploit-framework/data/wordlists/common_passwords.txt password dictionary

Hydra: hydra -L /usr/share/metasploit-framework/data/wordlists/common_users.txt -P /usr/share/metasploit-framework/data/wordlists/unix_passwords.txt -t 4 TARGET_IP ssh
