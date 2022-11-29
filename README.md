# 🧰 IPv6 Utils

IPv6 utils is a useful toolkit for people doing IPv6 networking.

## Formatting & identification

A hexadecimal number can have 16 different values (from 0 to 9 and from A to F), which corresponds to exactly 4 bits. As each group is composed of four hexadecimal numbers, each group has 16 bits:

```
 16   32   48   64   80   96  112  128
 |    |    |    |    |    |    |    |
2a0e:a4eb:b50:000c:57f3:03f9:41f4:5533
```

IPv6 addresses can be used in different formats:

**Uncompressed:**
2a0e:a4eb:b50:**000**c:57f3:**0**3f9:41f4:5533

**Compressed:**
2a0e:a4eb:b50:c:57f3:3f9:41f4:5533

Examples of network ranges (All areas in bold are free and usable):

- 2001:db8:1ee::/48 (65,536 networks /64):

  - First address: 2001:db8:1ee:**0000:0000:0000:0000:0000**
  - Last address: 2001:db8:1ee:**ffff:ffff:ffff:ffff:ffff**

- 2001:db8:1ee::/44 (1,048,576 networks /64):
  - First address: 2001:db8:1e**0:0000:0000:0000:0000:0000**
  - Last address: 2001:db8:1e**f:ffff:ffff:ffff:ffff:ffff**

## Free tunnel brokers

- https://tunnelbroker.net/ (multiple locations)
- https://tb.netassist.ua/ (BGP only, Ukraine)
- https://tunnelbroker.ch/ (BGP enabled, Switzerland/Germany/Netherlands)
- https://route48.org/ (BGP enabled, multiple locations, cannot use external prefixes)
- https://www.route64.org/ (BGP enabled, multiple locations)
- https://august.tw/ (BGP only, Canada, no routes to greater China (HK, CN, Macao) and North Korea)

## Prefix providers

- https://securebit.ch/
- https://dyjix.eu/
- https://lir.services/
- https://ifog.ch/
- https://bakker-it.eu/
- https://flokinet.is/
- https://myroot.pw/
- https://ip6.im
- https://hostus.us/
- https://freerangecloud.com/
- https://snapserv.net/
- https://servperso.net/
- https://route48.org/
- https://august.tw/ 
- and many others ..

## Debug tools

- https://mtr.tools/
- https://bgp.tools
- https://ping.pe/

## Looking glasses

### Tier 1

- https://lg.as6453.net/bin/lg.cgi
- https://www.cogentco.com/en/looking-glass
- https://lookingglass.centurylink.com
- http://www.as3257.net/lg
- https://lg.as6453.net/bin/lg.cgi
- https://www.sprint.net/tools/looking-glass
- http://lg.zayo.com/lg.cgi
- https://lg.opentransit.net
- http://lg.telia.net
- https://gambadilegno.noc.seabone.net/lg
- https://www.gin.ntt.net/looking-glass
- https://lookingglass.telekom.com
- https://lg.twelve99.net/

### Others

- https://lg.ovh.net
- https://www.pch.net/tools/looking_glass
- https://lg.as213045.net
- https://www.as58057.net
- https://lg.retn.net
- https://lg.hivane.net
- https://www.as13030.net/looking-glass.php
- http://lg.core-backbone.com
- http://lg.as8218.eu
- https://lg.grenode.net
- https://lg.shadow.tech
- https://lg.ch.as1836.net/lg
- http://lg.hopus.net
- https://lg.globenet.net/lg/lg.cgi
- https://lg.eastlink.ca
- https://webadmin.oxymium.net/mrlg
- https://lg.de-cix.net
- https://as41103.net/cgi-bin/bgplg
- http://www.atlantis.bg/?id=18
- https://lg.tetaneutral.net
- http://lg.as60362.net
- https://portal.spilsby.net.uk/lg
- https://lg.a2b-internet.com
- https://lg.anexia-it.com/lg
- http://lg.avelacom.ru

## List of subnets with CIDR

<table>
              <thead>
                <tr>
                  <th>CIDR</th>
                  <th>Number of networks/addresses</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>/1</td>
                  <td>9,223,372,036,854,775,808 networks /64</td>
                </tr>
                <tr>
                  <td>/2</td>
                  <td>4,611,686,018,427,387,904 networks /64</td>
                </tr>
                <tr>
                  <td>/3</td>
                  <td>2,305,843,009,213,693,952 networks /64</td>
                </tr>
                <tr>
                  <td>/4</td>
                  <td>1,152,921,504,606,846,976 networks /64</td>
                </tr>
                <tr>
                  <td>/5</td>
                  <td>576,460,752,303,423,488 networks /64</td>
                </tr>
                <tr>
                  <td>/6</td>
                  <td>288,230,376,151,711,744 networks /64</td>
                </tr>
                <tr>
                  <td>/7</td>
                  <td>144,115,188,075,855,872 networks /64</td>
                </tr>
                <tr>
                  <td>/8</td>
                  <td>72,057,594,037,927,936 networks /64</td>
                </tr>
                <tr>
                  <td>/9</td>
                  <td>36,028,797,018,963,968 networks /64</td>
                </tr>
                <tr>
                  <td>/10</td>
                  <td>18,014,398,509,481,984 networks /64</td>
                </tr>
                <tr>
                  <td>/11</td>
                  <td>9,007,199,254,740,992 networks /64</td>
                </tr>
                <tr>
                  <td>/12</td>
                  <td>4,503,599,627,370,496 networks /64</td>
                </tr>
                <tr>
                  <td>/13</td>
                  <td>2,251,799,813,685,248 networks /64</td>
                </tr>
                <tr>
                  <td>/14</td>
                  <td>1,125,899,906,842,624 networks /64</td>
                </tr>
                <tr>
                  <td>/15</td>
                  <td>562,949,953,421,312 networks /64</td>
                </tr>
                <tr>
                  <td>/16</td>
                  <td>281,474,976,710,656 networks /64</td>
                </tr>
                <tr>
                  <td>/17</td>
                  <td>140,737,488,355,328 networks /64</td>
                </tr>
                <tr>
                  <td>/18</td>
                  <td>70,368,744,177,664 networks /64</td>
                </tr>
                <tr>
                  <td>/19</td>
                  <td>35,184,372,088,832 networks /64</td>
                </tr>
                <tr>
                  <td>/20</td>
                  <td>17,592,186,044,416 networks /64</td>
                </tr>
                <tr>
                  <td>/21</td>
                  <td>8,796,093,022,208 networks /64</td>
                </tr>
                <tr>
                  <td>/22</td>
                  <td>4,398,046,511,104 networks /64</td>
                </tr>
                <tr>
                  <td>/23</td>
                  <td>2,199,023,255,552 networks /64</td>
                </tr>
                <tr>
                  <td>/24</td>
                  <td>1,099,511,627,776 networks /64</td>
                </tr>
                <tr>
                  <td>/25</td>
                  <td>549,755,813,888 networks /64</td>
                </tr>
                <tr>
                  <td>/26</td>
                  <td>274,877,906,944 networks /64</td>
                </tr>
                <tr>
                  <td>/27</td>
                  <td>137,438,953,472 networks /64</td>
                </tr>
                <tr>
                  <td>/28</td>
                  <td>68,719,476,736 networks /64</td>
                </tr>
                <tr>
                  <td>/29</td>
                  <td>34,359,738,368 networks /64</td>
                </tr>
                <tr>
                  <td>/30</td>
                  <td>17,179,869,184 networks /64</td>
                </tr>
                <tr>
                  <td>/31</td>
                  <td>8,589,934,592 networks /64</td>
                </tr>
                <tr>
                  <td>/32</td>
                  <td>4,294,967,296 networks /64</td>
                </tr>
                <tr>
                  <td>/33</td>
                  <td>2,147,483,648 networks /64</td>
                </tr>
                <tr>
                  <td>/34</td>
                  <td>1,073,741,824 networks /64</td>
                </tr>
                <tr>
                  <td>/35</td>
                  <td>536,870,912 networks /64</td>
                </tr>
                <tr>
                  <td>/36</td>
                  <td>268,435,456 networks /64</td>
                </tr>
                <tr>
                  <td>/37</td>
                  <td>134,217,728 networks /64</td>
                </tr>
                <tr>
                  <td>/38</td>
                  <td>67,108,864 networks /64</td>
                </tr>
                <tr>
                  <td>/39</td>
                  <td>33,554,432 networks /64</td>
                </tr>
                <tr>
                  <td>/40</td>
                  <td>16,777,216 networks /64</td>
                </tr>
                <tr>
                  <td>/41</td>
                  <td>8,388,608 networks /64</td>
                </tr>
                <tr>
                  <td>/42</td>
                  <td>4,194,304 networks /64</td>
                </tr>
                <tr>
                  <td>/43</td>
                  <td>2,097,152 networks /64</td>
                </tr>
                <tr>
                  <td>/44</td>
                  <td>1,048,576 networks /64</td>
                </tr>
                <tr>
                  <td>/45</td>
                  <td>524,288 networks /64</td>
                </tr>
                <tr>
                  <td>/46</td>
                  <td>262,144 networks /64</td>
                </tr>
                <tr>
                  <td>/47</td>
                  <td>131,072 networks /64</td>
                </tr>
                <tr>
                  <td>/48</td>
                  <td>65,536 networks /64</td>
                </tr>
                <tr>
                  <td>/49</td>
                  <td>32,768 networks /64</td>
                </tr>
                <tr>
                  <td>/50</td>
                  <td>16,384 networks /64</td>
                </tr>
                <tr>
                  <td>/51</td>
                  <td>8,192 networks /64</td>
                </tr>
                <tr>
                  <td>/52</td>
                  <td>4,096 networks /64</td>
                </tr>
                <tr>
                  <td>/53</td>
                  <td>2,048 networks /64</td>
                </tr>
                <tr>
                  <td>/54</td>
                  <td>1,024 networks /64</td>
                </tr>
                <tr>
                  <td>/55</td>
                  <td>512 networks /64</td>
                </tr>
                <tr>
                  <td>/56</td>
                  <td>256 networks /64</td>
                </tr>
                <tr>
                  <td>/57</td>
                  <td>128 networks /64</td>
                </tr>
                <tr>
                  <td>/58</td>
                  <td>64 networks /64</td>
                </tr>
                <tr>
                  <td>/59</td>
                  <td>32 networks /64</td>
                </tr>
                <tr>
                  <td>/60</td>
                  <td>16 networks /64</td>
                </tr>
                <tr>
                  <td>/61</td>
                  <td>8 networks /64</td>
                </tr>
                <tr>
                  <td>/62</td>
                  <td>4 networks /64</td>
                </tr>
                <tr>
                  <td>/63</td>
                  <td>2 networks /64</td>
                </tr>
                <tr>
                  <td>/64</td>
                  <td>18,446,744,073,709,551,616 addresses</td>
                </tr>
                <tr>
                  <td>/65</td>
                  <td>9,223,372,036,854,775,808 addresses</td>
                </tr>
                <tr>
                  <td>/66</td>
                  <td>4,611,686,018,427,387,904 addresses</td>
                </tr>
                <tr>
                  <td>/67</td>
                  <td>2,305,843,009,213,693,952 addresses</td>
                </tr>
                <tr>
                  <td>/68</td>
                  <td>1,152,921,504,606,846,976 addresses</td>
                </tr>
                <tr>
                  <td>/69</td>
                  <td>576,460,752,303,423,488 addresses</td>
                </tr>
                <tr>
                  <td>/70</td>
                  <td>288,230,376,151,711,744 addresses</td>
                </tr>
                <tr>
                  <td>/71</td>
                  <td>144,115,188,075,855,872 addresses</td>
                </tr>
                <tr>
                  <td>/72</td>
                  <td>72,057,594,037,927,936 addresses</td>
                </tr>
                <tr>
                  <td>/73</td>
                  <td>36,028,797,018,963,968 addresses</td>
                </tr>
                <tr>
                  <td>/74</td>
                  <td>18,014,398,509,481,984 addresses</td>
                </tr>
                <tr>
                  <td>/75</td>
                  <td>9,007,199,254,740,992 addresses</td>
                </tr>
                <tr>
                  <td>/76</td>
                  <td>4,503,599,627,370,496 addresses</td>
                </tr>
                <tr>
                  <td>/77</td>
                  <td>2,251,799,813,685,248 addresses</td>
                </tr>
                <tr>
                  <td>/78</td>
                  <td>1,125,899,906,842,624 addresses</td>
                </tr>
                <tr>
                  <td>/79</td>
                  <td>562,949,953,421,312 addresses</td>
                </tr>
                <tr>
                  <td>/80</td>
                  <td>281,474,976,710,656 addresses</td>
                </tr>
                <tr>
                  <td>/81</td>
                  <td>140,737,488,355,328 addresses</td>
                </tr>
                <tr>
                  <td>/82</td>
                  <td>70,368,744,177,664 addresses</td>
                </tr>
                <tr>
                  <td>/83</td>
                  <td>35,184,372,088,832 addresses</td>
                </tr>
                <tr>
                  <td>/84</td>
                  <td>17,592,186,044,416 addresses</td>
                </tr>
                <tr>
                  <td>/85</td>
                  <td>8,796,093,022,208 addresses</td>
                </tr>
                <tr>
                  <td>/86</td>
                  <td>4,398,046,511,104 addresses</td>
                </tr>
                <tr>
                  <td>/87</td>
                  <td>2,199,023,255,552 addresses</td>
                </tr>
                <tr>
                  <td>/88</td>
                  <td>1,099,511,627,776 addresses</td>
                </tr>
                <tr>
                  <td>/89</td>
                  <td>549,755,813,888 addresses</td>
                </tr>
                <tr>
                  <td>/90</td>
                  <td>274,877,906,944 addresses</td>
                </tr>
                <tr>
                  <td>/91</td>
                  <td>137,438,953,472 addresses</td>
                </tr>
                <tr>
                  <td>/92</td>
                  <td>68,719,476,736 addresses</td>
                </tr>
                <tr>
                  <td>/93</td>
                  <td>34,359,738,368 addresses</td>
                </tr>
                <tr>
                  <td>/94</td>
                  <td>17,179,869,184 addresses</td>
                </tr>
                <tr>
                  <td>/95</td>
                  <td>8,589,934,592 addresses</td>
                </tr>
                <tr>
                  <td>/96</td>
                  <td>4,294,967,296 addresses</td>
                </tr>
                <tr>
                  <td>/97</td>
                  <td>2,147,483,648 addresses</td>
                </tr>
                <tr>
                  <td>/98</td>
                  <td>1,073,741,824 addresses</td>
                </tr>
                <tr>
                  <td>/99</td>
                  <td>536,870,912 addresses</td>
                </tr>
                <tr>
                  <td>/100</td>
                  <td>268,435,456 addresses</td>
                </tr>
                <tr>
                  <td>/101</td>
                  <td>134,217,728 addresses</td>
                </tr>
                <tr>
                  <td>/102</td>
                  <td>67,108,864 addresses</td>
                </tr>
                <tr>
                  <td>/103</td>
                  <td>33,554,432 addresses</td>
                </tr>
                <tr>
                  <td>/104</td>
                  <td>16,777,216 addresses</td>
                </tr>
                <tr>
                  <td>/105</td>
                  <td>8,388,608 addresses</td>
                </tr>
                <tr>
                  <td>/106</td>
                  <td>4,194,304 addresses</td>
                </tr>
                <tr>
                  <td>/107</td>
                  <td>2,097,152 addresses</td>
                </tr>
                <tr>
                  <td>/108</td>
                  <td>1,048,576 addresses</td>
                </tr>
                <tr>
                  <td>/109</td>
                  <td>524,288 addresses</td>
                </tr>
                <tr>
                  <td>/110</td>
                  <td>262,144 addresses</td>
                </tr>
                <tr>
                  <td>/111</td>
                  <td>131,072 addresses</td>
                </tr>
                <tr>
                  <td>/112</td>
                  <td>65,536 addresses</td>
                </tr>
                <tr>
                  <td>/113</td>
                  <td>32,768 addresses</td>
                </tr>
                <tr>
                  <td>/114</td>
                  <td>16,384 addresses</td>
                </tr>
                <tr>
                  <td>/115</td>
                  <td>8,192 addresses</td>
                </tr>
                <tr>
                  <td>/116</td>
                  <td>4,096 addresses</td>
                </tr>
                <tr>
                  <td>/117</td>
                  <td>2,048 addresses</td>
                </tr>
                <tr>
                  <td>/118</td>
                  <td>1,024 addresses</td>
                </tr>
                <tr>
                  <td>/119</td>
                  <td>512 addresses</td>
                </tr>
                <tr>
                  <td>/120</td>
                  <td>256 addresses</td>
                </tr>
                <tr>
                  <td>/121</td>
                  <td>128 addresses</td>
                </tr>
                <tr>
                  <td>/122</td>
                  <td>64 addresses</td>
                </tr>
                <tr>
                  <td>/123</td>
                  <td>32 addresses</td>
                </tr>
                <tr>
                  <td>/124</td>
                  <td>16 addresses</td>
                </tr>
                <tr>
                  <td>/125</td>
                  <td>8 addresses</td>
                </tr>
                <tr>
                  <td>/126</td>
                  <td>4 addresses</td>
                </tr>
                <tr>
                  <td>/127</td>
                  <td>2 addresses</td>
                </tr>
                <tr>
                  <td>/128</td>
                  <td>1 address</td>
                </tr>
              </tbody>
</table>
 
## Type of addresses
<table>
              <thead>
                <tr>
                  <th>Prefix</th>
                  <th>Description</th>
                  <th>IPv4 equivalent</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>::1/128</td>
                  <td>Loopback</td>
                  <td>127.0.0.1</td>
                </tr>
                <tr>
                  <td>fe80::/10</td>
                  <td>Link-Local</td>
                  <td>169.254.0.0/16</td>
                </tr>
                <tr>
                  <td>2000::/3</td>
                  <td>Global Unicast</td>
                  <td></td>
                </tr>
                <tr>
                  <td>fc00::/7</td>
                  <td>Unique Local</td>
                  <td>10.0.0.0/8, 172.16.0.0/12, 192.168.0.0/16</td>
                </tr>
                <tr>
                  <td>ff00::/8</td>
                  <td>Multicast</td>
                  <td>224.0.0.0/4</td>	
                </tr>
                <tr>
                  <td>2001:db8::/32</td>
                  <td>Documentation</td>
                  <td>192.0.2.0/24, 198.51.100.0/24, 203.0.113.0/24</td>
                </tr>
                <tr>
                  <td>::/128</td>
                  <td>Unspecified</td>
                  <td>0.0.0.0</td>
                </tr>
                <tr>
                  <td>::/8</td>
                  <td>Reserved</td>
                  <td></td>
                </tr>
                </tbody>
</table>
            
## Sources
- https://fr.wikipedia.org/wiki/IPv6
- http://www.gestioip.net/cgi-bin/subnet_calculator.cgi
- https://www.cidr.eu/en/ipv6
