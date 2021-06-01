phpipam is an open-source web IP address management application (IPAM). Its goal is to provide light, modern and useful IP address management. It is php-based application with MySQL database backend, using jQuery libraries, ajax and HTML5/CSS3 features.

--------------------------------------------

I am not the author of phpIPAM. This ansible playbook is for testing purposes. It installs phpIPAM with default DB settings based on the installation iinstructions found at https://phpipam.net/phpipam-installation-on-centos-7/

This is built on CentOS 8 for use on a localhost. The database, apache, etc. are all installed one host.

Once the playbook is ran, open a browser tab to the localhost IP and follow the prompts as described in step 3. at https://phpipam.net/phpipam-installation-on-centos-7/