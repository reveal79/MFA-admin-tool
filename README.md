# MFA-admin-tool
This is a way to manage MFA for single users with azure p1 licenses
MFA ADMIN TOOL

This is only configured for single tenant, so if you manage multiple tenants you'd have to close and open and login with admin credentials based on that tenant
Requirements:
Modules: azuread
This script will install the required modules if they're not.

How to use: 
Right click file and run with powershell 
Or load the script in your favorite powershell editor, ie powershell ise or visual studio code

Requirements: must have email address

Check if MFA is enabled, if so what type is configured

Enable MFA - Turns on MFA for a user

Disable MFA - Disables MFA for a user

Reset MFA - Resets MFA methods and requires to re-register for MFA

Revoke MFA - Revokes all tokens and sessions and requires MFA to be configured again

