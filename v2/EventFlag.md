# イベントフラグAPI

url: https://www.fljpapi.com/api/v2/timeline
メソッド:GET

### APIの説明
イベントフラグを取得できます。

**レスポンス例(短縮しています)**
```json
{
  "data": {
    "cacheIntervalMins": 15,
    "channels": {
      "client-events": {
        "cacheExpire": "2025-07-23T12:12:49.789Z",
        "states": [
          {
            "activeEvents": [
              {
                "activeSince": "2024-04-09T13:00:00.000Z",
                "activeUntil": "2026-01-01T14:00:00.000Z",
                "eventType": "EventFlag.Event_DelMar_Season01_Dailies"
              }
           ]
          }
         ]
        }
       }
      }
}
              
```
