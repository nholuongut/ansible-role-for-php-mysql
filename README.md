# Ansible Role: PHP-MySQL

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Installs PHP [MySQL](https://www.mysql.com/) support on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    php_enablerepo: ""

(RedHat/CentOS only) If you have enabled any additional repositories (might I suggest nholuong.repo-epel or nholuong.repo-remi), those repositories can be listed under this variable (e.g. `remi,epel`). This can allow you to install later versions of PHP packages.

    php_mysql_package: php-mysql # RedHat
    php_mysql_package: php5-mysql # Debian

The PHP MySQL package to install via apt/yum. This should only be overridden if you need to install a unique/special package for MySQL support, as in the case of using software collections on Enterprise Linux.

## Dependencies

  - nholuong.php

## Example Playbook

    - hosts: webservers
      roles:
        - { role: nholuong.php-mysql }

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟