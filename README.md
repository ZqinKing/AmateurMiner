# AmateurMiner
# 白帽小钢炮
### [DownLoad](https://github.com/ZqinKing/AmateurMiner/releases)<br>
#####  <br>
####  V2.8(2018.09.03)<br>
#####  1、增加对HSPMiner的支持<br>
#####  <br>
#####  <br>
####  V2.6(2018.07.21)<br>
#####  1、稳定性修复<br>
#####  2、放弃对Claymore的重启操作，使用Claymore是每30分钟，会设置一次dcri以便于A卡机获得更好的算力<br>
#####   （建议设置 "-r 1" 参数，纯A卡机除此之外建议加上 "-asm 2", 直接在参数栏填上即可）<br>
#####  3、显卡信息现已支持大部分显卡，包括A卡已经P系列N卡（仅ETH、ETC）<br>
#####  4、优化本地代理，降低矿池拒绝率<br>
#####  5、增加定是重启功能<br>
#####  <br>
#####  <br>
####  V2.5.8(2018.07.16)<br>
#####  1、增加矿池自定义功能，但是目前只支持正常钱包地址的挖矿，注册并使用注册账号的矿池不支持（ETH\ETC不影响）<br>
#####  2、修复在中文路径下，Claymore因获取不到日志信息而导致的循环重启情况<br>
#####  <br>
#####  <br>
####  V2.5(2018.07.08)<br>
#####  1、修复上一版本，出现异常重启失效的BUG<br>
#####  2、增加对Claymore的运行监测，监测到异常是重启软件<br>
#####  <br>
####  V2.4(2018.07.05)<br>
#####  1、增加BTM挖矿工作量检测，若15分钟未检测到有份额提交的，自动重启矿工。（主要针对NebuTech5.0长时间工作后异常停止）<br>
#####  2、增加BTM矿池工作任务下发检测，若5分钟未检测到有新的工作任务下发的自动重启本地代理。<br>
#####  3、BTM新增对91矿池、蜘蛛矿池的抽水拦截，（由于NebuTech抽水使用的是随机矿池，故必须支持，否则会导致不能完全去除NebuTech的抽水）<br>
#####  4、稳定性修复<br>
#####  <br>
####  V2.3(2018.07.04)<br>
##### 1、Support ETH&ETC&BYTOM(BTM)<br>
##### 1、支持ETH、ETC、BTM挖矿<br>
##### 2、Cost reduction（ETC&ETH devfee 0.3%, BTM devfee 0.5%）<br>
##### 2、减少矿工费用，（ETC&ETH矿工费减少至0.3%，BTM矿工非减少至0.5%）<br>
