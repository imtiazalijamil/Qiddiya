# MDM - With Imaging
## Enroll Device After Image

Personal Notes:
- To enroll device after MDT, create basic account in UEM with staging enabled (Single User).
- Create SmartGroup (Prov_Prof)
- Create VPN Profile
- Assign apps, VPN Profile
- Add WS-One Application to MDT to deploy.
>msiexec.exe /i AirwatchAgent.msi /quiet ENROLL=Y SERVER=https://*****.awmdm.com LGNAME=MIAJ USERNAME=test PASSWORD=test

- Staging details can be found at Settings --> Devices & Users --> Window Desktop --> Staging & Provisioning
- 
✨  change staging account random passwod, better option to create  new local account✨
