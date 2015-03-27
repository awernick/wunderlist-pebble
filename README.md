# Wunderlist for Pebble Watch

1. Directly fetch from API (multiple calls)
2. Register webhook with GCN and APNs (requires companion app)

## Direct Fetch from API
### Advantages
* Shorter development time
* Less code maintenance
* Shorter learning curve for Beto and Adrian

### Disadvantages
* Slower
* No caching, always needs internet
* No push notification for updates or new team tasks

## Companion App
### Advantages
* Faster
* Push notifications
* Experience with both platforms (Android, iOS)

### Disadvantage
* Three separate code bases
* Longer development time
* Yet another companion app 
* Learning curve for iOS development
