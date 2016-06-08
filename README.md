# PIA OpenVPN configurations with strong encryption settings

Private Internet Access now offers strengthened VPN encryption settings. However, they do not offer configuration files to easily import these settings into OpenVPN. So I made some.

These configurations support:

* UDP port 1197
* 4096bit RSA server certificate
* AES-256-CBC cipher
* SHA256 authentication
* TLS v1.0-1.2

Also included in this repository is the `ca_rsa4096.crt` certificate from PIA. I copied it from the [PIA forum thread announcing the strong encryption support](https://www.privateinternetaccess.com/forum/discussion/20093/).

Open an issue if you have any problems or suggestions for improvement.
