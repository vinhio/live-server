# live-server

This is a little development server. Use it for hacking your HTML/JavaScript/CSS files, but not for deploying the final site.

There are two reasons for using this:

- AJAX requests don't work with the file:// protocol due to security restrictions, i.e. you need a server if your site fetches content through JavaScript.
- Having the page reload automatically after changes to files can accelerate development.

## Run Mac or Linux
```bash
./live-server -addr=0.0.0.0:8080 -dir=./public
```

## Run Windows
```bash
.\live-server-arm64.exe -addr=:7007 -dir="C:\live-server\public"
```
