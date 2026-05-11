# Amenity

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **String** | Description of the amenity. | 
**uuid** | **String** | Unique identifier for the amenity. | 
**name** | **String** | Display name of the amenity. | 
**category** | [**AmenityCategory**](AmenityCategory.md) | Category classification (e.g. restaurant, lodge, ski_school). | 
**website** | **String** | Website URL for the amenity, if available. | 
**opensAt** | **String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional] 
**closesAt** | **String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional] 
**schedules** | [Schedule] | Recurring operating schedules for this amenity (e.g. \&quot;Saturday &amp; Sunday,  9:00 a.m. to 4:00 p.m.\&quot;), with both human-readable and structured fields. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


