# pydistance
python calculate distance between two point...

# env
```
python==2.7+
```

# usage
```
# coding=utf-8

import pydistance

long1 = 22.0
lat1 = 131.2

long2 = 24.0
lat2 = 110.2

print "haversine = %s(m)" % pydistance.get_distance_haversine(long1, lat1, long2, lat2)
print "WGS-84 = %s(m)" % pydistance.get_distance_wgs84(long1, lat1, long2, lat2)

```

# result
```
haversine = 2337555.38881(m)
WGS-84 = 2340173.99386(m)
```
