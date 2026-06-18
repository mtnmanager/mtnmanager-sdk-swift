# Weather

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**areaUuid** | **String** | The area this weather belongs to, or omitted for resort-wide weather. | [optional] 
**areaName** | **String** | The area&#39;s name, or omitted for resort-wide weather. | [optional] 
**areaDisplayOrder** | **Int** | The area&#39;s display order, or omitted for resort-wide weather. | [optional] 
**current** | [**CurrentWeather**](CurrentWeather.md) | Current weather conditions | 
**hourlyForecast** | [HourlyForecast] | Hourly forecast for next 24 hours (including current hour) | 
**dailyForecast** | [DailyForecast] | Daily forecast for next 7 days (including today) | 
**attribution** | **String** | Data source attribution | 
**updatedAt** | **Date** | When this data was last updated | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


