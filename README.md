Collection and analysis of various logs (e.g., process logs, network logs) are fundamental activities in computer forensics. Ensuring the security of the activity logs is therefore crucial to ensure reliable forensics investigations. However, because of the black-box nature of clouds and the volatility and co-mingling of cloud data, providing the cloud logs to investigators while preserving users’ privacy and the integrity of logs is challenging. The current secure logging schemes, which consider the logger as trusted cannot be applied in clouds since there is a chance that cloud providers (logger) collude with malicious users or investigators to alter the logs.

Dependencies:
 1. Python2.7
 2. MongoDb
	
Python Dependencies:
 1. eventlet
 2. flask_socketio
 3. pycrypto
 4. bitarray
 5. pymongo

Steps to run server:
 1. Start mongodb server on localhost
 2. Start this application server by executing following command
    `>> python init.py`
 3. The server will run on http://127.0.0.1:4000/
 4. Open http://127.0.0.1:4000/ in a web browser
