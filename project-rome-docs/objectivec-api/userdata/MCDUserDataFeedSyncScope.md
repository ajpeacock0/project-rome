---
title: MCDUserDataFeedSyncScope
description: This class represents the user data that is synchronized with the Connected Devices Platform backend when the app uses certain user-specific Connected Devices functionality.
keywords: microsoft, windows, user activities, iOS, iPhone, objectiveC, connected devices, Project Rome 
---

# class `MCDUserDataFeedSyncScope`

```
@protocol MCDUserDataFeedSyncScope<NSObject>
```
 This interface represents the user data that is synchronized with the Connected Devices Platform
 backend when the app uses certain user-specific Connected Devices functionality, such as user
 activities. An instance is retrieved statically from the class that manages such functionality
 (e.g. **MCDUserActivityChannel**), and it is used in the construction of **MCDUserDataFeed**.