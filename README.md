gCodeVisualizer - a web-based visual gcode viewer and analyzer.
Available online at http://gcode.ws/

If you want to use it locally with chrome - you will need to add "--allow-file-access-from-files" command line parameter,
which is unsafe (and you should never browse internet with that option "on").

### Docker Setup Instructions:

1. Run docker-compose
``` bash
docker-compose up -d
```

2. Access site via port `7890` on your browser
```
localhost:7890
127.0.0.1:7890
X.X.X.X:7890
<domain-name>:7890
```