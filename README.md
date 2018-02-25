# syncplay-server
Dockerfile for a syncplay server

![syncplay](http://syncplay.pl/wp-content/uploads/2012/12/SyncplayIcon128.png) 

[Syncplay](http://syncplay.pl/)

## Usage

```
docker create \
--name=syncplay \
--net=host \
-e PASSWORD=<PASSWORD> \
-e PORT=<PORT> \
bentech2/syncplay-server
```
