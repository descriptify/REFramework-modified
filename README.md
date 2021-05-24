### Modified ReFrameWork Template ###
This framework is based on UiPath's REFramework template (https://github.com/UiPath/ReFrameWork/)

### Change log ###
- Terminated process if unhandled system error in 'End Process' state
- Limited package dependencies to 4 packages (Excel, Mail, System, UiAutomation)
- Added retry loop in InitAllApplications.xaml
- Deleted GetTransactionData.xaml, CloseAllApplications.xaml and GetAppCredentials.xaml from the 'Framework' folder
- Added a loop in KillAllProcesses.xaml to provide multiple applications to kill
- Included option for logging warnings in queue items (as input to SetTransactionStatus.xaml)
- Deleted 'Tests' folder
 

### Standard REFramework documentation is included in the Documentation folder ###

[ReFrameWork Documentation](https://github.com/UiPath/ReFrameWork/blob/master/Documentation/REFramework%20documentation.pdf)