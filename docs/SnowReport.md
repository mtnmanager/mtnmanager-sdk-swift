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
**surfaceCondition** | [**SurfaceCondition**](SurfaceCondition.md) | Primary surface condition using industry standard codes.  Not included if the snow surface condition feature is disabled.   - BS (Bare Spots)  - CO (Corn Snow)  - FG (Frozen Granular)  - HP (Hard Pack)  - IP (Ice Patches)  - IS (Icy Surface)  - LG (Loose Granular)  - MG (Machine Groomed)  - P (Powder)  - PP (Packed Powder)  - SC (Spring Conditions)  - TC (Thin Cover)  - V (Variable)  - WG (Wet Granular)  - WP (Wet Powder) | [optional] 
**secondarySurfaceCondition** | [**SurfaceCondition**](SurfaceCondition.md) | Secondary surface condition using industry standard codes.  Not included if the secondary snow surface condition feature is disabled.   - BS (Bare Spots)  - CO (Corn Snow)  - FG (Frozen Granular)  - HP (Hard Pack)  - IP (Ice Patches)  - IS (Icy Surface)  - LG (Loose Granular)  - MG (Machine Groomed)  - P (Powder)  - PP (Packed Powder)  - SC (Spring Conditions)  - TC (Thin Cover)  - V (Variable)  - WG (Wet Granular)  - WP (Wet Powder) | [optional] 
**conditionNotes** | **String** | Additional notes about current snow conditions, e.g. groomer&#39;s notes | 
**snowfallCm** | [**SnowMetrics**](SnowMetrics.md) | Snowfall accumulation metrics in centimeters. | 
**snowfallIn** | [**SnowMetrics**](SnowMetrics.md) | Snowfall accumulation metrics in inches. | 
**reportedAt** | **Date** | When this snow report was last updated. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


