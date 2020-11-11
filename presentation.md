theme: Letters from Sweden
slidenumbers: true
slide-transition: fade(0.3)

# MongoDB Realm

---

# RealmSwift SDK

- v10 ([10.1.2](https://github.com/realm/realm-cocoa/blob/master/CHANGELOG.md))
- Added Combine publishers
- New APIs to access MongoDB directly
  - why?

---

## MongoDB Realm

- Replaces Realm Cloud
- Uses MongoDB 4.4+ for data storage
- Realm: suite of services (formerly "Stitch")
  - Static hosting
  - Push notifications
  - Sync (beta)
  - Triggers, Functions and GraphQL

---

# Connect

- app id instead of URL

---

# Partitioning

- no more "selective sync"
- partition key
- open realm using partition "value"
- value can be dynamic (e.g. userID)

---

# Demo App

https://github.com/phatblat/RealmTaskTracker

---

## References

- [Migrating from Realm Cloud to MongoDB Realm](https://richard-67741.medium.com/migrating-from-realm-cloud-to-mongodb-realm-3f108292d607)
- [Quick Start with SwiftUI and Combine](https://docs.mongodb.com/realm/ios/swiftui/)
- [iOS Swift Tutorial](https://docs.mongodb.com/realm/tutorial/ios-swift/)
- [RealmSwift API Docs](https://realm.io/docs/swift/latest/api/index.html)
- [MongoDB University](https://university.mongodb.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
