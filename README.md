# Resources
Resource files

## Files descriptions
[MSS-legacy.admx](MSS-legacy.admx) and [MSS-legacy.adml](MSS-legacy.adml): These are the MSS (Legacy) GPOs from MS. Since MS deleted most of their link to them but still needed for several compliance like STIG, we made them available here. Also can be downloaded from [Internet Archive](https://Archive.org) at [This Link](https://web.archive.org/web/20200723045549/https://msdnshared.blob.core.windows.net/media/2016/10/MSS-legacy.zip)
MSS-legacy.admx and MSS-legacy.adml must be copied to the \Windows\PolicyDefinitions and \Windows\PolicyDefinitions\en-US directories respectivel. If they are intended for be deployed on a Domain Controller, the location would be %SystemDrive%\Windows\SYSVOL\domain\Policies\PolicyDefinitions and %SystemDrive%\Windows\SYSVOL\domain\Policies\PolicyDefinitions\en-US directories respectivel

[SecGuide.admx](SecGuide.admx) and [SecGuide.adml](SecGuide.adml): These are the MS Security Guide GPOs from MS, needed for compliance. They must be copied to the \Windows\PolicyDefinitions and \Windows\PolicyDefinitions\en-US directories respectivel. If they are intended for be deployed on a Domain Controller, the location would be %SystemDrive%\Windows\SYSVOL\domain\Policies\PolicyDefinitions and %SystemDrive%\Windows\SYSVOL\domain\Policies\PolicyDefinitions\en-US directories respectivel
