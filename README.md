# syncplay-server
Dockerfile for a syncplay server

# Usage
<pre>
docker create \
--name=syncplay \
--net=host \
-e PASSWORD=<PASSWORD> \
-e PORT=<PORT> \
bentech2/syncplay-server
<pre>
