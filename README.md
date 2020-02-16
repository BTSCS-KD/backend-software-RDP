# backend-software-RDP
Information on how to set up the rdp connection for kiosks

#Software Required

*Server 2008

*IIS 7 or higher

*Google Chrome (internet explorer still will work just might not display sites correctly)

*TS RemoteApp Manager 

*TS Gateway Manager

*TS Configuration

*TS Manager

*TS Licensing Manager

*Connected to a AD DS Server (Active Directory Domain Server) (100% REQUIRED)

#How to install the TS (Ternimal Server) Software.

First off once you have installed server 2008 to a vm or a server go into roles and privliges. Find Ternimal Services, Click the tick box. also while you are hear tick the Web Server (IIS) box.

Click Next and select all serverices for both TS and IIS and then complete the install.

After its finished installing reboot the system. log in with your AD DS Account and go into server manager by default this should automaticly open. Double click on Roles and it will open then Double click on Ternimal Services.
