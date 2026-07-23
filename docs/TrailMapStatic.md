# TrailMapStatic

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** |  | 
**name** | **String** |  | 
**slug** | **String** |  | 
**season** | [**SeasonType**](SeasonType.md) |  | 
**displayOrder** | **Int64** |  | 
**version** | **Int64** | Monotonically incremented whenever the map&#39;s static content (geometry,  artwork, element membership, or the metadata carried here) changes. This  body is byte-stable for a fixed &#x60;version&#x60;, and the &#x60;version&#x60; is part of  the request URL — so the resource is immutable per version. | 
**backgroundImageUrl** | **String** |  | 
**elements** | [TrailMapStaticElement] |  | 
**geoControlPoints** | [GeoControlPoint] |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


