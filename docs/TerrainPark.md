# TerrainPark

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** | Unique identifier for the terrain park. | 
**name** | **String** | Display name of the terrain park. | 
**slug** | **String** | URL-friendly name of the terrain park. | 
**number** | **Int** | Optional terrain park number. | [optional] 
**status** | [**TerrainParkStatus**](TerrainParkStatus.md) | Current operational status (open, closed, or unknown). | 
**conditionNotes** | **String** | Notes about current conditions in this terrain park. | 
**areaUuid** | **String** | UUID of the area this terrain park belongs to, if assigned. | [optional] 
**areaName** | **String** | Name of the area this terrain park belongs to, if assigned. | [optional] 
**areaDisplayOrder** | **Int** | Display order of the area this terrain park belongs to, if assigned, for sorting purposes. | [optional] 
**features** | [TerrainParkFeature] | Features within this terrain park (jumps, boxes, rails, etc.). | 
**updatedAt** | **Date** | When this terrain park or any of its features was last updated. | 
**images** | [EntityImage] | Images attached to this terrain park, ordered for display. Each includes  a ThumbHash for rendering a blurred placeholder while the image loads. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


