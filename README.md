# MtnManager Swift SDK

SDK for interacting with the MtnManager API, providing real-time access to your ski resort’s public operational data.

For more information, please visit [https://docs.mtnmanager.com/developer/](https://docs.mtnmanager.com/developer/)

## Installation

### Carthage

Run `carthage update`

### CocoaPods

Run `pod install`

## Documentation for API Endpoints

All URIs are relative to *https://your-resort.mtnmanager.com*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*MtnManagerAPI* | [**getAmenities**](docs/MtnManagerAPI.md#getamenities) | **GET** /api/v1/report/amenities | Get amenities
*MtnManagerAPI* | [**getAppReport**](docs/MtnManagerAPI.md#getappreport) | **GET** /api/v1/report/app | Get app report
*MtnManagerAPI* | [**getFullReport**](docs/MtnManagerAPI.md#getfullreport) | **GET** /api/v1/report | Get full report
*MtnManagerAPI* | [**getHours**](docs/MtnManagerAPI.md#gethours) | **GET** /api/v1/report/hours | Get operating hours
*MtnManagerAPI* | [**getLifts**](docs/MtnManagerAPI.md#getlifts) | **GET** /api/v1/report/lifts | Get lifts
*MtnManagerAPI* | [**getOverview**](docs/MtnManagerAPI.md#getoverview) | **GET** /api/v1/report/overview | Get overview
*MtnManagerAPI* | [**getParkingLots**](docs/MtnManagerAPI.md#getparkinglots) | **GET** /api/v1/report/parking-lots | Get parking lots
*MtnManagerAPI* | [**getRuns**](docs/MtnManagerAPI.md#getruns) | **GET** /api/v1/report/runs | Get runs
*MtnManagerAPI* | [**getSnow**](docs/MtnManagerAPI.md#getsnow) | **GET** /api/v1/report/snow | Get snow conditions
*MtnManagerAPI* | [**getSummerTrails**](docs/MtnManagerAPI.md#getsummertrails) | **GET** /api/v1/report/summer-trails | Get summer trails
*MtnManagerAPI* | [**getTerrainParks**](docs/MtnManagerAPI.md#getterrainparks) | **GET** /api/v1/report/terrain-parks | Get terrain parks
*MtnManagerAPI* | [**getTrailMap**](docs/MtnManagerAPI.md#gettrailmap) | **GET** /api/v1/report/trail-map/{uuid} | Get trail map
*MtnManagerAPI* | [**getTrailMapStatic**](docs/MtnManagerAPI.md#gettrailmapstatic) | **GET** /api/v1/report/trail-map/{uuid}/static/{version} | Get static trail map
*MtnManagerAPI* | [**getTrailMaps**](docs/MtnManagerAPI.md#gettrailmaps) | **GET** /api/v1/report/trail-maps | Get trail maps
*MtnManagerAPI* | [**getWeather**](docs/MtnManagerAPI.md#getweather) | **GET** /api/v1/report/weather | Get weather
*MtnManagerAPI* | [**getWebcamHistory**](docs/MtnManagerAPI.md#getwebcamhistory) | **GET** /api/v1/report/webcam/{uuid}/history | Get webcam history
*MtnManagerAPI* | [**getWebcams**](docs/MtnManagerAPI.md#getwebcams) | **GET** /api/v1/report/webcams | Get webcams


## Documentation For Models

 - [Amenity](docs/Amenity.md)
 - [AmenityCalendarEntry](docs/AmenityCalendarEntry.md)
 - [AmenityCategory](docs/AmenityCategory.md)
 - [AmenitySchedule](docs/AmenitySchedule.md)
 - [AppReport](docs/AppReport.md)
 - [CalendarDay](docs/CalendarDay.md)
 - [ClosureReason](docs/ClosureReason.md)
 - [CurrentWeather](docs/CurrentWeather.md)
 - [CurrentWeatherImperial](docs/CurrentWeatherImperial.md)
 - [CurrentWeatherMetric](docs/CurrentWeatherMetric.md)
 - [DailyForecast](docs/DailyForecast.md)
 - [DailyForecastImperial](docs/DailyForecastImperial.md)
 - [DailyForecastMetric](docs/DailyForecastMetric.md)
 - [DayOfWeek](docs/DayOfWeek.md)
 - [EntityImage](docs/EntityImage.md)
 - [FeatureSize](docs/FeatureSize.md)
 - [FeatureType](docs/FeatureType.md)
 - [FullReport](docs/FullReport.md)
 - [GeoBounds](docs/GeoBounds.md)
 - [GeoControlPoint](docs/GeoControlPoint.md)
 - [GeoPoint](docs/GeoPoint.md)
 - [GeometryMode](docs/GeometryMode.md)
 - [HourlyForecast](docs/HourlyForecast.md)
 - [HourlyForecastImperial](docs/HourlyForecastImperial.md)
 - [HourlyForecastMetric](docs/HourlyForecastMetric.md)
 - [LabelOffset](docs/LabelOffset.md)
 - [Lift](docs/Lift.md)
 - [LiftStatus](docs/LiftStatus.md)
 - [LiftType](docs/LiftType.md)
 - [MarkerIcon](docs/MarkerIcon.md)
 - [MobileAppBanner](docs/MobileAppBanner.md)
 - [OperatingHours](docs/OperatingHours.md)
 - [Overview](docs/Overview.md)
 - [OverviewLifts](docs/OverviewLifts.md)
 - [OverviewNews](docs/OverviewNews.md)
 - [OverviewRuns](docs/OverviewRuns.md)
 - [OverviewSummerTrails](docs/OverviewSummerTrails.md)
 - [OverviewTerrainParks](docs/OverviewTerrainParks.md)
 - [ParkingLot](docs/ParkingLot.md)
 - [ParkingLotStatus](docs/ParkingLotStatus.md)
 - [PathUuid](docs/PathUuid.md)
 - [Region](docs/Region.md)
 - [ResortInfo](docs/ResortInfo.md)
 - [ResortStatus](docs/ResortStatus.md)
 - [Run](docs/Run.md)
 - [RunDifficulty](docs/RunDifficulty.md)
 - [RunStatus](docs/RunStatus.md)
 - [Schedule](docs/Schedule.md)
 - [SeasonType](docs/SeasonType.md)
 - [SnowMetrics](docs/SnowMetrics.md)
 - [SnowReport](docs/SnowReport.md)
 - [SummerTrail](docs/SummerTrail.md)
 - [SummerTrailDifficulty](docs/SummerTrailDifficulty.md)
 - [SummerTrailStatus](docs/SummerTrailStatus.md)
 - [SummerTrailType](docs/SummerTrailType.md)
 - [SurfaceCondition](docs/SurfaceCondition.md)
 - [TerrainPark](docs/TerrainPark.md)
 - [TerrainParkFeature](docs/TerrainParkFeature.md)
 - [TerrainParkFeatureStatus](docs/TerrainParkFeatureStatus.md)
 - [TerrainParkStatus](docs/TerrainParkStatus.md)
 - [TrailMap](docs/TrailMap.md)
 - [TrailMapElement](docs/TrailMapElement.md)
 - [TrailMapElementOneOf](docs/TrailMapElementOneOf.md)
 - [TrailMapElementOneOf1](docs/TrailMapElementOneOf1.md)
 - [TrailMapElementOneOf2](docs/TrailMapElementOneOf2.md)
 - [TrailMapElementOneOf3](docs/TrailMapElementOneOf3.md)
 - [TrailMapElementOneOf4](docs/TrailMapElementOneOf4.md)
 - [TrailMapElementOneOf5](docs/TrailMapElementOneOf5.md)
 - [TrailMapElementOneOf6](docs/TrailMapElementOneOf6.md)
 - [TrailMapElementOneOf7](docs/TrailMapElementOneOf7.md)
 - [TrailMapStatic](docs/TrailMapStatic.md)
 - [TrailMapStaticElement](docs/TrailMapStaticElement.md)
 - [TrailMapStaticElementOneOf](docs/TrailMapStaticElementOneOf.md)
 - [TrailMapStaticElementOneOf1](docs/TrailMapStaticElementOneOf1.md)
 - [TrailMapStaticElementOneOf2](docs/TrailMapStaticElementOneOf2.md)
 - [TrailMapStaticElementOneOf3](docs/TrailMapStaticElementOneOf3.md)
 - [TrailMapStaticElementOneOf4](docs/TrailMapStaticElementOneOf4.md)
 - [TrailMapStaticElementOneOf5](docs/TrailMapStaticElementOneOf5.md)
 - [TrailMapStaticElementOneOf6](docs/TrailMapStaticElementOneOf6.md)
 - [TrailMapStaticPath](docs/TrailMapStaticPath.md)
 - [TrailMapSummary](docs/TrailMapSummary.md)
 - [UnitPreference](docs/UnitPreference.md)
 - [Weather](docs/Weather.md)
 - [WeatherConditionCode](docs/WeatherConditionCode.md)
 - [Webcam](docs/Webcam.md)
 - [WebcamHistoryFrame](docs/WebcamHistoryFrame.md)
 - [WebcamHistoryQuery](docs/WebcamHistoryQuery.md)
 - [WebcamHistoryResponse](docs/WebcamHistoryResponse.md)


<a id="documentation-for-authorization"></a>
## Documentation For Authorization

Endpoints do not require authorization.
