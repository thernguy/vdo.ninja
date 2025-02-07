To run this locally 
- Start a http server with python or vscode live server
For WebRTC support, we need https for to do that
- we ca use caddy with mkcert to generate ssl cert
To generate ssl
- install caddy mkcert
- run: 
  - mkcert [your pc ip]
in the Caddyfile, replace the ip address with your
- run:
  - caddy run 
Now open your ip with:
  - http://[your-ip]:PORT
  
