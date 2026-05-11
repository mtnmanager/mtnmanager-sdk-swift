# TrailMap

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** |  | 
**name** | **String** |  | 
**slug** | **String** |  | 
**season** | [**SeasonType**](SeasonType.md) |  | 
**displayOrder** | **Int64** |  | 
**version** | **Int64** | Monotonically incremented on every update. Clients can compare this  against a cached value to decide whether to reload the trail map. | 
**backgroundImageUrl** | **String** |  | 
**resort** | [**ResortInfo**](ResortInfo.md) |  | 
**elements** | [TrailMapElement] |  | 
**geoControlPoints** | [GeoControlPoint] |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


