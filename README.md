# Web Authorize

## Description
* This script is for my company's web authorization to access to Internet.
* Currently this script only support Linux and MacOSX.
* Only support bash

##Usage

./webauthorize.sh [-a username:password] [-i interface] [-p ip] [-h] [-v]

* Login:
    * ./webauthorize.sh -a username:password
    * ./webauthorize.sh -a username:password -i eth0
    * ./webauthorize.sh -a username:password -p userip
* Logout
    * ./webauthorize.sh
    * ./webauthorize.sh -p userip
    
## Note
The latest web site use rsa. You need use [jssh](https://github.com/smallmuou/jssh) to generator password.
<pre>
jssh password-generator.js < your password>
</pre>
it will output like follow:
<pre>
096cf31121c4191378302341b8098fbef863a7942013fa8a7e73122f91c083d17042bf5b71a19fd8a877b0aa1b8ea453b7125adf92c037a5cf6920894df8fa3afe4928584115699464337529f7d68469921440642a58b8561a08af40426914996352148bdbd89743a622a54bb3e5b3a734d04cc403c7a6631f3cbf2535607f1c
</pre>