# VATSIM Radar data

## Airlines List

```typescript
interface RadarDataAirline {
    icao: UKE
    name: Air Ukraine
    callsign: AIRUKRAINE
    virtual: true
}
```

- https://data.vatsim-radar.com/airlines
- https://data.vatsim-radar.com/airlines/all

Source: https://gng.aero-nav.com/

- When making a PR, use /custom-data/airlines.json to propose your changes
- Other files in data are auto-generated
- Trying to make VA to show on VR via remarks? Add it to custom-data, or to https://gng.aero-nav.com/AERONAV/icao_fhairlines

Data updates within 7 days after merge. Merge is expected to be done every month. 
