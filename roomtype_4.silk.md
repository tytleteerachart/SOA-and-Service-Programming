# Get room type information by room_type_id

This can be run with `silk -silk.url="http://128.199.122.210:9001"`

## `GET /rooms/type/4`

Perform a find room type information with id `4`.

===

* `Status: 200`
* `Content-Type: "application/json;charset=UTF-8"`
```
{"timestamp":1493650055137,"status":404,"error":"Not Found","exception":"room.exception.RoomTypeNotFound","message":"Could not find room type id : 4","path":"/rooms/type/4"}
```
