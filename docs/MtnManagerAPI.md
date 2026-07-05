# MtnManagerAPI

All URIs are relative to *https://your-resort.mtnmanager.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getAmenities**](MtnManagerAPI.md#getamenities) | **GET** /api/v1/report/amenities | Get amenities
[**getFullReport**](MtnManagerAPI.md#getfullreport) | **GET** /api/v1/report | Get full report
[**getHours**](MtnManagerAPI.md#gethours) | **GET** /api/v1/report/hours | Get operating hours
[**getLifts**](MtnManagerAPI.md#getlifts) | **GET** /api/v1/report/lifts | Get lifts
[**getMobileApp**](MtnManagerAPI.md#getmobileapp) | **GET** /api/v1/report/mobile-app | Get mobile app data
[**getOverview**](MtnManagerAPI.md#getoverview) | **GET** /api/v1/report/overview | Get overview
[**getParkingLots**](MtnManagerAPI.md#getparkinglots) | **GET** /api/v1/report/parking-lots | Get parking lots
[**getRuns**](MtnManagerAPI.md#getruns) | **GET** /api/v1/report/runs | Get runs
[**getSnow**](MtnManagerAPI.md#getsnow) | **GET** /api/v1/report/snow | Get snow conditions
[**getSummerTrails**](MtnManagerAPI.md#getsummertrails) | **GET** /api/v1/report/summer-trails | Get summer trails
[**getTerrainParks**](MtnManagerAPI.md#getterrainparks) | **GET** /api/v1/report/terrain-parks | Get terrain parks
[**getTrailMap**](MtnManagerAPI.md#gettrailmap) | **GET** /api/v1/report/trail-map/{uuid} | Get trail map
[**getTrailMaps**](MtnManagerAPI.md#gettrailmaps) | **GET** /api/v1/report/trail-maps | Get trail maps
[**getWeather**](MtnManagerAPI.md#getweather) | **GET** /api/v1/report/weather | Get weather
[**getWebcamHistory**](MtnManagerAPI.md#getwebcamhistory) | **GET** /api/v1/report/webcam/{uuid}/history | Get webcam history
[**getWebcams**](MtnManagerAPI.md#getwebcams) | **GET** /api/v1/report/webcams | Get webcams


# **getAmenities**
```swift
    open class func getAmenities(acceptLanguage: String? = nil, completion: @escaping (_ data: [Amenity]?, _ error: Error?) -> Void)
```

Get amenities

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get amenities
MtnManagerAPI.getAmenities(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**[Amenity]**](Amenity.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getFullReport**
```swift
    open class func getFullReport(acceptLanguage: String? = nil, completion: @escaping (_ data: FullReport?, _ error: Error?) -> Void)
```

Get full report

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get full report
MtnManagerAPI.getFullReport(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

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
    open class func getHours(acceptLanguage: String? = nil, completion: @escaping (_ data: OperatingHours?, _ error: Error?) -> Void)
```

Get operating hours

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get operating hours
MtnManagerAPI.getHours(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

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
    open class func getLifts(acceptLanguage: String? = nil, completion: @escaping (_ data: [Lift]?, _ error: Error?) -> Void)
```

Get lifts

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get lifts
MtnManagerAPI.getLifts(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**[Lift]**](Lift.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMobileApp**
```swift
    open class func getMobileApp(acceptLanguage: String? = nil, completion: @escaping (_ data: MobileAppResponse?, _ error: Error?) -> Void)
```

Get mobile app data

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get mobile app data
MtnManagerAPI.getMobileApp(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**MobileAppResponse**](MobileAppResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getOverview**
```swift
    open class func getOverview(acceptLanguage: String? = nil, completion: @escaping (_ data: Overview?, _ error: Error?) -> Void)
```

Get overview

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get overview
MtnManagerAPI.getOverview(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

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
    open class func getParkingLots(acceptLanguage: String? = nil, completion: @escaping (_ data: [ParkingLot]?, _ error: Error?) -> Void)
```

Get parking lots

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get parking lots
MtnManagerAPI.getParkingLots(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

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
    open class func getRuns(acceptLanguage: String? = nil, completion: @escaping (_ data: [Run]?, _ error: Error?) -> Void)
```

Get runs

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get runs
MtnManagerAPI.getRuns(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

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
    open class func getSnow(acceptLanguage: String? = nil, completion: @escaping (_ data: [SnowReport]?, _ error: Error?) -> Void)
```

Get snow conditions

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get snow conditions
MtnManagerAPI.getSnow(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

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
    open class func getSummerTrails(acceptLanguage: String? = nil, completion: @escaping (_ data: [SummerTrail]?, _ error: Error?) -> Void)
```

Get summer trails

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get summer trails
MtnManagerAPI.getSummerTrails(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

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
    open class func getTerrainParks(acceptLanguage: String? = nil, completion: @escaping (_ data: [TerrainPark]?, _ error: Error?) -> Void)
```

Get terrain parks

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get terrain parks
MtnManagerAPI.getTerrainParks(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**[TerrainPark]**](TerrainPark.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTrailMap**
```swift
    open class func getTrailMap(uuid: String, acceptLanguage: String? = nil, completion: @escaping (_ data: TrailMap?, _ error: Error?) -> Void)
```

Get trail map

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let uuid = "uuid_example" // String | Resource UUID
let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get trail map
MtnManagerAPI.getTrailMap(uuid: uuid, acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **uuid** | **String** | Resource UUID | 
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**TrailMap**](TrailMap.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getTrailMaps**
```swift
    open class func getTrailMaps(acceptLanguage: String? = nil, completion: @escaping (_ data: [TrailMapSummary]?, _ error: Error?) -> Void)
```

Get trail maps

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get trail maps
MtnManagerAPI.getTrailMaps(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**[TrailMapSummary]**](TrailMapSummary.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getWeather**
```swift
    open class func getWeather(acceptLanguage: String? = nil, completion: @escaping (_ data: [Weather]?, _ error: Error?) -> Void)
```

Get weather

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get weather
MtnManagerAPI.getWeather(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**[Weather]**](Weather.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getWebcamHistory**
```swift
    open class func getWebcamHistory(uuid: String, from: String? = nil, to: String? = nil, acceptLanguage: String? = nil, completion: @escaping (_ data: WebcamHistoryResponse?, _ error: Error?) -> Void)
```

Get webcam history

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let uuid = "uuid_example" // String | Resource UUID
let from = "from_example" // String | Inclusive lower bound on `captured_at` (RFC 3339). (optional) (default to "null")
let to = "to_example" // String | Inclusive upper bound on `captured_at` (RFC 3339). (optional) (default to "null")
let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get webcam history
MtnManagerAPI.getWebcamHistory(uuid: uuid, from: from, to: to, acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **uuid** | **String** | Resource UUID | 
 **from** | **String** | Inclusive lower bound on &#x60;captured_at&#x60; (RFC 3339). | [optional] [default to &quot;null&quot;]
 **to** | **String** | Inclusive upper bound on &#x60;captured_at&#x60; (RFC 3339). | [optional] [default to &quot;null&quot;]
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**WebcamHistoryResponse**](WebcamHistoryResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getWebcams**
```swift
    open class func getWebcams(acceptLanguage: String? = nil, completion: @escaping (_ data: [Webcam]?, _ error: Error?) -> Void)
```

Get webcams

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import MtnManagerSDK

let acceptLanguage = "acceptLanguage_example" // String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported. (optional)

// Get webcams
MtnManagerAPI.getWebcams(acceptLanguage: acceptLanguage) { (response, error) in
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

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **String** | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] 

### Return type

[**[Webcam]**](Webcam.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

