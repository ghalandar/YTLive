# YTLive: A Dataset of Real-World YouTube Live Streaming Sessions
This repository contains the YTLive dataset, providing timestamped information about YouTube live streams and their viewer statistics.

## Files

### durations.csv
Contains stream duration information with precise timestamps (UTC):
- `videoId`: Unique stream identifier (SHA-256 hash)
- `actualStartTime`: Stream start timestamp (ISO 8601)
- `actualEndTime`: Stream end timestamp (ISO 8601)  
- `duration_in_minutes`: Total duration in minutes
  
### viewers.csv
Contains periodic viewer counts recorded at 5-minute intervals:
- `Timestamp`: Observation time (UTC)
- Columns named with `videoId`s: Concurrent viewer counts

## Key Characteristics
- 📅 Covers 2-month observation period (May & June 2024)
- ⏱ 5-minute sampling interval for viewer counts
- ⚠️ Contains anomalous never-ending streams
- 🔍 3 example streams included in sample data

## Citation
```

```
