# Overview

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | [**ResortStatus**](ResortStatus.md) | Current operational status of the resort (open or closed).  This is calculated based on the current time relative to today&#39;s scheduled hours. | 
**opensAt** | **String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**closesAt** | **String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**season** | [**SeasonType**](SeasonType.md) | Current operating season (winter, summer, or closed/off-season). | 
**news** | [**OverviewNews**](OverviewNews.md) | Written news — daily update, announcements, etc. | 
**runs** | [**OverviewRuns**](OverviewRuns.md) | Run statistics: counts, acres, and last-updated timestamp. | 
**lifts** | [**OverviewLifts**](OverviewLifts.md) | Lift statistics: counts and last-updated timestamp. | 
**summerTrails** | [**OverviewSummerTrails**](OverviewSummerTrails.md) | Summer trail statistics: counts and last-updated timestamp. | 
**terrainParks** | [**OverviewTerrainParks**](OverviewTerrainParks.md) | Terrain park statistics: counts and last-updated timestamp. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


