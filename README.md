# Deploying
Because the code tries to access localState but Chrome blocks access for
`file://` protocols without exception, deployments need to be accessed via http.

- run `python3 -m http.server` in the Dojoo directory
- access the web app using `127.0.0.1:8000`
