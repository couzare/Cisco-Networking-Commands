# Cisco-Networking-Commands
Cisco Networking Commands

A '>' indicates the start of a new command line.

# ROUTER COMMANDS

### >CONFIGURE (Router)

>accept-lifetime start-time [ duration duration value | infinite | end-time ]
>no accept-lifetime start-time [ duration duration value | infinite | end-time ]


>ip access-class access-list-name {in | out}
>no ip access-class access-list-name {in | out}


>ip access-list {standard | extended} name
>no ip access-list name


>auto-cost reference-bandwidth bandwidth [ gbps | mbps ]
>no auto-cost reference-bandwidth


>auto-summary
>no auto-summary


>bandwidth { kbps | inherit [ kbps ]}


>boot system


>cdp enable


>clock rate bps


>clock timezone zone hours-offset


>config-register value


>crypto key generate rsa [ general-keys | usage-keys | signature | encryption ] [ label key-label ] [exportable] [ modulus modulus-size ] [ storage devicename : ] [redundancy] [ on devicename : ]


>channel-group number mode {active | on | passive}


>default-router address [address2 ... address8]


>description description


>ip dns-server


>domain-name domain


>duplex {auto | full | half}


>enable password pass-value


>enable secret pass-value


>encapsulation dot1q command


>End


>Exit


>history size number-of-lines
>no history size


>hostname name


>icmp-echo {destination-ip-address | destination-hostname} [source-ip {ip-address | hostname} | source-interface interface-name]


>interface {FastEthernet|GigabitEhternet} {portnumber}


>ip access-group access-list-name {in | out}
>no ip access-group access-list-name {in | out}


>access-list access-list-number {permit | deny}
{host | source source-wildcard | any}


>ip address ip-address mask
>no ip address


>ip authentication key-chain eigrp autonomous-system key-chain


>ip authentication mode eigrp, autonomous-system md5


>ip classless {default}


>ip default-network ip-address


>ip dhcp pool name


>ip domain-lookup


>ip domain-name dns-server-domain-name


>no ip domain-name


>ip host name address1 [address2... address6]
>no ip host name address1 [address2... address6]


>ip name-server ip-address


>ip nat {inside | outside}


>ip nat inside source static local-ip global-ip


>ip nat pool name start-ip end-ip prefix-length prefix-length [accounting method-list-name] [arp-ping]


>ip ospf authentication [key-chain key-name | message-digest | null]
>no ip ospf authentication


>ip ospf authentication-key [0 | 3 | 7] password
>no ip ospf authentication-key


>ip ospf cost interface-cost
>no ip ospf cost interface-cost


>ip ospf dead-interval seconds


>ip ospf hello-interval seconds


>ip ospf message-digest-key key-id md5 [ 0 | 3 | 7 ] key
>no ip ospf message-digest-key key-id


>ipv6 ospf network {broadcast | non-broadcast | {point-to-multipoint [non-broadcast] | point-to-point}}
>no ipv6 ospf network


>ipv6 ospf priority number-value
>no ipv6 ospf priority number-value


>ip route{network} {mask} {next hop}


>ip ssh version [1 | 2]
>no ip ssh version [1 | 2]


>ip subnet-zero


>ipv6 enable
>no ipv6 enable


>host group profile-name no host group profile-name


>ipv6 ospf process-id area area-id [instance instance-id]
>no ipv6 ospf process-id area area-id [instance instance-id]


>ipv6 ospf dead-interval seconds
>no ipv6 ospf dead-interval


>ipv6 ospf hello-interval seconds
>no ipv6 ospf hello-interval


>ipv6 ospf priority number-value
>no ipv6 ospf priority number-value


>ipv6 route destination-prefix/prefix-length {next-hop-address|next-hop-interface next-hop-linklocal-address} [distance]
>no ipv6 route destination-prefix/prefix-length {next-hop-address|next-hop-interface next-hop-linklocal-address} [distance]


>ip route prefix mask {address | interface} [distance] [tag tag] [permanent]
>no ip route prefix mask


>ipv6 router ospf process-id


>ipv6 traffic-filter access-list-name {in | out}
>no ipv6 traffic-filter access-list-name


>ipv6 unicast-routing
>no ipv6 unicast-routing


>keepalive seconds


>key key-id
>no key key-id


>key chain name-of-chain
>no key chain name-of-chain


>key-string text
>no key-string [text]


>lease {days [hours][minutes] | infinite}
>no lease


>line [aux | console | tty | vty ] line-number [ending-line-number]


>line [vty ] line-number [ending-line-number]


>lldp receive


>lldp run


>lldp transmit


>login local


>logging buffered [buffer-size | level]
>no logging buffered


>default logging buffered


>logging host-name
>no logging host-name


>maximum-paths maximum
>no maximum-paths


>monitor session session_number {destination {interface interface-id [encapsulation {dot1q}] | remote vlan vlan-id reflector-port interface-id} | source {interface interface-id [, | -] [both | rx | tx ] | remote vlan vlan-id}}


>neighbor {ipv4-address | ipv6-address} translate-update multicast [unicast]
>no neighbor {ipv4-address | ipv6-address} translate-update multicast [unicast]


>network ipv6-address/prefix-length
>no network ipv6-address/prefix-length


>ntp master [ stratum ]


>ntp peer ip-address [version number] [key keyed] [source interface] [prefer]
>no ntp peer ip-address


>ntp server ip-address [version number] [key keyed] [source interface] [prefer]
>no ntp server ip-address


>passive-interface [default | interface-type interface-number]
>no passive-interface [default | interface-type interface-number]


>password password


>ppp authentication chap


>remark text-string
>no remark text-string


>router-id router-id
>no router-id router-id


>router ospfv3 [process-id]


>send-lifetime [local] start-time duration duration-value | infinite | end-time]


>service timestamps type [uptime]
>service timestamps type datetime [msec] [localtime] [show-timezone]
>no service timestamps type


>key-string text
>no key-string [text]


>speed {100 | 1000 | 10000 | auto}


>standby [group-number] ipv6 {ipv6-global-address | ipv6-address /prefix-length | ipv6-prefix /prefix-length | link-local-address | autoconfig}
>no standby [group-number] ipv6 {ipv6-global-address | ipv6-address /prefix-length | ipv6-prefix /prefix-length | link-local-address | autoconfig}


>track object-id interface interface-type number {ip routing | line-protocol}
>no track object-id [force]


>transport input {all | lat | mop | nasi | none | pad | rlogin | ssh | telnet | v120}no transport input


>username name password password


>variance {value}


>version {1 | 2}
>no version {1 | 2}


>clear ip dhcp binding {address | *}


>clear ip nat translation


>clear logging


>clock set hh:mm:ss day month year


>clock set hh:mm:ss month day year


>configure terminal


>enable
>copy running-config startup-config


>enable
>copy startup-config running-config


>copy tftp flash


>debug ip ospf { events | packet }
>no debug ip ospf { events | packet }


>debug ppp {packet | negotiation | error | authentication | compression | cbcp}
>no debug ppp {packet | negotiation | error | authentication | compression | cbcp}


>disable [level]


>disconnect [connection]


>enable [privilege-level]


>erase {filesystem:| start-up config}


>ping [protocol] {ip-address | hostname}

>reload [text | in [hh:]mm [text] | at hh:mm [month day | day month] [text] | cancel]


>resume {number}


>Setup


### >telnet {host} [port] [keyword]


>terminal history size number-of-linesno terminal history size


>configure terminal


>table-map map-name


>no table-map map-name


>Traceroute


>undebug all


>verify/md5 filesystem:filename


>write [ erase | memory | network | terminal | ]


>confreg [value]


>write erase


### >SHOW (Router)


>show ip access-list [access-list-number | access-list-name]


>show arp vrf vrf-name [traffic] [ ip-address | hardware-address | interface-path-id ] [traffic] location node-id


>show cdp


>show cdp entry {* | entry-name [protocol | version]}


>show cdp interface [type number]


>show cdp neighbors [type number] [detail]


>show cdp traffic


>show clock [detail]


>show controllers serial [number] (2500 series)


>show etherchannel [summary | load-balance | port-channel]


>show flash


>show history


>show hosts


>show interfaces {type number}


>show run interface tunnel 1


>show ip access-lists [access-list-name]


>show ip arp [ip-address] [hostname] [mac-address] [type number]


>show ip cache [prefix mask] [type number]


>show ip dhcp { binding [address] | conflict [address] |database [url] | server statistics }


>show ip dns source-interface [ vrf { vrf-name | all | default | management }]


>show ip interface interface-type number


>show ip interface brief


>show ip nat statistics


>show ip nat translations [verbose]


>show ip ospf { [ process-id ] | border-routers | database | interface | virtual-links }


>show ospfv3 [process-id [area-id] ] [address-family] [vrf {vrf-name | *}]database [database-summary | internal | external [ipv6-prefix] [link-state-id] ] | grace | inter-area prefix [ipv6-prefix | link-state-id] | inter-area router [destination-router-id | link-state-id] | link [interface interface-name | link-state-id] | network [link-state-id] | nssa-external [ipv6-prefix] [link-state-id] | prefix [ref-lsa {router | network} | link-state-id] | promiscuous | router [link-state-id] | unknown [ {area | as | link} [link-state-id] ] [adv-router router-id] [self-originate]}


>show ospfv3 [process-id] [area-id] [address-family] [vrf {vrf-name | *}]interface [type number] [brief]


>show ospfv3 [process-id] [area-id] [address-family] [vrf {vrf-name | *}] neighbor [interface-type interface-number] [neighbor-id] [detail][ summary [ per-instance] ]


>show ip protocols


>show ip route [ address[ mask] [ longer-prefixes]] | [ protocol[ process-id]] | [ list access-list-number| access-list-name]


>show ip route [address [mask] [longer-prefixes]] | [protocol [process-id]]


>show ipv6 eigrp [as-number] interfaces [type number] [detail]


>show ipv6 eigrp neighbors [interface-type | as-number |static | detail]


>show ipv6 route [ipv6-address | ipv6-prefix/prefix-length [longer-prefixes] | [protocol] | [ repair] | [updated [boot-up] [day month] [time]] | interface type number | nd | nsf | table table-id | watch]


>show router ospf process-id


>show ipv6 protocols [summary]


>show logging [history]


>show monitor [session {session_number | all |local | range | remote}] [ | {begin |exclude | include} expression]


>show lldp {interface {ethernet slot/port | mgmt. intf-no} | neighbors [detail | interface]}


>show ntp status


>show processes [cpu]


>show running-config


>show sessions


>show standby [type number [group]] [brief]


>show startup-config


>show version


>show vlan [brief | id vlan-id | name name [ifindex] | ifindex]


>show ssh


>show ip ospf process-id rib [redistribution] [network-prefix] [network-mask] [detai]


>Rommon


>Rommon (Router)


>confreg


>reset



======================================================================================================================================================================



# SWITCH COMMANDS


### >CONFIGURE (Switch)


>cdp enable


>End


>Exit


>lldp receive
>lldp run
>lldp transmit


>login local


>configure terminal
>no cdp enable


>cdp run
>no cdp run


>channel-group {channel-group number} [ mode { active | on | passive }]
>no channel-group {channel-group number} [ mode { active | on | passive }]


>crypto key generate rsa
>no crypto key generate rsa


>description description
>no description


>duplex { full | half | auto }
>no duplex { full | half | auto }


>enable password password
>no enable password


>enable secret secret
>no enable secret


>history size {0-256}


>hostname name
>no hostname


>interface type slot/port-adapter
>no interface type slot/port-adapter


>ip address {ip-address} {subnetmask}
>no ip address {ip-address} {subnetmask}


>ip default-gateway {ip address}
>no ip default-gateway {ip-address}


>ip domain-name domain-name [use-vrf name]
>no ip domain-name domain-name [use-vrf name]


### >ip ssh version [ 1 | 2 ]
### >no ip ssh version [ 1 | 2 ]


>ip routing


>ipv6 route ipv6-prefix / prefix-length ipv6-address | interface-type interface-number ipv6-address ]} [administrative-distance ] [administrative-multicast-distance | unicast | multicast ] [tag tag ]
line [aux | console | vty] line-number [ending-line-number]


>no lldp receive


>no lldp run


>no lldp transmit


>Login
>no login
>no login local


>name vlan-name
>no name


>no enable secret password


>sdm prefer { default | dual-ipv4-and-ipv6 | lanbaserouting }


>Shutdown
>no shutdown


>spanning-tree bpduguard { enable | disable }


>spanning-tree vlan vlan-id{root {primary |secondary}
>no spanning-tree vlan vlan-id{root {primary |secondary}


>panning-tree vlan vlan-id cost { 1 – 200000000}
>no spanning-tree vlan vlan-id cost {cost value 1 – 200000000}


>spanning-tree portfast default
>no spanning-tree portfast {bpduguard} default


>spanning-tree portfast disable


>spantree portfast bpdu-guard default
>no spantree portfast bpdu-guard default


>speed { 100 | 1000 | 10000 | auto }
>no speed


>switchport access vlan vlan-id
>no switchport access vlan


>switchport mode {access | trunk | dynamic {auto | desirable}}
>no switchport mode {access | trunk }


>switchport port-security
>no switchport port-security


>switchport port-security mac-address {mac-address }
>no switchport port-security mac-address {mac-address }


>switchport port-security mac-address sticky
>no switchport port-security mac-address sticky


>switchport port-security maximum max-addr [ vlan vlan-ID ]


>switchport port-security violation { protect | restrict | shutdown }


>switchport trunk allowed vlan {vlan-list | {add | all | except | remove} vlan-list | none}
>no switchport trunk allowed vlan {vlan-list | {add | all | except | remove} vlan-list | none}


>switchport voice vlan { vlan-list | dot1p | untagged }
>no switchport voice vlan


>transport input {telnet |ssh} [telnet |ssh]
>no transport input


>username {name} password {password}
>no username user-id


>name vlan-name


>ip route {ipaddress} {subnet mask} {next hop ip address }


### >copy running-config startup-config


### >copy startup-config running-config


>Disable


>Enable


>erase startup-config


>exit


### >ping {host | address}


>Reload


>resume {session number }


### >ssh -l [username]{ipv4-address | hostname}]


>domain-name domain


>write erase


### >SHOW (Switch)


>show cdp


>show cdp traffic


>show running-config


>show startup-config


>show sdm prefer [ default | dual-ipv4-and-ipv6 default | lanbase-routing]


>show cdp entry {* | entry-name [protocol | version]}


>show cdp interface [type number]


>show cdp neighbors [type number] [detail]


>show controller


>show crypto key mypubkey rsa


>show flash


>show history


>show interfaces {type number}


>show ip arp


>show ip interface brief [brief]


>show ip route [address[ mask] [ longer-prefixes ]


>show lldp {interface {ethernet slot/port} | neighbors [detail | interface]}


>show lldp entry entry-name


>show lldp {interface {ethernet slot/port | mgmt intf-no} | neighbors [detail | interface] | timers | traffic [interface {ethernet slot/port | mgmt intf-no}]}


>show lldp neighbour


>show lldp neighbour detail


>show mac-address-table [dynamic | static] [address mac-addr]
[interface interface-id] [vlan vlan-id] [address mac-address]


>show port-security [address | interface interface]


>show sessions


>show spanning-tree


>show spanning-tree interface portfast


>show spanning-tree vlan {vlan-id}


>show spanning-tree vlan {vlan-id} [bridge [address] | brief | detail ]


>show spanning-tree vlan {vlan-id} [active [brief | detail]]


>show version


>show vlan id vlan-id


>show vlan [ brief | name { name } | summary ]



======================================================================================================================================================================



## PC COMMANDS


# >CONFIGURE (PC)


>gateway ip-address


>ip address {network mask | dhcp}


>ipv6 address {autoconfig | ipv6-prefix/prefix-length}


>ipv6 gateway ipv6-prefix


>mac-address mac-address


### >EXEC (PC)


>ping ip-address


>tracert ip-address


>ipconfig /renew


>ipconfig /release


### >SHOW (PC)


>arp -a


>ipconfig /all
