# Run

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** | Unique identifier for the run. | 
**name** | **String** | Display name of the run. | 
**slug** | **String** | URL-friendly name of the run. | 
**number** | **Int** | Optional run number. | [optional] 
**difficulty** | [**RunDifficulty**](RunDifficulty.md) | Difficulty rating of the run. | 
**status** | [**RunStatus**](RunStatus.md) | Current operational status (open, closed, or unknown). | 
**lastGroomed** | **Date** | When the run was last groomed.  &#x60;null&#x60; if not groomed this season (since the snow year began: Aug 1, or  Jan 1 in the southern hemisphere), or if the runs grooming feature is disabled. | [optional] 
**groomedToday** | **Bool** | Whether the run has been groomed since the resort last closed (or,  for a resort with no operating hours set, within the last 24 hours). | 
**snowSinceGroomedCm** | **Int** | New snow (cm) reported since &#x60;last_groomed&#x60; (\&quot;groomed with fresh\&quot;).  Absent unless the run was groomed within the last 24 hours and the  resort keeps a snow report. | [optional] 
**snowSinceGroomedIn** | **Int** | New snow (inches) reported since &#x60;last_groomed&#x60;; see  &#x60;snow_since_groomed_cm&#x60;. | [optional] 
**snowmaking** | **Bool** | Whether the run has snowmaking capabilities. | 
**nightSkiing** | **Bool** | Whether the run is available for night skiing. | 
**conditionNotes** | **String** | Notes about current conditions on this run. | 
**areaUuid** | **String** | UUID of the area this run belongs to, if assigned. | [optional] 
**areaName** | **String** | Name of the area this run belongs to, if assigned. | [optional] 
**areaDisplayOrder** | **Int** | Display order of the area this run belongs to, if assigned, for sorting purposes. | [optional] 
**updatedAt** | **Date** | When this run&#39;s information was last updated. | 
**images** | [EntityImage] | Images attached to this run, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


