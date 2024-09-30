# Dependencies Folder
Here we store dependencies the project requires to run. We do this as a deep copy so that each game project can manage its own specific versions of each dependency.

## Gathering your Dependencies

### System Core
From Heathen Engineering this is an open source asset pulled off GitHub from here
https://github.com/heathen-engineering/SystemCore

As you can see we have only copied in the part the game project needs … that is the com.heathen.systemcore folder.

### Steamworks.NET
From Riley Labrecque, in this case we know Steamworks SDK and by extension Steamworks.NET has an issue with its latest version so we want to get specifically the version they checked in with the Steamworks SDK 1.59 setup. To find that we navigate to the folder we want e.g. `com.rlabrecque.steamworks.net` … as seen here https://github.com/rlabrecque/Steamworks.NET/tree/master/com.rlabrecque.steamworks.net … next we click the history button in the upper right corner of the folder display and scroll down to the `Update to Steamworks SDK 1.59` clicking the `View code at this point` button which takes us here https://github.com/rlabrecque/Steamworks.NET/tree/078ed3c7c9b767a42be555b75ea5fb014c067132/com.rlabrecque.steamworks.net and finally we download the code at this point we can do that by clicking the Blue Steamworks.NET to navigate to the root of this point in the change set … that will take us here https://github.com/rlabrecque/Steamworks.NET/tree/078ed3c7c9b767a42be555b75ea5fb014c067132 and then we can use the big green button that says `<> Code` to download it as a zip … this is the URL to that zip if you need it https://github.com/rlabrecque/Steamworks.NET/archive/078ed3c7c9b767a42be555b75ea5fb014c067132.zip

### Toolkit for Steamworks Foundation
Just to add to the example we have also grabbed Steamworks Foundation from Heathen Engineering. You can find this on GitHub from here https://github.com/heathen-engineering/Toolkit-for-Steamworks-Foundation

## Installing them
To install them on Unity we use Unity Package Manager, select the `+` button and use the Add from Disk option. You will then browse to the Dependencies folder and select the package.json located in each of the folders. You will want to do this in dependency order … in this case that is 

1. System Core
2. Steamworks.NET
3. Toolkit for Steamworks SDK Foundation