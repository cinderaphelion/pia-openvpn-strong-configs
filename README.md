# PIA OpenVPN configurations with strong encryption settings

Private Internet Access began offering [strengthened VPN encryption settings](https://www.privateinternetaccess.com/forum/discussion/20093/) on December 28 2015. However, they did not at that time provide any configuration files to easily import these settings into OpenVPN. So I made some. They are available in the `conf` folder.

On July 8 2016 Private Internet Access began providing strong encryption configuration files from their [Client Support page](https://www.privateinternetaccess.com/pages/client-support/#first). However these config files [did not work on Linux due to incorrect casing](https://www.privateinternetaccess.com/forum/discussion/21822/fix-all-the-new-connection-files-in-linux-for-import). So I fixed them. They are available in the `ovpn` folder.

I included the `.crt` and `.pem` certificates in this repository directly from [the PIA source](https://www.privateinternetaccess.com/openvpn/openvpn-strong.zip).

## Configuration Details

* UDP port 1197
* 4096bit RSA server certificate
* AES-256-CBC cipher
* SHA256 authentication
* TLS v1.0-1.2

Open an issue if you have any problems or suggestions for improvement.
