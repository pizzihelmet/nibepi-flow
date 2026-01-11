# nibepi-flow
Flows.json for NibePi nodes i Node-RED

Detta repo innehåller `flows.json` som hör ihop med:
`pizzihelmet/node-red-contrib-nibepi` (branch `vv-ai`)

## Backup innan du byter flows (rekommenderat)
```
cd ~/.node-red
cp flows.json flows_backup_$(date +%F_%H%M).json
```

## Uppdatera flows.json
Ladda ner `flows.json` från detta repo och ersätt filen här på din Pi:
```
curl -L -o flows.json https://raw.githubusercontent.com/pizzihelmet/nibepi-flow/vv-ai-flow/flows.json
```

Starta om Node-RED efteråt:
`sudo systemctl restart nodered`

https://github.com/pizzihelmet/node-red-contrib-nibepi/tree/vv-ai
