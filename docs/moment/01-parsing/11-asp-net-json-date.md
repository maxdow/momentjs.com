---
title: ASP.NET JSON Date
version: 1.3.0
signature: |
  moment(String);
---


ASP.NET returns dates in JSON as `/Date(1198908717056)/` or `/Date(1198908717056-0700)/`

If a string that matches this format is passed in, it will be parsed correctly.

```javascript
moment("/Date(1198908717056-0700)/"); // 2007-12-28T23:11:57.056-07:00
```
