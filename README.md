# fastestMirror
returns the fastest mirror from a list 

go get github.com/mataperezluis/fastestMirror
go install github.com/mataperezluis/fastestMirror/mirrorFinder

run: 
$GOPATH/bin/mirrorFinder

# Valid request
curl -i -X GET "http://localhost:8000/fastest-mirror" 

The response is as follows:
HTTP/1.1 200 OK
Content-Type: application/json
Date: Wed, 27 Mar 2019 23:13:42 GMT
Content-Length: 64
{"fastest_url":"http://ftp.sk.debian.org/debian/","latency":230}

