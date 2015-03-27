# Wunderlist for Pebble Watch

### Two Development Approaches
1. Directly fetch from API (multiple calls)
2. Register webhook with GCN and APNs (requires companion app)

### Direct Fetch from API
| Advantages                                 | Disadvantages                                      |
|--------------------------------------------|----------------------------------------------------|
| Shorter development time                   | Slower                                             |
| Less code maintenance                      | No caching, always needs internet                  |
| Shorter learning curve for Beto and Adrian | No push notification for updates or new team tasks |


###  Companion App
| Advantages                                    | Disadvantages                                   |
|-----------------------------------------------|-------------------------------------------------|
| Faster                                        | Three separate code bases                       |
| Push notifications                            | Longer development time                         |
| Experience with both platforms (Android, iOS) | Yet another companion app                       |
|                                               | Learning curve for iOS development              |
