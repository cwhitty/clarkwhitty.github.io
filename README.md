<HTML><BODY>
<style>TABLE,TD,TH{border:1px solid black;border-collapse:collapse;}
th{text-align:left;background-color:AliceBlue;}
H1,H2{padding-left:15px}
.smallText{font-size:10px; color:black; font-family:courier}
.normalText{font-size:14px; color:black; font-family:arial}
.procText{font-size:14px; color:black; font-family:arial; padding-left:35px}
.headerText{font-size:30px; color:black; font-weight:bold; font-family:arial ;text-align:left; padding-left:5px}
.header2Text{font-size:20px; color:darkblue; font-weight:bold; font-family:arial ;text-align:left; padding-left:5px}
.header3Text{font-size:18px; color:darkblue; font-weight:bold; font-family:arial ;text-align:left; padding-left:10px}
</style>
<BR><DIV class='headerText'>project://Cisco</DIV>
*<BR><DIV class='header2Text'>3 QuickCall Libraries in project://Cisco:</DIV>*
<BR><DIV class='header2Text'>project://Cisco/session_profiles/7009.fftc (project://Cisco/session_profiles/7009.fftc)</DIV>
<DIV style='margin-left:35px; font-size:12px;color:black; font-family:arial'></DIV>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>main</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setVlanIpAddress</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlanId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipAddr</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mask</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<br>
<BR><DIV class='header2Text'>project://Cisco/session_profiles/CiscoIOS_Telnet_Quickcalls.fftc (project://Cisco/session_profiles/CiscoIOS_Telnet_Quickcalls.fftc)</DIV>
<DIV style='margin-left:35px; font-size:12px;color:black; font-family:arial'>looks like getConnectedVlans could use some work</DIV>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>main</DIV>
<DIV class='procText'>creates the vlan
adds the port to the newly created vlan (trunk or access mode)

</DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>login</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>terminalAccess</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vty or tty
vty means virtual terminal like ssh or telnet
tty means physical terminal like the device console </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>startOfProcedure</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>printedMessage1</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>first message to be printed to the console
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showIpTraffic</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removeVlan</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vlan id to remove </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showInterfaces</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addPortToVlan</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>port name 
for example: Te0/17 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>access or trunk
basically, tagged or untagged </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vlan ID to assign </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setPortToDefault</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupVlan</DIV>
<DIV class='procText'>creates the vlan
adds the interface to the newly created vlan (access or trunk mode)
</DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>protocolFamily</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>valid values are: ethernet-switching, inet </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>getConnectedVlans</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removePortFromVlan</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addSubnetToOspfV2</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>processId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>linkName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mask</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>area</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addSubnetToOspfV3</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>processId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>linkName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>area</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupOspfV3</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>processId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>routerId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the 4 byte ip address used for this router as its router id </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setOspfV2CostOnInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>cost</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>intName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the name of the interface on which to set the cost, like Te 0/16 or Vlan132 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupSwitchport</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>protocolFamily</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>valid values are: ethernet-switching, inet </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setVlanIpAddress</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlanId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipAddr</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mask</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setInterfaceIpAddress</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>intName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the name of the interface to which the IP address is assigned
for example: Te0/17, Vlan125 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipAddr</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>IP Address to assign
for example: 10.1.1.1, 2001:125::1 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mask</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>netmask to be applied to the IP address
for example: /24, /64  </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipVersion</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>IP version
values are 4 or 6 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setVlanIpV6Address</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlanId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipAddr</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mask</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addVlanToTrunk</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupSpanningTree</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mstp, rstp, stp, pvst </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mst instance number, if applicable </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vlan id to add to the mst instance, if applicable </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>revision</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mst revision number, if applicable </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setBridgePriority</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>priority</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the bridge priority value used by spanning tree </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>stp, mstp, rstp, pvst
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the mst instance value, if applicable </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>for switches that only do per-vlan stp, like some cisco switches, we need to specify the bridge priority at the vlan level.  so this is the vlan id that we want to affect with regards to spanning tree priority </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>getBridgeId</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>getBridgePriority</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>stp, rstp </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan.  so this is the vlan id that we want to query with regards to spanning tree priority </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>iThinkThisCanBeDeprecatedcheckRootSwitch</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mstp, stp, rstp </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mst instance, if applicable </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan.  so this is the vlan id that we want to query with regards to spanning tree root </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>checkRootSwitch</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mstp, stp, rstp, pvst
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mst instance, if applicable </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan.  so this is the vlan id that we want to query with regards to spanning tree root </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setPathCost</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>cost</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>checkPortState</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>changePortState</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>state</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>checkBPDUs</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>edge</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setPortPriority</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>priority</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the spanning tree port priority  </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>stp, rstp, mstp, pvst </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mst instance, if applicable </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>int</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the interface name on which to apply the port priority i.e., Eth3/10/1
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vlan ID, if applicable </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>changeMSTRegionName</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>name</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setStpToDefault</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mstiList</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>a list of mst instances to remove from the switch, if applicable
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>checkEtherchannel</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>state</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>member</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>lag</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setSpanningTreeInterfaceCost</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>stp, rstp, pvst

 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>intName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>interface name </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>cost</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the spanning tree cost of this interface
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mst instance, if applicable </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vlan id, if applicable </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>checkTrafficBalancing</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port1</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port2</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setPortMTU</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mtu</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>clearMacAddressTable</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>type</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removeOSPFv2</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setOspfV2RouterId</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>routerId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV2Neighbors</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV2Routes</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showRunningConfig</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>ping</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>target</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipVersion</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>4 or 6 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>numTrialPings</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>number of 'trial' pings to perform before taking an actual frameloss measurement
integer, usually 0 or 1 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>shutdownInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>interface</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the interface that you want to shutdown </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>enableInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>interface</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the interface that you want to no shut </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupIGMPQuerier</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the vlan you want to enable igmp querier on </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipAddress</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the ip address you want to the igmp querier function to use </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showIGMPQuerierAddress</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The VLAN ID where IGMP querier is running </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showIGMPGroups</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addBgpNeighbor</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>localAs</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The local AS, the AS of this router </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>neighborIp</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The IPv4 address of the neighbor to be added </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>neighborAs</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The AS of the neighbor to be added </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>md5Password</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removeBGPv4</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>AS</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The BGP AS </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showBgpNeighbors</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>specificNeighborIpAddr</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>if given, we show the status for this specific neighbor, otherwise we show them all </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showBgpRoutes</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>path</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>you can pass a path into this proc, and the proc will return how many routes contain that path </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>nextHop</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>you can pass a nextHop into this proc, and the proc will return how many routes are using that next hop </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>interface</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the name of the interface
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showVersion</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removeOSPFv3</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>interface</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the interface name from which you want to remove ospfv3 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV3Routes</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV3Database</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV3Neighbors</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showSpanningTreeMstConfig</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>getBridgeMac</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mstp, rstp, pvst </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the mst instance value, if applicable

 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>getSpanningTreeRootPathCost</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>stp, rstp, pvst </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree root for each vlan.  so this is the vlan id that we want to query with regards to spanning tree root path cost </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showSpanningTreeInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mstp, rstp, stp, pvst
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the mst instance value, if applicable
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>intName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>interface name </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>for switches that only do per-vlan stp, like some cisco switches, there is a spanning tree instance for each vlan.  so this is the vlan id that we want to query with regards to spanning tree information </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showMacInAddressTable</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mac</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mac address to find in the address table, i.e. 0000.0100.0000
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showLAG</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel id to be queried </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removeLAG</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel id  to be queried </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addPortToLAG</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port name that will be added to the LAG </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel id (the LAG interface) to which a port will be added
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>active or static
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showLACPInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel id to be queried </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port to be queried </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setLacpTimeout</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel that we want to configure
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>timeOutValue</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>LONG or SHORT
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addLAGPortToVlan</DIV>
<DIV class='procText'>For some routers, one must add both the interfaces and the port-channel into a vlan.  Other routers just require the port-channel to be added.</DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>port name 
for example: Te0/17 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>access or trunk
basically, tagged or untagged </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vlan ID to assign </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel name decimal value, i.e. 25 (to indicate po25) </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showSystemId</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>getLldpLocalPortId</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>intName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>interface name
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showLldpNeighborsFromInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>intName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the local interface where we see lldp neighbors
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupLLDP</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>interface where lldp is to be configured </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>enableIpRouting</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipVersion</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>IP version (values are 4 or 6) </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setSpanningTreeTimers</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>stp, rstp, mstp, pvst
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>forwardDelay</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>set the forward delay for the spanning tree </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>helloTime</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>set the hello Time for the spanning tree </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>maxAge</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>set the max age for the spanning tree </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mst instance, if applicable
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vlan ID, if using PVST </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showSpanningTreeRootTimers</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>pvst
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>msti</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>mst instance, if applicable </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vlan ID, if applicable
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showInterfacesStatus</DIV>
<DIV class='procText'></DIV><BR>
<br>
<BR><DIV class='header2Text'>project://Cisco/session_profiles/CiscoNexus_Telnet_Quickcalls.fftc (project://Cisco/session_profiles/CiscoNexus_Telnet_Quickcalls.fftc)</DIV>
<DIV style='margin-left:35px; font-size:12px;color:black; font-family:arial'></DIV>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>main</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>checkBPDUs</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>edge</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupVlan</DIV>
<DIV class='procText'>creates the vlan
adds the interface to the newly created vlan (access or trunk mode)
</DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>protocolFamily</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>valid values are: ethernet-switching, inet </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>changeLAG</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>action</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>addLAG_S - add port-channel
removeLAG_S - remove port-channel
addPort - add port to port-channel
removePort - remove port from port channel
addLAG_Lacp - add port-channel Lacp
removeLAG_Lacp - remove port-channel Lacp
addPort_Lacp - add port to port-channel Lacp
removePort_Lacp - remove port from port channel Lacp </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>lag</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>checkEtherchannel</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>state</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>member</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>lag</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showLLDP</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mode</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>changeMSTRegionName</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>name</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>checkTrafficBalancing</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>session</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port1</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port2</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setPortMTU</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port name, i.e., Eth3/10/1 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>mtu</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the desired MTU to be used on a system-wide basis
values are 1500 - 9216 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>clearMacAddressTable</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>type</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>dynamic is the only choice </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>login</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>user</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>pass</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>terminalAccess</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>vty or tty
vty means virtual terminal like ssh or telnet
tty means physical terminal like the device console </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>ping</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>target</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipVersion</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>4 or 6 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>numTrialPings</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>number of 'trial' pings to perform before taking an actual frameloss measurement
integer, usually 0 or 1 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removeOSPFv2</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removeOSPFv3</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>interface</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the interface name from which you want to remove ospfv3 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupOspfV3</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>processId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>routerId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the 4 byte ip address used for this router as its router id </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV2Neighbors</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV2Routes</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addBgpNeighbor</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>localAs</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The local AS, the AS of this router </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>neighborIp</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The IPv4 address of the neighbor to be added </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>neighborAs</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The AS of the neighbor to be added </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>md5Password</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showIGMPQuerierAddress</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The VLAN ID where IGMP querier is running </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupIGMPQuerier</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>vlan</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the vlan you want to enable igmp querier on </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>ipAddress</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the ip address you want to the igmp querier function to use </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV3Database</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV3Neighbors</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showOspfV3Routes</DIV>
<DIV class='procText'></DIV><BR>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>addSubnetToOspfV3</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>processId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>linkName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>area</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'> </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>removeBGPv4</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>AS</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>The BGP AS </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showLACPInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel id to be queried </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port to be queried </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setLacpTimeout</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel that we want to configure
 </TD>
</TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>timeOutValue</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>LONG or SHORT
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showLAG</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>portChannelId</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the port channel id to be queried </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showLldpNeighborsFromInterface</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>intName</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>the local interface where we see lldp neighbors
 </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>setupLLDP</DIV>
<DIV class='procText'></DIV><BR>
<DIV class='normalText'><TABLE style='margin-left:35px; width=600px'>
<TR><TH style='width:200px; padding:5px;color:darkblue;' class='normalText'>Argument</TH>
<TH style='width:400px; padding:5px;color:darkblue;' class='normalText'>Description</TH></TR>
<TR><TD style='width:200px; padding:5px;color:darkblue' class='normalText'>port</TD>
<TD style='width:400px; padding:5px;color:darkblue' class='normalText'>interface where lldp is to be configured </TD>
</TR>
</TABLE></DIV><br>
<DIV style='margin-left:30px; font-size:18px;color:darkgreen;font-weight:bold; font-family:courier'>showSystemId</DIV>
<DIV class='procText'></DIV><BR>
<br>
<DIV class='normalText'>Created on: Monday November 06 2017 10:03:28 CST</DIV></BODY></HTML>
