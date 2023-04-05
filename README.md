# miranda.py UPnP client - python3 compatible 

Based on [https://github.com/issackelly/wemo/blob/master/miranda.py](https://github.com/issackelly/wemo/blob/master/miranda.py).

Miranda is a UPnP client designed to discover, query and interact with UPnP devices, particularly        Internet Gateway Devices. It can be used to audit UPnP-enabled devices on a network for possible         vulnerabilities.

Features:

- Interactive shell with tab completion and command history
- Passive and active discovery of UPnP devices
- Customizable M-SEARCH queries (query for specific devices/services)
- Full control over application settings such as IP addresses, ports and headers
- Simple enumeration of UPnP devices, services, actions and variables
- Correlation of input/output state variables with service actions
- Ability to send actions to UPnP services/devices


A nice description how to use it can be found here: [How to discover Universal Plug and Play (UPnP) hosts using Miranda](https://medium.com/purple-team/how-to-discover-universal-plug-and-play-upnp-hosts-using-miranda-fee1bbf30000)

cf also [https://www.youtube.com/watch?v=rseMaljMcBY&t=21m15s](https://www.youtube.com/watch?v=rseMaljMcBY&t=21m15s).

To start:

```
python3 miranda.py
```  

![](help.png)
