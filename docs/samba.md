# SAMBA (Network drive) 

SAMBA allows one to connect to (or “mount”) their home and project directories on their local computer.   

This method of accessing your RCC home and project space is only available from within the UChicago campus network. From off-campus, you will need to first **connect through the UChicago VPN.**

**Connecting from Windows**   


![Map Network Drive](img/data_management/map_network_drive.png)

On a Windows computer, select “Map Network Drive” and enter one of the following UNC paths depending on which location on Midway you wish to connect to:  
=== "Midway2"
    === "Home"
        ```
        \\midwaysmb.rcc.uchicago.edu\homes
        ```
    === "Project2"
        ```
        \\midwaysmb.rcc.uchicago.edu\project2
        ```
    === "Scratch"
        ```
        \\midwaysmb.rcc.uchicago.edu\midway2-scratch
        ```
===+ "Midway3"
    === "Home"
        ```
        \\midway3smb1.rcc.uchicago.edu\homes
        ``` 
    === "Project"
        ```
        \\midway3smb1.rcc.uchicago.edu\project
        ```
    === "Scratch"
        ```
        \\midway3smb1.rcc.uchicago.edu\midway3-scratch
        ```

Enter `ADLOCAL\CNetID` for the username and enter your CNet password.  


**Connecting from macOS**   

![Connect to Server](img/data_management/connect_to_server.jpg)  

On a macOS X computer, select “Connect to Server” (from "Go" dropdown in Finder) and enter one of the following URLs depending on which location on Midway you wish to connect to:  

=== "Midway2"
    === "Home"
        ```
        smb://midwaysmb.rcc.uchicago.edu/homes
        ```
    === "Project2"
        ```
        smb://midwaysmb.rcc.uchicago.edu/project2
        ```
    === "Scratch"
        ```
        smb://midwaysmb.rcc.uchicago.edu/midway2-scratch
        ```
===+ "Midway3"
    === "Home"
        ```
        smb://midway3smb1.rcc.uchicago.edu/homes
        ``` 
    === "Project"
        ```
        smb://midway3smb1.rcc.uchicago.edu/project
        ```
    === "Scratch"
        ```
        smb://midway3smb1.rcc.uchicago.edu/midway3-scratch
        ```
Enter `ADLOCAL\CNetID` for the username and enter your CNet password.  

!!! warning
    While transferring large files and/or datasets over SAMBA may be appealing, it slows file transfer for all other users. Please use Globus for large transfers.