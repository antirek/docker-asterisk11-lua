# docker-asterisk11-lua


## Usage

Use in Dockerfile 

`````
FROM antirek/asterisk11-lua:18.09.1

CMD asterisk && tail -f /var/log/asterisk/messages
`````

## v18.09.1

- luarocks up to 2.4.4

- base ubuntu to 14.04.4

- add luarocks tarantool


## v18.07.2

- add luarocks statsd


## v18.07.1

- add [luchia](https://github.com/thehunmonkgroup/luchia) for connect to CouchDB

- up [luasec](https://github.com/brunoos/luasec) to 0.7