## MissionPlanner of ArduPilot

#### Following https://github.com/ArduPilot/MissionPlanner

### Setup environment

1. MS Windows 10 Enterprise
2. MS Visual Studio Enterprise 2017 v15.2
3. Python 2.7 https://www.python.org/downloads/
4. DirectX for Managed Code: https://www.microsoft.com/en-us/download/confirmation.aspx?id=10084
5. Download and install lates version of MissionPlanner from http://firmware.ardupilot.org/Tools/MissionPlanner/

### Make MissionPlanner to be built

1. Open solution in VS
2. Set build target: Debug/x86/MissionPlanner
3. Change TargetFrameworks from 'netstandard2.0' to 'net461' for the following projects:
   - ExtLibs/Comms/MissionPlanner.Comms.csproj
   - ExtLibs/GMap.NET.Core/GMap.NET.Core.csproj
   - ExtLibs/GeoUtility/GeoUtility.csproj b/ExtLibs/GeoUtility/GeoUtility.csproj
   - ExtLibs/KMLib/KMLib.csproj
   - ExtLibs/LibVLC.NET/LibVLC.NET.csproj
   - ExtLibs/ManagedNativeWifi.Simple/ManagedNativeWifi.Simple.csproj
   - ExtLibs/Mavlink/MAVLink.csproj
   - ExtLibs/MetaDataExtractorCSharp240d/MetaDataExtractor.csproj
   - ExtLibs/Comms/MissionPlanner.Comms.csproj
   - ExtLibs/SharpKml/SharpKml.csproj
   - ExtLibs/px4uploader/px4uploader.csproj
   - ExtLibs/Arduino/Arduino.csproj
  