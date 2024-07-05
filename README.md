# Parse_RSRP_draw

online tool => https://dustinchen26.github.io/parse_ping_fail/

## Example
```
// ping CPE印出時間
ping 10.205.164.5 -t | while read pong; do echo "$(date): $pong"; done
ping 10.205.164.10 -t | while read pong; do echo "$(date): $pong"; done
ping 10.205.164.11 -t | while read pong; do echo "$(date): $pong"; done
ping 10.205.164.18 -t | while read pong; do echo "$(date): $pong"; done

```
