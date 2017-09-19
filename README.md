# munin-http_response_time
Munin plugin to measure http response time 

# Install
`copy http_response_ to /usr/share/munin/plugins/`

Now for each domain create a symlink and a config file

### Create a symlink for example:
`ln -s /etc/munin/plugins/http_response_googlecom /usr/share/munin/plugins/http_response_`

### Create a config file
`/etc/munin/plugin-conf.d/http_response_googlecom`

```
[http_response_googlecom]
env.http_response_url https://google.com
```
