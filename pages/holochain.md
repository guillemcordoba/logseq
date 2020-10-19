---
title: holochain
---

## Modules
### type Agent { id: ID! profile: Profile! }
### type Profile { username: String }
### type Header { id: ID! timestamp: Date! author: Agent! previousHeader: Header! entry: HolochainEntry! }
### interface HolochainEntry { id: ID! headers: [Header!]! }
