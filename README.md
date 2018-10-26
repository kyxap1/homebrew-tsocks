1. tap repo: `brew tap kyxap1/homebrew-tsocks`
2. install tsocks: `brew install --HEAD tsocks` 
3. set up socks proxy: `ssh -D 8089 remote.server`
4. edit configuration file: `vim /usr/local/etc/tsocks.conf`
5. set server as localhost: `server = localhost`
6. set server port as 8089: `server_port = 8089`
7. check that everything works: `tsocks curl ifconfig.me`
