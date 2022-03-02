# mmsdtng-service
systemD service for mmsd-tng

Automated script run at boot manged by systemd

`git clone https://github.com/fbmoose48/mmsdtng-service.git`

`cd mmsdtng-service`

1. Create "/etc/systemd/system/mmsdtng.service"

`sudo cp ./mmsdtng.service /etc/systemd/system/`

2. Enable service

`sudo systemctl enable mmsdtng.service`

3. Start service

`sudo systemctl start mmsdtng.service`

4. Confirm service status

`sudo systemctl status mmsdtng.service`

