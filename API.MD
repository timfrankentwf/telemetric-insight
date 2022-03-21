# Introduction

The goal is to built a tool to analyse the telemetry during a live session and acces to previous sessions.

For now, the project wil focus on data-collection and processing.

---

```c#
String base     = 'https://livetiming.formula1.com/';
String event    = '/{YYYY}/{YYYY-MM-DD}_{EventName}/{YYYY-MM-DD}_{Session}/';
String topic    = '{topic}.{filetype}';

String static   = base + 'static' + event + topic;
String live     = base + 'signalr/start?transport=..'
```

## Data available:
1. Heartbeat
2. TopThree
3. TimingStats
4.  TrackStatus
5.  DriverList
6.  RaceControlMessages
7.  SessionInfo
8.  SessionData
9.  LapCount
10. TimingData
11. TimingAppData
12. CarData.z
13. Position.z
14. ExtrapolatedClock
15. RcmSeries
16. WeatherData

### Unknown
SessionStatus
Orchestration
TyreStints
WeatherSeries
PitLaneDisplay
LapChart
