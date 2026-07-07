# Webcam

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** |  | 
**name** | **String** |  | 
**areaUuid** | **String** |  | [optional] 
**areaName** | **String** |  | [optional] 
**areaDisplayOrder** | **Int** |  | [optional] 
**latestImageUrl** | **String** | URL of the newest frame (refreshes within ~60s via the edge cache). | 
**latestDaylightImageUrl** | **String** | URL of the last daylight frame. | 
**latestThumbUrl** | **String** |  | 
**latestDaylightThumbUrl** | **String** |  | 
**latestThumbhash** | **String** | ThumbHash of the &#x60;latest&#x60; frame (standard base64) — a compact blur  placeholder to render while the image loads. Empty string until the first  frame (or on cameras predating the feature). | 
**latestDaylightThumbhash** | **String** | ThumbHash of the &#x60;latest-daylight&#x60; frame (standard base64). Empty string  until the first daylight frame. | 
**hasHistory** | **Bool** | Whether this camera archives frames — i.e. whether its history endpoint  returns anything. When &#x60;false&#x60;, don&#39;t call the history API for it. | 
**elevationFt** | **Int** | Camera elevation in both units; omitted when unset. | [optional] 
**elevationM** | **Int** |  | [optional] 
**lastFrameAt** | **String** | Time of the most recently published frame; omitted until the first frame. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


