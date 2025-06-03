# winCheatSheet

## Diagnostic:

``` Powershell
Get-CimInstance -ClassName Win32_BIOS
Get-Date
```

``` Powershell
# As admin:
(Get-BitLockerVolume -MountPoint C).KeyProtector
```


## Networking:

``` Powershell
(nslookup google.com) ; (nslookup flinders.edu.au)
```

## Device Setup (Marden Office)
``` Powershell
Set-TimeZone -Id 'Cen. Australia Standard Time'
```
