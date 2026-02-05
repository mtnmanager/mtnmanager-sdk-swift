# MtnManagerAPI

All URIs are relative to *https://your-resort.mtnmanager.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getFullReport**](MtnManagerAPI.md#getfullreport) | **GET** /api/v1/report | Get full report
[**getHours**](MtnManagerAPI.md#gethours) | **GET** /api/v1/report/hours | Get operating hours
[**getLifts**](MtnManagerAPI.md#getlifts) | **GET** /api/v1/report/lifts | Get lifts
[**getOverview**](MtnManagerAPI.md#getoverview) | **GET** /api/v1/report/overview | Get overview
[**getParkingLots**](MtnManagerAPI.md#getparkinglots) | **GET** /api/v1/report/parking-lots | Get parking lots
[**getRuns**](MtnManagerAPI.md#getruns) | **GET** /api/v1/report/runs | Get runs
[**getSnow**](MtnManagerAPI.md#getsnow) | **GET** /api/v1/report/snow | Get snow conditions
[**getSummerTrails**](MtnManagerAPI.md#getsummertrails) | **GET** /api/v1/report/summer-trails | Get summer trails
[**getTerrainParks**](MtnManagerAPI.md#getterrainparks) | **GET** /api/v1/report/terrain-parks | Get terrain parks
[**getWeather**](MtnManagerAPI.md#getweather) | **GET** /api/v1/report/weather | Get weather


# **getFullReport**
```swift
    open class func getFullReport(completion: @escaping (_ data: FullReport?, _ error: Error?) -> Void)
```

Get full report

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get full report
MtnManagerAPI.getFullReport() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**FullReport**](FullReport.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getHours**
```swift
    open class func getHours(completion: @escaping (_ data: OperatingHours?, _ error: Error?) -> Void)
```

Get operating hours

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get operating hours
MtnManagerAPI.getHours() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**OperatingHours**](OperatingHours.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getLifts**
```swift
    open class func getLifts(completion: @escaping (_ data: [Lift]?, _ error: Error?) -> Void)
```

Get lifts

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get lifts
MtnManagerAPI.getLifts() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[Lift]**](Lift.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getOverview**
```swift
    open class func getOverview(completion: @escaping (_ data: Overview?, _ error: Error?) -> Void)
```

Get overview

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get overview
MtnManagerAPI.getOverview() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**Overview**](Overview.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getParkingLots**
```swift
    open class func getParkingLots(completion: @escaping (_ data: [ParkingLot]?, _ error: Error?) -> Void)
```

Get parking lots

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get parking lots
MtnManagerAPI.getParkingLots() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[ParkingLot]**](ParkingLot.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRuns**
```swift
    open class func getRuns(completion: @escaping (_ data: [Run]?, _ error: Error?) -> Void)
```

Get runs

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get runs
MtnManagerAPI.getRuns() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[Run]**](Run.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSnow**
```swift
    open class func getSnow(completion: @escaping (_ data: [SnowReport]?, _ error: Error?) -> Void)
```

Get snow conditions

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get snow conditions
MtnManagerAPI.getSnow() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[SnowReport]**](SnowReport.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSummerTrails**
```swift
    open class func getSummerTrails(completion: @escaping (_ data: [SummerTrail]?, _ error: Error?) -> Void)
```

Get summer trails

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get summer trails
MtnManagerAPI.getSummerTrails() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[SummerTrail]**](SummerTrail.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTerrainParks**
```swift
    open class func getTerrainParks(completion: @escaping (_ data: [TerrainPark]?, _ error: Error?) -> Void)
```

Get terrain parks

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get terrain parks
MtnManagerAPI.getTerrainParks() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[TerrainPark]**](TerrainPark.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getWeather**
```swift
    open class func getWeather(completion: @escaping (_ data: Weather?, _ error: Error?) -> Void)
```

Get weather

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK


// Get weather
MtnManagerAPI.getWeather() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**Weather**](Weather.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

