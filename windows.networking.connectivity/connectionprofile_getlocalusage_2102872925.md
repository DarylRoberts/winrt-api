---
-api-id: M:Windows.Networking.Connectivity.ConnectionProfile.GetLocalUsage(Windows.Foundation.DateTime,Windows.Foundation.DateTime)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Networking.Connectivity.DataUsage GetLocalUsage(Windows.Foundation.DateTime StartTime, Windows.Foundation.DateTime EndTime)
-->

# Windows.Networking.Connectivity.ConnectionProfile.GetLocalUsage

## -description
> [!NOTE]
> [GetLocalUsage](connectionprofile_getlocalusage_2102872925.md) may be altered or unavailable for releases after Windows 8.1. Instead, use [GetNetworkUsageAsync](connectionprofile_getnetworkusageasync_665790436.md)

Gets the estimated data usage for a connection during over a specific period of time.

## -parameters
### -param StartTime
The start date/time for the usage data request.

### -param EndTime
The end date/time for the usage data request.

## -returns
The requested local data usage information.

## -remarks
For an example of how this method is used, see [How to retrieve connection usage data for a specific period of time](http://msdn.microsoft.com/library/c9409429-7712-42e9-a2af-3940a7375c21).

## -examples

## -see-also
[GetLocalUsage(DateTime, DateTime, RoamingStates)](connectionprofile_getlocalusage_45954997.md)