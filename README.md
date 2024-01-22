[RoutingRule]
#端口本地规则#
DOMAIN,m.baidu.com,PROXY
DOMAIN,www.baidu.com,PROXY
DOMAIN,thirdqq.qlogo.cn,PROXY
DOMAIN,thirdwx.qlogo.cn,PROXY
DOMAIN-KEYWORD,ap6,DIRECT
DOMAIN-KEYWORD,taobao,DIRECT
DOMAIN-KEYWORD,jiazhang,DIRECT
DOMAIN-KEYWORD,msdk,DIRECT
DOMAIN-KEYWORD,paojiaoyun,DIRECT
DOMAIN-KEYWORD,itop.qq.com,DIRECT
DOMAIN,down.anticheatexpert.com,PROXY
DOMAIN,nj.cschannel.anticheatexpert.com,PROXY
DOMAIN-KEYWORD,cg.qq.com,DIRECT
DOMAIN-KEYWORD,weixin.qq.com,DIRECT
DOMAIN-KEYWORD,openmobile.qq.com,DIRECT
DOMAIN-KEYWORD,lanzou,DIRECT
DOMAIN-KEYWORD,qq.com,DIRECT
PORT,80,REJECT
PORT,443,REJECT
PORT,10012,PROXY
PORT,17500,PROXY
PORT,5692,REJECT
PORT,20297,REJECT

FINAL,DIRECT
 
[RoutingDomainStrategy]
AsIs
 
[FreedomDomainStrategy]
AsIs
 
[LocalPolicy]
bufferSize = 4096
connIdle = 300
downlinkOnly = 0
handshake = 4
uplinkOnly = 0
 
[DnsServer]


[DnsRule]
 
[DnsHost]
 
[DnsClientIp]
 
[Log]
loglevel = none
 
[PerAppVpn]
 
[PerAppMode]
 
[PerAppAllow]
 
[PerAppDisallow]
