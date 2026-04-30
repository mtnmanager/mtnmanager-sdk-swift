# TrailMapSummary

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** |  | 
**name** | **String** |  | 
**season** | [**SeasonType**](SeasonType.md) |  | 
**displayOrder** | **Int64** |  | 
**hostedUrl** | **String** |  | 
**geoBounds** | [**GeoBounds**](GeoBounds.md) | Lat/lng bounding box of this map&#39;s georeferenced area, plus the  centroid of its control points (used for tie-breaking when multiple  maps cover the same point). Omitted when the map has no georeferencing. | [optional] 
**entityUuids** | **[String]** | Deduplicated UUIDs of every entity (lift, run, terrain park,  summer trail, amenity, parking lot) referenced by this map&#39;s elements. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


