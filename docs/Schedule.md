# Schedule

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**daysString** | **String** | Human-readable description of which days this schedule applies to.  Examples: \&quot;Daily\&quot;, \&quot;Saturday &amp; Sunday\&quot;, \&quot;Monday, Wednesday, and Friday\&quot; | 
**daysOfWeek** | [DayOfWeek] | Array of days of the week this schedule applies to.  For programmatic use. | 
**timeString** | **String** | Human-readable time range.  Example: \&quot;9:00 a.m. to 4:00 p.m.\&quot; | 
**opensAt** | **String** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. | 
**closesAt** | **String** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. | 
**inEffect** | **Bool** | Whether this schedule is currently in effect.  &#x60;false&#x60; for upcoming schedules that haven&#39;t started yet. | 
**effectiveString** | **String** | Human-readable date range when this schedule is effective.  Example: \&quot;November 1, 2024 to April 15, 2025\&quot; | 
**effectiveFrom** | **Date** | Start date of the effective period (YYYY-MM-DD). | 
**effectiveTo** | **Date** | End date of the effective period (YYYY-MM-DD). | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


