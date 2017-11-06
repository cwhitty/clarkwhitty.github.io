<style>TABLE,TD,TH{border:1px solid black;border-collapse:collapse;} th{text-align:left;background-color:AliceBlue;} H1,H2{padding-left:15px} .smallText{font-size:10px; color:black; font-family:courier} .normalText{font-size:14px; color:black; font-family:arial} .procText{font-size:14px; color:black; font-family:arial; padding-left:35px} .headerText{font-size:30px; color:black; font-weight:bold; font-family:arial ;text-align:left; padding-left:5px} .header2Text{font-size:20px; color:darkblue; font-weight:bold; font-family:arial ;text-align:left; padding-left:5px} .header3Text{font-size:18px; color:darkblue; font-weight:bold; font-family:arial ;text-align:left; padding-left:10px}</style>  

<div class="headerText">project://Cisco</div>

<div class="header2Text">3 QuickCall Libraries in project://Cisco:</div>

<div class="header2Text">project://Cisco/session_profiles/7009.fftc (project://Cisco/session_profiles/7009.fftc)</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">main</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setVlanIpAddress</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlanId</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipAddr</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mask</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

</tbody>

</table>

</div>

<div class="header2Text">project://Cisco/session_profiles/CiscoIOS_Telnet_Quickcalls.fftc (project://Cisco/session_profiles/CiscoIOS_Telnet_Quickcalls.fftc)</div>

<div style="margin-left:35px; font-size:12px;color:black; font-family:arial">looks like getConnectedVlans could use some work</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">main</div>

<div class="procText">creates the vlan adds the port to the newly created vlan (trunk or access mode)</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">login</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">terminalAccess</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vty or tty vty means virtual terminal like ssh or telnet tty means physical terminal like the device console</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">startOfProcedure</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">printedMessage1</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">first message to be printed to the console</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showIpTraffic</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removeVlan</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vlan id to remove</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showInterfaces</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addPortToVlan</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">port name for example: Te0/17</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">access or trunk basically, tagged or untagged</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vlan ID to assign</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setPortToDefault</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupVlan</div>

<div class="procText">creates the vlan adds the interface to the newly created vlan (access or trunk mode)</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">protocolFamily</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">valid values are: ethernet-switching, inet</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">getConnectedVlans</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removePortFromVlan</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addSubnetToOspfV2</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">processId</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">linkName</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mask</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">area</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addSubnetToOspfV3</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">processId</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">linkName</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">area</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupOspfV3</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">processId</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">routerId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the 4 byte ip address used for this router as its router id</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setOspfV2CostOnInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">cost</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">intName</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the name of the interface on which to set the cost, like Te 0/16 or Vlan132</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupSwitchport</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">protocolFamily</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">valid values are: ethernet-switching, inet</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setVlanIpAddress</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlanId</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipAddr</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mask</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setInterfaceIpAddress</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">intName</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the name of the interface to which the IP address is assigned for example: Te0/17, Vlan125</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipAddr</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">IP Address to assign for example: 10.1.1.1, 2001:125::1</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mask</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">netmask to be applied to the IP address for example: /24, /64</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipVersion</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">IP version values are 4 or 6</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setVlanIpV6Address</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlanId</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipAddr</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mask</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addVlanToTrunk</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupSpanningTree</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mstp, rstp, stp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mst instance number, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vlan id to add to the mst instance, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">revision</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mst revision number, if applicable</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setBridgePriority</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">priority</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the bridge priority value used by spanning tree</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">stp, mstp, rstp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the mst instance value, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">for switches that only do per-vlan stp, like some cisco switches, we need to specify the bridge priority at the vlan level. so this is the vlan id that we want to affect with regards to spanning tree priority</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">getBridgeId</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">getBridgePriority</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">stp, rstp</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan. so this is the vlan id that we want to query with regards to spanning tree priority</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">iThinkThisCanBeDeprecatedcheckRootSwitch</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mstp, stp, rstp</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mst instance, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan. so this is the vlan id that we want to query with regards to spanning tree root</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">checkRootSwitch</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mstp, stp, rstp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mst instance, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan. so this is the vlan id that we want to query with regards to spanning tree root</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setPathCost</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">cost</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">checkPortState</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">changePortState</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">state</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">checkBPDUs</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">edge</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setPortPriority</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">priority</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the spanning tree port priority</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">stp, rstp, mstp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mst instance, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">int</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the interface name on which to apply the port priority i.e., Eth3/10/1</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vlan ID, if applicable</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">changeMSTRegionName</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">name</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setStpToDefault</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mstiList</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">a list of mst instances to remove from the switch, if applicable</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">checkEtherchannel</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">state</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">member</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">lag</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setSpanningTreeInterfaceCost</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">stp, rstp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">intName</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">interface name</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">cost</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the spanning tree cost of this interface</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mst instance, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vlan id, if applicable</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">checkTrafficBalancing</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port1</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port2</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setPortMTU</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mtu</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">clearMacAddressTable</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">type</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removeOSPFv2</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setOspfV2RouterId</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">routerId</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV2Neighbors</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV2Routes</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showRunningConfig</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">ping</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">target</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipVersion</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">4 or 6</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">numTrialPings</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">number of 'trial' pings to perform before taking an actual frameloss measurement integer, usually 0 or 1</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">shutdownInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">interface</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the interface that you want to shutdown</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">enableInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">interface</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the interface that you want to no shut</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupIGMPQuerier</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the vlan you want to enable igmp querier on</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipAddress</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the ip address you want to the igmp querier function to use</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showIGMPQuerierAddress</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The VLAN ID where IGMP querier is running</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showIGMPGroups</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addBgpNeighbor</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">localAs</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The local AS, the AS of this router</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">neighborIp</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The IPv4 address of the neighbor to be added</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">neighborAs</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The AS of the neighbor to be added</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">md5Password</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removeBGPv4</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">AS</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The BGP AS</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showBgpNeighbors</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">specificNeighborIpAddr</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">if given, we show the status for this specific neighbor, otherwise we show them all</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showBgpRoutes</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">path</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">you can pass a path into this proc, and the proc will return how many routes contain that path</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">nextHop</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">you can pass a nextHop into this proc, and the proc will return how many routes are using that next hop</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">interface</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the name of the interface</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showVersion</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removeOSPFv3</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">interface</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the interface name from which you want to remove ospfv3</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV3Routes</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV3Database</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV3Neighbors</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showSpanningTreeMstConfig</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">getBridgeMac</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mstp, rstp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the mst instance value, if applicable</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">getSpanningTreeRootPathCost</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">stp, rstp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan. so this is the vlan id that we want to query with regards to spanning tree root path cost</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showSpanningTreeInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mstp, rstp, stp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the mst instance value, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">intName</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">interface name</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree instance for each vlan. so this is the vlan id that we want to query with regards to spanning tree information</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showMacInAddressTable</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mac</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mac address to find in the address table, i.e. 0000.0100.0000</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showLAG</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel id to be queried</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removeLAG</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel id to be queried</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addPortToLAG</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port name that will be added to the LAG</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel id (the LAG interface) to which a port will be added</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">active or static</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showLACPInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel id to be queried</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port to be queried</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setLacpTimeout</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel that we want to configure</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">timeOutValue</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">LONG or SHORT</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addLAGPortToVlan</div>

<div class="procText">For some routers, one must add both the interfaces and the port-channel into a vlan. Other routers just require the port-channel to be added.</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">port name for example: Te0/17</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">access or trunk basically, tagged or untagged</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vlan ID to assign</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel name decimal value, i.e. 25 (to indicate po25)</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showSystemId</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">getLldpLocalPortId</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">intName</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">interface name</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showLldpNeighborsFromInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">intName</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the local interface where we see lldp neighbors</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupLLDP</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">interface where lldp is to be configured</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">enableIpRouting</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipVersion</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">IP version (values are 4 or 6)</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setSpanningTreeTimers</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">stp, rstp, mstp, pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">forwardDelay</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">set the forward delay for the spanning tree</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">helloTime</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">set the hello Time for the spanning tree</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">maxAge</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">set the max age for the spanning tree</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mst instance, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vlan ID, if using PVST</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showSpanningTreeRootTimers</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">pvst</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">msti</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">mst instance, if applicable</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vlan ID, if applicable</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showInterfacesStatus</div>

<div class="header2Text">project://Cisco/session_profiles/CiscoNexus_Telnet_Quickcalls.fftc (project://Cisco/session_profiles/CiscoNexus_Telnet_Quickcalls.fftc)</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">main</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">checkBPDUs</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">edge</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupVlan</div>

<div class="procText">creates the vlan adds the interface to the newly created vlan (access or trunk mode)</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">protocolFamily</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">valid values are: ethernet-switching, inet</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">changeLAG</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">action</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">addLAG_S - add port-channel removeLAG_S - remove port-channel addPort - add port to port-channel removePort - remove port from port channel addLAG_Lacp - add port-channel Lacp removeLAG_Lacp - remove port-channel Lacp addPort_Lacp - add port to port-channel Lacp removePort_Lacp - remove port from port channel Lacp</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">lag</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">checkEtherchannel</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">state</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">member</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">lag</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showLLDP</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mode</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">changeMSTRegionName</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">name</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">checkTrafficBalancing</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">session</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port1</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port2</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setPortMTU</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port name, i.e., Eth3/10/1</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">mtu</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the desired MTU to be used on a system-wide basis values are 1500 - 9216</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">clearMacAddressTable</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">type</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">dynamic is the only choice</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">login</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">user</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">pass</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">terminalAccess</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">vty or tty vty means virtual terminal like ssh or telnet tty means physical terminal like the device console</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">ping</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">target</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipVersion</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">4 or 6</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">numTrialPings</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">number of 'trial' pings to perform before taking an actual frameloss measurement integer, usually 0 or 1</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removeOSPFv2</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removeOSPFv3</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">interface</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the interface name from which you want to remove ospfv3</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupOspfV3</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">processId</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">routerId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the 4 byte ip address used for this router as its router id</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV2Neighbors</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV2Routes</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addBgpNeighbor</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">localAs</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The local AS, the AS of this router</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">neighborIp</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The IPv4 address of the neighbor to be added</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">neighborAs</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The AS of the neighbor to be added</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">md5Password</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showIGMPQuerierAddress</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The VLAN ID where IGMP querier is running</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupIGMPQuerier</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">vlan</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the vlan you want to enable igmp querier on</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">ipAddress</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the ip address you want to the igmp querier function to use</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV3Database</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV3Neighbors</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showOspfV3Routes</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">addSubnetToOspfV3</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">processId</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">linkName</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">area</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">removeBGPv4</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">AS</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">The BGP AS</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showLACPInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel id to be queried</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port to be queried</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setLacpTimeout</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel that we want to configure</td>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">timeOutValue</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">LONG or SHORT</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showLAG</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">portChannelId</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the port channel id to be queried</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showLldpNeighborsFromInterface</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">intName</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">the local interface where we see lldp neighbors</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">setupLLDP</div>

<div class="normalText">

<table style="margin-left:35px; width=600px">

<tbody>

<tr>

<th style="width:200px; padding:5px;color:darkblue;" class="normalText">Argument</th>

<th style="width:400px; padding:5px;color:darkblue;" class="normalText">Description</th>

</tr>

<tr>

<td style="width:200px; padding:5px;color:darkblue" class="normalText">port</td>

<td style="width:400px; padding:5px;color:darkblue" class="normalText">interface where lldp is to be configured</td>

</tr>

</tbody>

</table>

</div>

<div style="margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier">showSystemId</div>

<div class="normalText">Created on: Monday November 06 2017 10:03:28 CST</div>
