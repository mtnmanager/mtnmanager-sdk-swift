# FullReport

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**resort** | [**ResortInfo**](ResortInfo.md) |  | 
**status** | [**Overview**](Overview.md) |  | 
**snow** | [SnowReport] | Provides current snow conditions including base depth, surface conditions,  and snowfall totals in both metric and imperial units.   May contain multiple, representing different reporting areas. | 
**lifts** | [Lift] | List of all lifts at the resort with their current operational status,  type, and optional wait time information. | 
**runs** | [Run] | List of all runs at the resort with their current status,  grooming information, and difficulty rating. | 
**terrainParks** | [TerrainPark] | List of all terrain parks at the resort with their current status,  condition notes, and list of features (jumps, boxes, rails, etc.) within them. | 
**parkingLots** | [ParkingLot] | List of all parking lots at the resort with their current status and amenities. | 
**summerTrails** | [SummerTrail] | List of all summer trails at the resort with their current status,  type (e.g. hiking, mountain biking), and optional difficulty rating. | 
**hours** | [**OperatingHours**](OperatingHours.md) |  | 
**weather** | [Weather] | Weather entries: the resort-wide entry first (current + forecast), then  any per-area current-conditions entries. Empty when weather is disabled  or unavailable. | [optional] 
**webcams** | [Webcam] | Enabled webcams with the URLs of their current and last-daylight frames  plus thumbnails. Empty when the resort does not have webcams. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


