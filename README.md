# llama.cpp Zabbix template

A zabbix 6.4 template for gathering metrics from the llama.cpp server.

## Macros

| Variable | Description | Must Be Set Per Host | Default |
| -------  | ----------- | -------------------  | ------- |
| {$HOST}  | IP Address / DNS to connect to | Yes | -     |
| {$PORT} | The port llama.cpp is listening on | No | 8080 |
| {$URL} | The url where llama.cpp  metrics can be found | No | /metrics |
| {$SCHEME} | The HTTP scheme to fetch data over | No | http:// |

## Setup

Simply import the template, attach to a Zabbix host, set the macros, and wait for data.