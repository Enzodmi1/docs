```
curl -i -X POST \\
    -H "Authorization: Bearer ${FLY\_API\_TOKEN}" -H "Content-Type: application/json" \\
    "http://${FLY\_API\_HOSTNAME}/v1/apps/my-awesome-machine-app/machines/d5683219b298e9/start" 

```
**Status: 200**
```json
{
  "previous\_state": "stopped"
}
```