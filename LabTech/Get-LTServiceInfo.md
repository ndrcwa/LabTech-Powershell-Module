# Get-LTServiceInfo
## SYNOPSIS
This function will pull all of the registry data into an object.
## SYNTAX
```powershell
Get-LTServiceInfo [-WhatIf] [-Confirm] [<CommonParameters>]
```
## PARAMETERS
### -WhatIf &lt;SwitchParameter&gt;

```
Required                    false
Position                    named
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Confirm &lt;SwitchParameter&gt;

```
Required                    false
Position                    named
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## NOTES
Version:        1.4

Author:         Chris Taylor

Website:        labtechconsulting.com

Creation Date:  3/14/2016

Purpose/Change: Initial script development



Update Date: 6/1/2017

Purpose/Change: Updates for better overall compatibility, including better support for PowerShell V2



Update Date: 8/24/2017

Purpose/Change: Update to use Clear-Variable.



Update Date: 3/12/2018

Purpose/Change: Support for ShouldProcess to enable -Confirm and -WhatIf.



Update Date: 8/28/2018

Purpose/Change: Remove '~' from server addresses. 
