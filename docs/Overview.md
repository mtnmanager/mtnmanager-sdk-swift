# Overview

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | [**ResortStatus**](ResortStatus.md) | Current operational status of the resort (open or closed).  This is calculated based on the current time relative to today&#39;s scheduled hours. | 
**opensAt** | **String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**closesAt** | **String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**season** | [**SeasonType**](SeasonType.md) | Current operating season (winter, summer, or closed/off-season). | 
**news** | **String** | Written news — daily update, announcements, etc. (Markdown source). | 
**newsHtml** | **String** | Written news — daily update, announcements, etc. (rendered as HTML from Markdown). | 
**newsUpdatedAt** | **Date** | When the written news was last updated. | 
**openRuns** | **Int64** | Number of runs currently open.  Not included if the runs status feature is disabled. | [optional] 
**groomedRuns** | **Int64** | Number of runs groomed within the last 24 hours.  Not included if the runs grooming feature is disabled. | [optional] 
**totalRuns** | **Int64** | Total number of runs at the resort. | 
**openAcres** | **Int64** | Total acres of open runs.  Not included if acres are not tracked or run status feature is disabled. | [optional] 
**totalAcres** | **Int64** | Total acres of all runs.  Not included if acres are not tracked. | [optional] 
**runsUpdatedAt** | **Date** | When the most recent update to run status was made. | 
**openLifts** | **Int64** | Number of lifts currently open.  Not included if the lifts status feature is disabled. | [optional] 
**totalLifts** | **Int64** | Total number of lifts at the resort. | 
**liftsUpdatedAt** | **Date** | When the most recent update to lift status was made. | 
**openSummerTrails** | **Int64** | Number of summer trails currently open.  Not included if the summer trails status feature is disabled. | [optional] 
**totalSummerTrails** | **Int64** | Total number of summer trails at the resort. | 
**summerTrailsUpdatedAt** | **Date** | When the most recent update to summer trail status was made. | 
**openTerrainParks** | **Int64** | Number of terrain parks currently open.  Not included if the terrain parks status feature is disabled. | [optional] 
**totalTerrainParks** | **Int64** | Total number of terrain parks at the resort. | 
**terrainParksUpdatedAt** | **Date** | When the most recent update to terrain park status was made. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


