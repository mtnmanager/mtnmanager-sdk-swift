# SnowReport

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** | Unique identifier for this snow report. | 
**areaUuid** | **String** | UUID of the area this report covers, if area-specific.  &#x60;null&#x60; for resort-wide reports. | [optional] 
**areaName** | **String** | Name of the area this report covers, if area-specific. | [optional] 
**areaDisplayOrder** | **Int** | Display order of the area this report covers, if area-specific, for sorting purposes. | [optional] 
**baseDepthCm** | **Int** | Current base depth in centimeters.  Not included if the base depth feature is disabled. | [optional] 
**baseDepthIn** | **Int** | Current base depth in inches.  Not included if the base depth feature is disabled. | [optional] 
**surfaceCondition** | [**SurfaceCondition**](SurfaceCondition.md) |  | [optional] 
**secondarySurfaceCondition** | [**SurfaceCondition**](SurfaceCondition.md) |  | [optional] 
**conditionNotes** | **String** | Additional notes about current snow conditions, e.g. groomer&#39;s notes | 
**snowfallCm** | [**SnowMetrics**](SnowMetrics.md) | Snowfall accumulation metrics in centimeters. | 
**snowfallIn** | [**SnowMetrics**](SnowMetrics.md) | Snowfall accumulation metrics in inches. | 
**reportedAt** | **Date** | When this snow report was last updated. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


