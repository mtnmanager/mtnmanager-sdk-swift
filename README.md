# MtnManager Swift SDK

SDK for interacting with the MtnManager API, providing real-time access to your ski resort’s public operational data.

For more information, please visit [https://mtnmanager.com](https://mtnmanager.com)

## Installation

### Carthage

Run `carthage update`

### CocoaPods

Run `pod install`

## Documentation for API Endpoints

All URIs are relative to *https://your-resort.mtnmanager.com*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*MtnManagerAPI* | [**getFullReport**](docs/MtnManagerAPI.md#getfullreport) | **GET** /api/v1/report | Get full report
*MtnManagerAPI* | [**getHours**](docs/MtnManagerAPI.md#gethours) | **GET** /api/v1/report/hours | Get operating hours
*MtnManagerAPI* | [**getLifts**](docs/MtnManagerAPI.md#getlifts) | **GET** /api/v1/report/lifts | Get lifts
*MtnManagerAPI* | [**getOverview**](docs/MtnManagerAPI.md#getoverview) | **GET** /api/v1/report/overview | Get overview
*MtnManagerAPI* | [**getParkingLots**](docs/MtnManagerAPI.md#getparkinglots) | **GET** /api/v1/report/parking-lots | Get parking lots
*MtnManagerAPI* | [**getRuns**](docs/MtnManagerAPI.md#getruns) | **GET** /api/v1/report/runs | Get runs
*MtnManagerAPI* | [**getSnow**](docs/MtnManagerAPI.md#getsnow) | **GET** /api/v1/report/snow | Get snow conditions
*MtnManagerAPI* | [**getSummerTrails**](docs/MtnManagerAPI.md#getsummertrails) | **GET** /api/v1/report/summer-trails | Get summer trails
*MtnManagerAPI* | [**getTerrainParks**](docs/MtnManagerAPI.md#getterrainparks) | **GET** /api/v1/report/terrain-parks | Get terrain parks
*MtnManagerAPI* | [**getWeather**](docs/MtnManagerAPI.md#getweather) | **GET** /api/v1/report/weather | Get weather


## Documentation For Models

 - [CalendarDay](docs/CalendarDay.md)
 - [ClosureReason](docs/ClosureReason.md)
 - [CurrentWeather](docs/CurrentWeather.md)
 - [CurrentWeatherImperial](docs/CurrentWeatherImperial.md)
 - [CurrentWeatherMetric](docs/CurrentWeatherMetric.md)
 - [DailyForecast](docs/DailyForecast.md)
 - [DailyForecastImperial](docs/DailyForecastImperial.md)
 - [DailyForecastMetric](docs/DailyForecastMetric.md)
 - [DayOfWeek](docs/DayOfWeek.md)
 - [FeatureSize](docs/FeatureSize.md)
 - [FeatureType](docs/FeatureType.md)
 - [FullReport](docs/FullReport.md)
 - [HourlyForecast](docs/HourlyForecast.md)
 - [HourlyForecastImperial](docs/HourlyForecastImperial.md)
 - [HourlyForecastMetric](docs/HourlyForecastMetric.md)
 - [Lift](docs/Lift.md)
 - [LiftStatus](docs/LiftStatus.md)
 - [LiftType](docs/LiftType.md)
 - [OperatingHours](docs/OperatingHours.md)
 - [Overview](docs/Overview.md)
 - [ParkingLot](docs/ParkingLot.md)
 - [ParkingLotStatus](docs/ParkingLotStatus.md)
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
 - [UnitPreference](docs/UnitPreference.md)
 - [Weather](docs/Weather.md)
 - [WeatherConditionCode](docs/WeatherConditionCode.md)


<a id="documentation-for-authorization"></a>
## Documentation For Authorization

Endpoints do not require authorization.
