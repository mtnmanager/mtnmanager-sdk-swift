# CalendarDay

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**date** | **Date** | Calendar date (YYYY-MM-DD). | 
**dayOfWeek** | [**DayOfWeek**](DayOfWeek.md) | Day of the week. | 
**isOpen** | **Bool** | Whether the resort is open on this day. | 
**opensAt** | **String** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if closed on this day. | [optional] 
**closesAt** | **String** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if closed on this day. | [optional] 
**closureReason** | [**ClosureReason**](ClosureReason.md) |  | [optional] 
**specialEvent** | **String** | Special event for this day. | [optional] 
**amenities** | [AmenityCalendarEntry] | Per-amenity hours for this day. Only included when amenity hours are configured. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


