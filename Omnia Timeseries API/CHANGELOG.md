# Omnia Timeseries API changelog

All notable changes to this API will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]
- Wildcard search on Timeseries name
- Timeseries Data aggregation (event-based Average, Maximum, Minimum, Standard Deviation and Count)

## [v1.1]
### Added
- Create one timeseries metadata object
- Partial update of one timeseries metadata object
- Full update of one timeseries metadata object
- Retrieve one timeseries metadata object by id
- Retrieve a list of all timeseries, or a subset based on one of the query parameters: name, externalId or assetId
- Retrieve raw data points (timeseries data) within a given time window (id, startTime, endTime)
- Include outside data points (left and right outside points)
- Retrieve first data point of a timeseries
- Retrieve latest data point of a timeseries
- Support for paging (by continuation token) on both timeseries metadata and timeseries data
