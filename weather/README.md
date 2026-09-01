# VRChat weather feed

`current.txt` is the lightweight file read by `VRCNetworkSkyWeather.cs`.

## Raw URL

```text
https://raw.githubusercontent.com/Matzzteg/VRCImages/main/weather/current.txt
```

## Format

```text
scenario=clear
```

Allowed values: `clear`, `cloudy`, `overcast`, `rain`, `storm`.

The hourly **Update VRChat weather** workflow writes this file from the current Berlin weather condition. **Set VRChat weather manually** is intended for scene testing; the next automatic update replaces the manual scenario.
