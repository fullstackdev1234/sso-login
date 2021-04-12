#SSO Signin Demo
# /etc/hosts configuration
127.0.0.1 sso.test.com
127.0.0.1 client.test.com

# npm install
cd sso-server & npm install
cd sso-client & npm install

# run sso-server and sso-signin client
cd sso-server & npm run start
cd sso-client & npm run start

# try to using browser
open http://sso.test.com:3010 first and then 
login to http://client.test.com:3020.
Then back to http://sso.test.com:3010 and you can see SSO correctly working.