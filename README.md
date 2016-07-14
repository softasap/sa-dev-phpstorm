sa-dev-phpstorm
===============

[![Build Status](https://travis-ci.org/softasap/sa-dev-phpstorm.svg?branch=master)](https://travis-ci.org/softasap/sa-dev-phpstorm)

Installs Jetbrains phpstorm


Possible overrides:

Optional java install:

option_install_java: false
java_version: 7 # 6,8

Storm version:
phpstorm_version: "2016.2" # | "2016.1" |  10.0.3  | "10.0" | 9.0.2 | 8.0.3 | 8.0.1 | 7.1.4 | 6.0.3 | 5.0.4

Installation Directory
apps_dir: "/home/{{ansible_user_id}}/apps"
