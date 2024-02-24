# How-To-Setup-Root-User

1. You should be outside of any folder / file / directory and You need Be in root user ``sudo -s``.
2. You need to set the password for the root user ``sudo passwd root``.
3. You need to go in a file .So run `nano /etc/ssh/sshd_config`.
4. You need to go down and find `PermitRootLogin` and `PasswordAuthentication` make them Yes.

# Image
![image](https://github.com/CoconutGamer/How-To-Setup-FTP-Access/assets/154960261/7c187de7-aba0-4cb0-8f1d-ca7b5d854535)

5. Then run `sudo systemctl restart sshd` So that the changes take place.

> [!NOTE]
> The Port `22` Shoud Be Open In The Firewall.
