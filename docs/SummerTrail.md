# SummerTrail

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** | Unique identifier for the trail. | 
**name** | **String** | Display name of the trail. | 
**slug** | **String** | URL-friendly name of the trail. | 
**number** | **Int** | Optional trail number. | [optional] 
**trailType** | [SummerTrailType] | Type of trail activity (e.g. hiking, mountain_biking). Can have multiple. | 
**difficulty** | [**SummerTrailDifficulty**](SummerTrailDifficulty.md) |  | [optional] 
**status** | [**SummerTrailStatus**](SummerTrailStatus.md) | Current operational status (open, closed, or unknown). | 
**conditionNotes** | **String** | Notes about current conditions on this trail. | 
**areaUuid** | **String** | UUID of the area this trail belongs to, if assigned. | [optional] 
**areaName** | **String** | Name of the area this trail belongs to, if assigned. | [optional] 
**areaDisplayOrder** | **Int** | Display order of the area this trail belongs to, if assigned, for sorting purposes. | [optional] 
**updatedAt** | **Date** | When this trail&#39;s information was last updated. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


