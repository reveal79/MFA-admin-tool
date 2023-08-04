# MFA-admin-tool
This is a way to manage MFA for single users with Azure p1 licenses
MFA ADMIN TOOL

This is only configured for a single tenant, so if you manage multiple tenants you'd have to close and open and login with admin credentials based on that tenant
Requirements:
Modules: azure ad
This script will install the required modules if they're not.

How to use: 
Right-click the file and run with Powershell 
Or load the script in your favorite Powershell editor, ie powershell ise or visual studio code

Requirements: must have an email address

Check if MFA is enabled, and if so what type is configured

Enable MFA - Turns on MFA for a user

Enforce MFA - Enforces MFA for user

Disable MFA - Disables MFA for a user

Reset MFA - Resets MFA methods and requires to re-register for MFA

Revoke MFA - Revokes all tokens and sessions and requires MFA to be configured again

Image of the script for reference
![image](https://github.com/reveal79/MFA-admin-tool/assets/20243681/1ad46e83-f804-465e-8928-b6f0b737607d)
