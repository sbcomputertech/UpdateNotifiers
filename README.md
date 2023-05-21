# UpdateNotifiers
To get the latest version data for a project, make a request  to `https://raw.githubusercontent.com/sbcomputertech/UpdateNotifiers/main/<name>.json`
The response should be in the format 
```json
{
    "latest": "<version>",
    "released": <true/false>
}
```
