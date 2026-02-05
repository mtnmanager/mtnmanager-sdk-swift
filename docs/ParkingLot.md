# ParkingLot

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **String** | Unique identifier for the parking lot. | 
**name** | **String** | Display name of the parking lot. | 
**slug** | **String** | URL-friendly name of the parking lot. | 
**status** | [**ParkingLotStatus**](ParkingLotStatus.md) | Current status (open, closed, or full). | 
**capacity** | **Int** | Maximum vehicle capacity, if set. | [optional] 
**shuttle** | **Bool** | Whether shuttle service is available from this lot. | 
**paid** | **Bool** | Whether parking is paid/requires payment. | 
**reservationRequired** | **Bool** | Whether a reservation is required to park here. | 
**updatedAt** | **Date** | When this parking lot&#39;s information was last updated. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


