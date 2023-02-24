# Installation

1. Install Git and Python 3 on your server.
2. Clone the PYbot Github repository to your server via Git: `$ git clone https://github.com/XtraFoxx/Simple-Python-DDoS-putty.git`.
3. Change the host address and C&C port in the configuration section in [bot.py](/bot.py) to your server address and C&C port.
4. Start the CnC server by executing the command: `$ python cnc.py <cnc port>`.
5. Add accounts in [logins.txt](/logins.txt) using the format: `username:password`.
6. Connect to the server through [PuTTY](https://www.putty.org/) on a raw socket connection.
