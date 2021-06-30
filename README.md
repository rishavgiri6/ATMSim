## ATMSim
A J2EE based modular ATM simulator with the following functionalities:

#Proposed System
            The proposed system aims to solve all this by constant updating of bank records. The Java based construction of the system will enable transactions at any bank or ATM to be registered within a matter of seconds. Security of these details is also a top priority in this system. This central hub will be accessed by an ATM for secure customer transactions.

#ATM Simulation System Modules
Advertiser: The Bank can use free screen time to advertise their products. This will be possible only when no user is using the ATM for a transaction.

Authenticator: This is the module that will first present itself to a user. The user will have to present their ATM card and enter their PIN which will be checked with the secure database at the Bank Central Server. This module will also enable users to change their PIN.

Maintenance: This module will maintain a log of all updates and maintenance of the ATM. It will notify the central server of impending maintenance. In the event of delayed maintenance it will put the ATM in reduced functionality lock down mode.

Transaction: This is the module that handles all user interaction with the Bank Central Server after successful authentication. It will allow for bank account balance checking and for withdrawals made. It will log any changes in account details in the Bank Central Server.

Admin: The admin will operate from the Bank Central Server. The admin module will ensure that only updated databases are used by the transaction module. The maintenance of the machine can be remotely postponed by an authorised user through the admin module.

#Software Requirements:

Apache Tomcat Web Server
Oracle

#Tech stack used:
Java,J2EE
