# TerrainParkFeature

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** | Unique identifier for the feature. | 
**name** | **String** | Display name of the feature. | 
**slug** | **String** | URL-friendly name of the run. | 
**number** | **Int** | Optional feature number. | [optional] 
**featureType** | [**FeatureType**](FeatureType.md) | Type of feature (jump, box, rail, other). | 
**size** | [**FeatureSize**](FeatureSize.md) | Optional size rating of the feature (S, M, L, XL). | [optional] 
**status** | [**TerrainParkFeatureStatus**](TerrainParkFeatureStatus.md) | Current operational status (open, closed, or unknown).  &#x60;unknown&#x60; unless the terrain park feature status is enabled. | 
**images** | [EntityImage] | Images attached to this feature, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


