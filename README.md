# agoric-node-script

Quickly spin up an agoric node with this shell script


1. `git clone https://github.com/GLIBX/agoric-node-script.git`
2. `cd agoric-node-script`
3. `sudo chmod +x node_deploy.sh`
4. `sudo bash node_deploy.sh`
5. "Enter the name of your moniker to initialize chain"
7. Once the script is completed, to check if your node is syncing  and tail your ag service use commands `journalctl -u ag-chain-cosmos.service -f` and  `ag-cosmos-helper status 2>&1 | jq .SyncInfo`




# TODO

Automate sentry nodes deployment with vpn tunnel
