### Modified ReFrameWork Template ###
This framework is based on UiPath's REFramework template, which can be chosen on starting UiPath Studio as a standard template

### Change log ###
- Added 'Terminate' command if unhandled system error in 'End Process' state
- Added retry loop in InitAllApplications.xaml
- Deleted GetTransactionData.xaml, CloseAllApplications.xaml and GetAppCredentials.xaml from the 'Framework' folder
- Added a loop in KillAllProcesses.xaml to provide multiple applications to kill
- Deleted 'Tests' folder
- Removed superflous Transaction Data (Field 1, Field 2, Tr Data Datatable etc.)  

### Standard REFramework documentation is included in the Documentation folder ###

[ReFrameWork Documentation](https://github.com/UiPath/ReFrameWork/blob/master/Documentation/REFramework%20documentation.pdf)