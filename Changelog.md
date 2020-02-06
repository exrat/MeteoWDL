# FreshWDL Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)

## 1.1.8 Alpha 2019-11-03
_Quality of Life Update_

#### Added
- Option to only show Watts per Meter Squared on solar gauge. (To activate this, add the following to the 'solar' section of 'gaugeSettings' in your config file: mode: "Watt").
- Option to disable particular graphs if desired.
- Trend arrow to humidity gauge.
- Trend arrow to main temperature gauge.

#### Changes
- Barometer now displays "+" sign for positive trends.
- Windchill/heatindex gauge now changes tooltip accordingly.
- Changed number of ticks on rain gauges to make nicer numbers.
- Changed rainfall tick scaling method - no long uniform scaling - to produce nicer numbers.
- Changed number of ticks on windspeed gauge to produce whole numbers.
- Null (blank, "---") forecasts are now suppressed.

## 1.1.7 Alpha 2018-07-06

#### Added
- Dutch Language
- Danish Language
- Beaufort Scale to wind gauge / wind units

#### Changes
- Windchill gauge can now be set to heat index mode
- Windchill gauge can now be set to automatically swap between heat index and windchill mode
- Sprites now hosted with rest of repository

#### Fixed
- Text can no longer overflow and get cut off

## 1.1.6 Alpha 2018-06-28

#### Added
- Support for other langauges. (Note: please get in touch if you want to help with translating!)
- The date supplied by the clientraw file now displays in status guage.

#### Changes
- Rain gauge ticks reworked
- HTML now W3C valid

#### Fixed
- Issue with "-" character in station name
- Tweens (animations) no longer gitch if overidden by other animations

## 1.1.5 Alpha
(Only used internally)

## 1.1.4 Alpha 2018-01-17

#### Changes
- Status gauge rephrased

#### Fixed
- Now compatible with Internet Explorer
- Yearly rain graph date display issue solved
- Weekly rain graph date display issue solved
- Rain gauge ticks now always whole values
- UV bar display error when solar not enabled

## 1.1.3 Alpha 2018-01-14

#### Added
- Station name to status
- Ability to hide gauges using config file

#### Changed
- Status indicator colour clearer
- Tweaked auto scaling on rain and windspeed gauges
- Record date display now unambiguous
- Temporarily hidden altitude button
- Status time now represents time given in clientraw file

#### Fixed
- Date format on some graphs
- Screen rotation on mobile no longer cuts of bottom section
- Units now round to correct number of DP
- Overlap of temperature min/max

## 1.1.1 Alpha 2018-01-05
About: First Public Release.

#### Added
- Config file

#### Changed
- To dynamic HTML fetching
- To chartJS version 2.7.1

#### Fixed
- Minor memory leak

## 1.0.1 Alpha 2017-12-29

#### Added
- Status Widget

#### Improved
- Unit Buttons
- Checks if widgets need to be updated
- Data collection backend

## 1.0.0 Alpha

#### Added
- Base System
