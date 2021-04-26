---
tags: ACDC, KERI
email: sam@samuelsmith.org
version: 1.00
---

# ACDC Identifiers

[![hackmd-github-sync-badge](https://hackmd.io/n3EappXuQQaBxxkPkUPPIQ/badge)](https://hackmd.io/n3EappXuQQaBxxkPkUPPIQ)


## Namespaced


```namespace:testatorid:acdcid/path?query#fragment```

```did:keri:E4ReNhXtuh4DAKe4_qcX__uF70MnOvW5Wapj3LcQ8CT4:E8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E```

```URN:aid:E4ReNhXtuh4DAKe4_qcX__uF70MnOvW5Wapj3LcQ8CT4:E8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E```

```URN:aid:E4ReNhXtuh4DAKe4_qcX__uF70MnOvW5Wapj3LcQ8CT4:E8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E/mypath?myquery#myfragment```




### Namespaced Example

```json

{
  "cid": "did:keri:E4ReNhXtuh4DAKe4_qcX__uF70MnOvW5Wapj3LcQ8CT4:E8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E",
  "srcs": 
  [
    "did:keri:EMnOvW5Wapj3Lc4ReNhXtuh4DAKe4_qcX__uF70Q8CT4:ER6gzbMUqE8MU3qwXh0CgG4k3k4WKkk9hM0iaVeCmG7E",
    "urn:aid:Etuh4DAKe44ReNhX_qcX__uF70MnOvW5Wapj3LcQ8CT4:EzbMUqEXh08MU3qwR6gCgG4k3k4WKkk9hM0iaVeCmG7E"
  ],
  "schema": "alalalal",
  "datum": 
  {
    "k": "v"
  },
}
```

## Un-Namespaced

```testatorid:acdcid```

```E4ReNhXtuh4DAKe4_qcX__uF70MnOvW5Wapj3LcQ8CT4:E8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E```




### Un-Namespaced Example

```json

{
  "cid": "did:keri:E4ReNhXtuh4DAKe4_qcX__uF70MnOvW5Wapj3LcQ8CT4:E8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E",
  "srcs": 
  [
    "cid:keri:EMnOvW5Wapj3Lc4ReNhXtuh4DAKe4_qcX__uF70Q8CT4:ER6gzbMUqE8MU3qwXh0CgG4k3k4WKkk9hM0iaVeCmG7E",
    "cid:keri:Etuh4DAKe44ReNhX_qcX__uF70MnOvW5Wapj3LcQ8CT4:EzbMUqEXh08MU3qwR6gCgG4k3k4WKkk9hM0iaVeCmG7E"
  ],
  "schema": "alalalal",
  "datum": 
  {
    "k": "v"
  },
}
```

## KERI Like Derivation

Substitue dummy values for ACDC Portion CID

```json

{
  "cid": "did:keri:E4ReNhXtuh4DAKe4_qcX__uF70MnOvW5Wapj3LcQ8CT4:########################################",
  "srcs": 
  [
    "cid:keri:EMnOvW5Wapj3Lc4ReNhXtuh4DAKe4_qcX__uF70Q8CT4:ER6gzbMUqE8MU3qwXh0CgG4k3k4WKkk9hM0iaVeCmG7E",
    "cid:keri:Etuh4DAKe44ReNhX_qcX__uF70MnOvW5Wapj3LcQ8CT4:EzbMUqEXh08MU3qwR6gCgG4k3k4WKkk9hM0iaVeCmG7E"
  ],
  "schema": "alalalal",
  "datum": 
  {
    "k": "v"
  },
}
```
Compute digest of serializtion of ACDC mapping with dummy values

```8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E```

Prepend derivation code to digest to create fully qualified identifier

```E8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E```

Replace dummy with fully qualified identifier

```json

{
  "cid": "did:keri:E4ReNhXtuh4DAKe4_qcX__uF70MnOvW5Wapj3LcQ8CT4:E8MU3qwR6gzbMUqEXh0CgG4k3k4WKkk9hM0iaVeCmG7E",
  "srcs": 
  [
    "cid:keri:EMnOvW5Wapj3Lc4ReNhXtuh4DAKe4_qcX__uF70Q8CT4:ER6gzbMUqE8MU3qwXh0CgG4k3k4WKkk9hM0iaVeCmG7E",
    "cid:keri:Etuh4DAKe44ReNhX_qcX__uF70MnOvW5Wapj3LcQ8CT4:EzbMUqEXh08MU3qwR6gCgG4k3k4WKkk9hM0iaVeCmG7E"
  ],
  "schema": "alalalal",
  "datum": 
  {
    "k": "v"
  },
}
```
