# Log Book

## Steps taken to set up this website

* Create workspace on c9.io.
* Initialize local git repository on c9's workspace.
* Follow instructions to install Yii framework on c9, from \cite.
* Create repository on GitHub to store c9's workspace as backup.
* Push working repository on workspace to newly created repo in GitHub.
* Pull repo from GitHub to another working Linux machine.
* Setup working Linux machine so it can provide home user web page.
  * sudo apt install apache2
  * sudo service apache2 restart
  * Test connection using browser to point to localhost or IP address.
    * Get IP address using ifconfig command.
  * sudo apt install mysql-server php-mysql -y
    * Note root's password carefully.
  * sudo apt install php libapache2-mod-php php-mcrypt -y
  * sudo apt install php-sqlite3 -y
  * Enable per home user directory: sudo a2enmod userdir; sudo service
    apache2 restart.
