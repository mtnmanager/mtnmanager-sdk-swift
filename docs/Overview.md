# Overview

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | [**ResortStatus**](ResortStatus.md) | Current operational status of the resort (open or closed).  This is calculated based on the current time relative to today&#39;s scheduled hours. | 
**opensAt** | **String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**closesAt** | **String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**season** | [**SeasonType**](SeasonType.md) | Current operating season (winter, summer, or closed/off-season). | 
**previousSeason** | [**SeasonPeriod**](SeasonPeriod.md) | The last season to end before today, from the resort&#39;s operating  hours of the past year. &#x60;null&#x60; if there was none. While &#x60;season&#x60; is  &#x60;closed&#x60;, this and &#x60;next_season&#x60; tell an off-season that just ended a  winter from one leading up to a summer. | [optional] 
**nextSeason** | [**SeasonPeriod**](SeasonPeriod.md) | The next season to start after today, from the resort&#39;s scheduled  operating hours. &#x60;null&#x60; if none is scheduled yet. | [optional] 
**news** | [OverviewNews] | Written news — daily update, announcements, etc. The resort&#39;s primary  news comes first, followed by any others it publishes, in the order they  were added. News with nothing written is still listed, with empty  &#x60;raw&#x60; and &#x60;html&#x60;. | 
**runs** | [**OverviewRuns**](OverviewRuns.md) | Run statistics: counts, acres, and last-updated timestamp. | 
**lifts** | [**OverviewLifts**](OverviewLifts.md) | Lift statistics: counts and last-updated timestamp. | 
**summerTrails** | [**OverviewSummerTrails**](OverviewSummerTrails.md) | Summer trail statistics: counts and last-updated timestamp. | 
**terrainParks** | [**OverviewTerrainParks**](OverviewTerrainParks.md) | Terrain park statistics: counts and last-updated timestamp. | 
**powderAlerts** | [**PowderAlerts**](PowderAlerts.md) | Guest powder alerts the resort offers, by channel. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


