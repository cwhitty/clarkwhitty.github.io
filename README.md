# project://Cisco
3 QuickCall Libraries in project://Cisco:
## project://Cisco/session_profiles/7009.fftc (project://Cisco/session_profiles/7009.fftc)

### main
### setVlanIpAddress

Argument | Description
------------ | -------------
vlanId | 
ipAddr | 
mask | 
port | 
## project://Cisco/session_profiles/CiscoIOS_Telnet_Quickcalls.fftc (project://Cisco/session_profiles/CiscoIOS_Telnet_Quickcalls.fftc)
looks like getConnectedVlans could use some work
### main
creates the vlan
adds the port to the newly created vlan (trunk or access mode)

### login

Argument | Description
------------ | -------------
terminalAccess | vty or tty
vty means virtual terminal like ssh or telnet
tty means physical terminal like the device console
### startOfProcedure

Argument | Description
------------ | -------------
printedMessage1 | first message to be printed to the console
### showIpTraffic
### removeVlan

Argument | Description
------------ | -------------
vlan | vlan id to remove
### showInterfaces
### addPortToVlan

Argument | Description
------------ | -------------
port | port name 
for example: Te0/17
mode | access or trunk
basically, tagged or untagged
vlan | vlan ID to assign
### setPortToDefault

Argument | Description
------------ | -------------
port | 
### setupVlan
creates the vlan
adds the interface to the newly created vlan (access or trunk mode)

Argument | Description
------------ | -------------
session | 
vlan | 
port | 
mode | 
protocolFamily | valid values are: ethernet-switching, inet
### getConnectedVlans

Argument | Description
------------ | -------------
port | 
### removePortFromVlan

Argument | Description
------------ | -------------
session | 
port | 
mode | 
vlan | 
### addSubnetToOspfV2

Argument | Description
------------ | -------------
processId | 
linkName | 
mask | 
area | 
port | 
### addSubnetToOspfV3

Argument | Description
------------ | -------------
processId | 
linkName | 
area | 
### setupOspfV3

Argument | Description
------------ | -------------
processId | 
routerId | the 4 byte ip address used for this router as its router id
### setOspfV2CostOnInterface

Argument | Description
------------ | -------------
cost | 
intName | the name of the interface on which to set the cost, like Te 0/16 or Vlan132
### setupSwitchport

Argument | Description
------------ | -------------
session | 
port | 
mode | 
protocolFamily | valid values are: ethernet-switching, inet
### setVlanIpAddress

Argument | Description
------------ | -------------
vlanId | 
ipAddr | 
mask | 
port | 
### setInterfaceIpAddress

Argument | Description
------------ | -------------
intName | the name of the interface to which the IP address is assigned
for example: Te0/17, Vlan125
ipAddr | IP Address to assign
for example: 10.1.1.1, 2001:125::1
mask | netmask to be applied to the IP address
for example: /24, /64 
ipVersion | IP version
values are 4 or 6
### setVlanIpV6Address

Argument | Description
------------ | -------------
vlanId | 
ipAddr | 
mask | 
### addVlanToTrunk

Argument | Description
------------ | -------------
session | 
vlan | 
### setupSpanningTree

Argument | Description
------------ | -------------
mode | mstp, rstp, stp, pvst
msti | mst instance number, if applicable
vlan | vlan id to add to the mst instance, if applicable
revision | mst revision number, if applicable
### setBridgePriority

Argument | Description
------------ | -------------
priority | the bridge priority value used by spanning tree
mode | stp, mstp, rstp, pvst
msti | the mst instance value, if applicable
vlan | for switches that only do per-vlan stp, like some cisco switches, we need to specify the bridge priority at the vlan level.  so this is the vlan id that we want to affect with regards to spanning tree priority
### getBridgeId
### getBridgePriority

Argument | Description
------------ | -------------
mode | stp, rstp
vlan | for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan.  so this is the vlan id that we want to query with regards to spanning tree priority
### iThinkThisCanBeDeprecatedcheckRootSwitch

Argument | Description
------------ | -------------
mode | mstp, stp, rstp
msti | mst instance, if applicable
vlan | for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan.  so this is the vlan id that we want to query with regards to spanning tree root
### checkRootSwitch

Argument | Description
------------ | -------------
mode | mstp, stp, rstp, pvst
msti | mst instance, if applicable
vlan | for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan.  so this is the vlan id that we want to query with regards to spanning tree root
### setPathCost

Argument | Description
------------ | -------------
session | 
port | 
cost | 
### checkPortState
### changePortState

Argument | Description
------------ | -------------
session | 
port | 
state | 
### checkBPDUs

Argument | Description
------------ | -------------
session | 
port | 
edge | 
### setPortPriority

Argument | Description
------------ | -------------
priority | the spanning tree port priority 
mode | stp, rstp, mstp, pvst
msti | mst instance, if applicable
int | the interface name on which to apply the port priority i.e., Eth3/10/1
vlan | vlan ID, if applicable
### changeMSTRegionName

Argument | Description
------------ | -------------
session | 
name | 
### setStpToDefault

Argument | Description
------------ | -------------
mstiList | a list of mst instances to remove from the switch, if applicable
### checkEtherchannel

Argument | Description
------------ | -------------
session | 
state | 
member | 
lag | 
### setSpanningTreeInterfaceCost

Argument | Description
------------ | -------------
mode | stp, rstp, pvst

intName | interface name
cost | the spanning tree cost of this interface
msti | mst instance, if applicable
vlan | vlan id, if applicable
### checkTrafficBalancing

Argument | Description
------------ | -------------
session | 
port1 | 
port2 | 
### setPortMTU

Argument | Description
------------ | -------------
session | 
port | 
mtu | 
### clearMacAddressTable

Argument | Description
------------ | -------------
session | 
type | 
### removeOSPFv2
### setOspfV2RouterId

Argument | Description
------------ | -------------
routerId | 
### showOspfV2Neighbors
### showOspfV2Routes
### showRunningConfig
### ping

Argument | Description
------------ | -------------
target | 
ipVersion | 4 or 6
numTrialPings | number of 'trial' pings to perform before taking an actual frameloss measurement
integer, usually 0 or 1
### shutdownInterface

Argument | Description
------------ | -------------
interface | the interface that you want to shutdown
### enableInterface

Argument | Description
------------ | -------------
interface | the interface that you want to no shut
### setupIGMPQuerier

Argument | Description
------------ | -------------
vlan | the vlan you want to enable igmp querier on
ipAddress | the ip address you want to the igmp querier function to use
### showIGMPQuerierAddress

Argument | Description
------------ | -------------
vlan | The VLAN ID where IGMP querier is running
### showIGMPGroups

Argument | Description
------------ | -------------
vlan | 
### addBgpNeighbor

Argument | Description
------------ | -------------
localAs | The local AS, the AS of this router
neighborIp | The IPv4 address of the neighbor to be added
neighborAs | The AS of the neighbor to be added
md5Password | 
### removeBGPv4

Argument | Description
------------ | -------------
AS | The BGP AS
### showBgpNeighbors

Argument | Description
------------ | -------------
specificNeighborIpAddr | if given, we show the status for this specific neighbor, otherwise we show them all
### showBgpRoutes

Argument | Description
------------ | -------------
path | you can pass a path into this proc, and the proc will return how many routes contain that path
nextHop | you can pass a nextHop into this proc, and the proc will return how many routes are using that next hop
### showInterface

Argument | Description
------------ | -------------
interface | the name of the interface
### showVersion
### removeOSPFv3

Argument | Description
------------ | -------------
interface | the interface name from which you want to remove ospfv3
### showOspfV3Routes
### showOspfV3Database
### showOspfV3Neighbors
### showSpanningTreeMstConfig
### getBridgeMac

Argument | Description
------------ | -------------
mode | mstp, rstp, pvst
msti | the mst instance value, if applicable

### getSpanningTreeRootPathCost

Argument | Description
------------ | -------------
mode | stp, rstp, pvst
vlan | for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan.  so this is the vlan id that we want to query with regards to spanning tree root path cost
### showSpanningTreeInterface

Argument | Description
------------ | -------------
mode | mstp, rstp, stp, pvst
msti | the mst instance value, if applicable
intName | interface name
vlan | for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree instance for each vlan.  so this is the vlan id that we want to query with regards to spanning tree information
### showMacInAddressTable

Argument | Description
------------ | -------------
mac | mac address to find in the address table, i.e. 0000.0100.0000
### showLAG

Argument | Description
------------ | -------------
portChannelId | the port channel id to be queried
### removeLAG

Argument | Description
------------ | -------------
portChannelId | the port channel id  to be queried
### addPortToLAG

Argument | Description
------------ | -------------
port | the port name that will be added to the LAG
portChannelId | the port channel id (the LAG interface) to which a port will be added
mode | active or static
### showLACPInterface

Argument | Description
------------ | -------------
portChannelId | the port channel id to be queried
port | the port to be queried
### setLacpTimeout

Argument | Description
------------ | -------------
portChannelId | the port channel that we want to configure
timeOutValue | LONG or SHORT
### addLAGPortToVlan
For some routers, one must add both the interfaces and the port-channel into a vlan.  Other routers just require the port-channel to be added.

Argument | Description
------------ | -------------
port | port name 
for example: Te0/17
mode | access or trunk
basically, tagged or untagged
vlan | vlan ID to assign
portChannelId | the port channel name decimal value, i.e. 25 (to indicate po25)
### showSystemId
### getLldpLocalPortId

Argument | Description
------------ | -------------
intName | interface name
### showLldpNeighborsFromInterface

Argument | Description
------------ | -------------
intName | the local interface where we see lldp neighbors
### setupLLDP

Argument | Description
------------ | -------------
port | interface where lldp is to be configured
### enableIpRouting

Argument | Description
------------ | -------------
ipVersion | IP version (values are 4 or 6)
### setSpanningTreeTimers

Argument | Description
------------ | -------------
mode | stp, rstp, mstp, pvst
forwardDelay | set the forward delay for the spanning tree
helloTime | set the hello Time for the spanning tree
maxAge | set the max age for the spanning tree
msti | mst instance, if applicable
vlan | vlan ID, if using PVST
### showSpanningTreeRootTimers

Argument | Description
------------ | -------------
mode | pvst
msti | mst instance, if applicable
vlan | vlan ID, if applicable
### showInterfacesStatus
## project://Cisco/session_profiles/CiscoNexus_Telnet_Quickcalls.fftc (project://Cisco/session_profiles/CiscoNexus_Telnet_Quickcalls.fftc)

### main
### checkBPDUs

Argument | Description
------------ | -------------
session | 
port | 
edge | 
### setupVlan
creates the vlan
adds the interface to the newly created vlan (access or trunk mode)

Argument | Description
------------ | -------------
session | 
vlan | 
port | 
mode | 
protocolFamily | valid values are: ethernet-switching, inet
### changeLAG

Argument | Description
------------ | -------------
session | 
port | 
action | addLAG_S - add port-channel
removeLAG_S - remove port-channel
addPort - add port to port-channel
removePort - remove port from port channel
addLAG_Lacp - add port-channel Lacp
removeLAG_Lacp - remove port-channel Lacp
addPort_Lacp - add port to port-channel Lacp
removePort_Lacp - remove port from port channel Lacp
lag | 
mode | 
### checkEtherchannel

Argument | Description
------------ | -------------
session | 
state | 
member | 
lag | 
### showLLDP

Argument | Description
------------ | -------------
session | 
mode | 
### changeMSTRegionName

Argument | Description
------------ | -------------
session | 
name | 
### checkTrafficBalancing

Argument | Description
------------ | -------------
session | 
port1 | 
port2 | 
### setPortMTU

Argument | Description
------------ | -------------
port | the port name, i.e., Eth3/10/1
mtu | the desired MTU to be used on a system-wide basis
values are 1500 - 9216
### clearMacAddressTable

Argument | Description
------------ | -------------
type | dynamic is the only choice
### login

Argument | Description
------------ | -------------
user | 
pass | 
terminalAccess | vty or tty
vty means virtual terminal like ssh or telnet
tty means physical terminal like the device console
### ping

Argument | Description
------------ | -------------
target | 
ipVersion | 4 or 6
numTrialPings | number of 'trial' pings to perform before taking an actual frameloss measurement
integer, usually 0 or 1
### removeOSPFv2
### removeOSPFv3

Argument | Description
------------ | -------------
interface | the interface name from which you want to remove ospfv3
### setupOspfV3

Argument | Description
------------ | -------------
processId | 
routerId | the 4 byte ip address used for this router as its router id
### showOspfV2Neighbors
### showOspfV2Routes
### addBgpNeighbor

Argument | Description
------------ | -------------
localAs | The local AS, the AS of this router
neighborIp | The IPv4 address of the neighbor to be added
neighborAs | The AS of the neighbor to be added
md5Password | 
### showIGMPQuerierAddress

Argument | Description
------------ | -------------
vlan | The VLAN ID where IGMP querier is running
### setupIGMPQuerier

Argument | Description
------------ | -------------
vlan | the vlan you want to enable igmp querier on
ipAddress | the ip address you want to the igmp querier function to use
### showOspfV3Database
### showOspfV3Neighbors
### showOspfV3Routes
### addSubnetToOspfV3

Argument | Description
------------ | -------------
processId | 
linkName | 
area | 
### removeBGPv4

Argument | Description
------------ | -------------
AS | The BGP AS
### showLACPInterface

Argument | Description
------------ | -------------
portChannelId | the port channel id to be queried
port | the port to be queried
### setLacpTimeout

Argument | Description
------------ | -------------
portChannelId | the port channel that we want to configure
timeOutValue | LONG or SHORT
### showLAG

Argument | Description
------------ | -------------
portChannelId | the port channel id to be queried
### showLldpNeighborsFromInterface

Argument | Description
------------ | -------------
intName | the local interface where we see lldp neighbors
### setupLLDP

Argument | Description
------------ | -------------
port | interface where lldp is to be configured
### showSystemId
Created on: Monday November 06 2017 12:48:25 CST
