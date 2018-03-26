# Get random IP address
This container connects to a random VPN endpoint to get different IP address using PureVPN.
Based on Ubuntu.

## Usage:
```
docker run --privileged -ti -e purevpn_username='' -e purevpn_password='' sysboss/purevpn-ubuntu-container:latest
```
* Valid PureVPN credentials required.
