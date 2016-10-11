oracle-java-jdk
=========

Ansible role for downloading Oracle Java Development Kit and Java Cryptography Extensions binary archives to the control server, then extracting them to the target host.

Role Variables
--------------
Set the ```java_version``` parameter to install other versions of Node.js

        java_version: 8u102-b14
        
Available versions:

    8u102-b14
    8u101-b13
    7u80-b15
    7u79-b15
    

Set the ```prefix``` parameter to install somewhere other than ```opt/java```

        prefix: "opt/java"
        
License
-------

MIT

Testing
-------
Run the following command:

        ansible-playbook oracle-java-jdk/tests/test.yml

