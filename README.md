## Powershell commands:
- Set-ExecutionPolicy Unrestricted -Force
- Import-Module C:\scripts\GenerateSSCertificate.ps1
- New-SelfSignedCertificateEx –Subject "CN=KaribuHotel" –IsCA $true –Exportable –StoreLocation LocalMachine

## Path to client config:                       
- C:\Users\Administrator\AppData\Roaming\Microsoft\Microsoft Dynamics NAV\100