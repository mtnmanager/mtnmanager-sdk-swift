# OverviewNews

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** | Stable identifier of this news feed. | 
**name** | **String** | The name the resort gave this news feed, for telling several apart.  May be &#x60;null&#x60; on the primary news feed. | [optional] 
**isPrimary** | **Bool** | Whether this is the resort&#39;s primary news feed. Exactly one news is. | 
**raw** | **String** | Markdown source. Images the resort uploaded point at their public URLs,  so any Markdown renderer can display them. | 
**html** | **String** | Rendered HTML (from Markdown) | 
**updatedAt** | **Date** | When the news was last updated. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


