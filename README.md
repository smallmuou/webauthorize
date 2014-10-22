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
    