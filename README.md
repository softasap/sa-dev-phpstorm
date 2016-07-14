sa-dev-phpstorm
===============

[![Build Status](https://travis-ci.org/softasap/sa-dev-phpstorm.svg?branch=master)](https://travis-ci.org/softasap/sa-dev-phpstorm)

Installs Jetbrains phpstorm

    - {
        role: "sa-dev-phpstorm",
        option_install_java: true,
        java_version: 7,
        phpstorm_version: "2016.1"
      }


# Optionally install java
option_install_java: false

# if install java, which version
java_version: 7

# Supported phpstorm versions:
phpstorm_version: "2016.1" # 10.0.3  | "10.0" | 9.0.2 | 8.0.3 | 8.0.1 | 7.1.4 | 6.0.3 | 5.0.4



Possible overrides:

Optional java install:

option_install_java: false
java_version: 7 # 6,8

Storm version:
phpstorm_version: "2016.2" # | "2016.1" |  10.0.3  | "10.0" | 9.0.2 | 8.0.3 | 8.0.1 | 7.1.4 | 6.0.3 | 5.0.4

Installation Directory
apps_dir: "/home/{{ansible_user_id}}/apps"
