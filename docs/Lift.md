# Lift

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** | Unique identifier for the lift. | 
**name** | **String** | Display name of the lift. | 
**slug** | **String** | URL-friendly name of the lift. | 
**number** | **Int** | Optional lift number. | [optional] 
**liftType** | [**LiftType**](LiftType.md) | Type of lift (e.g. gondola, quad). | 
**highSpeed** | **Bool** | Whether this is a high-speed/detachable lift. | 
**bubble** | **Bool** | Whether the lift has a bubble/cover for weather protection. | 
**heated** | **Bool** | Whether the lift has heated seats. | 
**travelTime** | **Double** | Estimated travel time in minutes. | [optional] 
**lengthFt** | **Int** | Length of the lift in feet. | [optional] 
**lengthM** | **Int** | Length of the lift in meters. | [optional] 
**verticalRiseFt** | **Int** | Vertical rise of the lift in feet. | [optional] 
**verticalRiseM** | **Int** | Vertical rise of the lift in meters. | [optional] 
**status** | [**LiftStatus**](LiftStatus.md) | Current operational status (open, closed, on_hold, or unknown). | 
**waitTimeMinutes** | **Int64** | Current estimated wait time in minutes, if available. | [optional] 
**opensAt** | **String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if the lift has no scheduled hours for today. | [optional] 
**closesAt** | **String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if the lift has no scheduled hours for today. | [optional] 
**areaUuid** | **String** | UUID of the area this lift belongs to, if assigned. | [optional] 
**areaName** | **String** | Name of the area this lift belongs to, if assigned. | [optional] 
**areaDisplayOrder** | **Int** | Display order of the area this lift belongs to, if assigned, for sorting purposes. | [optional] 
**updatedAt** | **Date** | When this lift&#39;s information was last updated. | 
**images** | [EntityImage] | Images attached to this lift, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


