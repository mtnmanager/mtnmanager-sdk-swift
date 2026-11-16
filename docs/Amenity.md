# Amenity

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **String** | Description of the amenity. | 
**uuid** | **String** | Unique identifier for the amenity. | 
**name** | **String** | Display name of the amenity. | 
**slug** | **String** | URL-friendly name of the amenity. | 
**category** | [**AmenityCategory**](AmenityCategory.md) | Category classification (e.g. restaurant, lodge, ski_school). | 
**website** | **String** | Website URL for the amenity, if available. | 
**status** | [**AmenityStatus**](AmenityStatus.md) | Current operational status (open, closed, on_hold, or unknown). Always  &#x60;unknown&#x60; when the resort doesn&#39;t track amenity status, or this amenity  doesn&#39;t report one. | 
**hasOperatingHours** | **Bool** | Whether this amenity reports operating hours. When false, clients should  not expect &#x60;opens_at&#x60;, &#x60;closes_at&#x60;, or &#x60;schedules&#x60; to ever be populated. | 
**hasStatus** | **Bool** | Whether this amenity reports a status. When false, &#x60;status&#x60; is always  &#x60;unknown&#x60;. (It is also &#x60;unknown&#x60; while the resort doesn&#39;t track amenity  status at all.) | 
**opensAt** | **String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional] 
**closesAt** | **String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional] 
**schedules** | [Schedule] | Recurring operating schedules for this amenity (e.g. \&quot;Saturday &amp; Sunday,  9:00 a.m. to 4:00 p.m.\&quot;), with both human-readable and structured fields. | 
**images** | [EntityImage] | Images attached to this amenity, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


