### 2.2 IP收集 - IP.md
1. IP资产收集
   - 1.1 收集域名后应该是有一堆域名了，一个个判断略显麻烦，这里已经有师傅为我们做好了域名转化为ip的工具，同时能够将C段整理出来
      + https://github.com/EdgeSecurityTeam/Eeyes
2. CDN检测
   - 2.1 全球ping
      + https://ping.chinaz.com/
      + https://myssl.com/cdn_check.html
      + https://wepcc.com/
   - 2.2 nslookup
      + 命令：nslookup www.baidu.com
   - 2.3 工具
      + https://www.cdnplanet.com/tools/cdnfinder/
3. 绕过CDN获取真实IP
   - 查看IP与域名绑定的历史记录。使用 CDN 之前可能有记录。相关查询网站
      + DnsDB：https://www.dnsdb.io/zh-cn/
      + 微步在线：https://x.threatbook.com/
      + Netcraft：https://www.netcraft.com/ 待确认
      + IPIP：https://tools.ipip.net/ 功能多
4. IP段扫描
      + https://github.com/shadow1ng/fscan
      + https://github.com/Adminisme/ServerScan
      + https://github.com/EdgeSecurityTeam/EHole
4. ...

- 参考资源：https://xz.aliyun.com/t/10236
- https://baijiahao.baidu.com/s?id=1732065709434162645&wfr=spider&for=pc