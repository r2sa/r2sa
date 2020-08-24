# 架构与架构师

### 是什么?
- 架构是软件系统的结构与行为设计
- 架构实现就是围绕架构设计去开发程序的过程
- 架构师就是依据具体的业务场景给出架构设计并带领架构实现的团队领导型人物。

### 做什么?
1. 架构师需要交付什么
- 架构，通常以文档的形式体现
- 架构的实现，最终的技术决策流实际体现在线上系统的运行结构中

2. 做什么?
- 确认需求
- 系统分解
- 技术选型
- 制定技术规格说明

3. 在不同规模的团队中，不同的业务背景下，架构存在不同维度和层次:
- 高维度：系统、子系统或服务之间的切分与交叉结构
- 中维度：系统、服务内部模块的切分与交叉结构
- 底维度：模块组成的代码结构、数据结构、库表结构等

4. 不同维度下，架构师工作的共同点:
- 确定边界：划定问题域、系统域的边界 (*[什么是域]()*)
- 切分协作：切分系统和服务，目的是建立分工与协作，并行已获得效率
- 连接交互：在切分的各部分之间建立连接交互的原则和机制
- 组装整合：在切分的各部分按预期定义的规则和方法组装整合成一体，完成系统目标
以上的过程也是系统分解的过程

5. 架构实现过程中的考虑：
<table width="511.55" border="0" cellpadding="0" cellspacing="0" style='width:511.55pt;border-collapse:collapse;table-layout:fixed;'>
   <col width="66.65" style='mso-width-source:userset;mso-width-alt:2843;'/>
   <col width="198.30" style='mso-width-source:userset;mso-width-alt:8460;'/>
   <col width="246.60" style='mso-width-source:userset;mso-width-alt:10521;'/>
   <tr height="20.40" style='height:20.40pt;'>
    <td class="xl65" height="20.40" width="66.65" style='height:20.40pt;width:66.65pt;' x:str>考虑方面</td>
    <td class="xl66" width="444.90" colspan="2" style='width:444.90pt;border-right:.5pt windowtext;border-bottom:.5pt windowtext;' x:str>详细内容</td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl68" height="17.60" style='height:17.60pt;' x:str>选型评估</td>
    <td class="xl69" x:str>选库，选框架，选API</td>
    <td class="xl69"></td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl70" height="52.80" rowspan="3" style='height:52.80pt;border-right:.5pt windowtext;border-bottom:.5pt windowtext;' x:str>程序设计</td>
    <td class="xl69" x:str>逻辑</td>
    <td class="xl69" x:str>流程、分支</td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl69" x:str>控制</td>
    <td class="xl69" x:str>策略、并行串行、同步异步</td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl69" x:str>数据</td>
    <td class="xl69" x:str>结构、状态、存取</td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl68" height="17.60" style='height:17.60pt;' x:str>执行效率</td>
    <td class="xl69" x:str>运行时间、响应时长、吞吐总量</td>
    <td class="xl69"></td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl68" height="17.60" style='height:17.60pt;' x:str>稳定健壮</td>
    <td class="xl69" x:str>异常处理、边界条件</td>
    <td class="xl69"></td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl70" height="35.20" rowspan="2" style='height:35.20pt;border-right:.5pt windowtext;border-bottom:.5pt windowtext;' x:str>维护运维</td>
    <td class="xl69" x:str>维护</td>
    <td class="xl69" x:str>易读、易理解、易修改</td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl69" x:str>运维</td>
    <td class="xl69" x:str>监控、日志、配置、变更、兼容</td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl70" height="35.20" rowspan="2" style='height:35.20pt;border-right:.5pt windowtext;border-bottom:.5pt windowtext;' x:str>集成部署</td>
    <td class="xl69" x:str>提供库</td>
    <td class="xl69" x:str>依赖复杂度、便利性、易用性、升级管理</td>
   </tr>
   <tr height="17.60" style='height:17.60pt;'>
    <td class="xl69" x:str>提供服务</td>
    <td class="xl69" x:str>调用服务、监控统计、服务SLA</td>
   </tr>
   <![if supportMisalignedColumns]>
    <tr width="0" style='display:none;'>
     <td width="67" style='width:67;'></td>
     <td width="198" style='width:198;'></td>
     <td width="247" style='width:247;'></td>
    </tr>
   <![endif]>
  </table>

6. 注意点
- 架构决策 与 架构实现 的矛盾
- 如何掌控变化

### 架构师需要的能力
1. 设计能力
2. 技术实力
3. 沟通能力
4. 应急能力
5. 管理能力
6. 抽象能力


### 参考资料
- 极客时间:程序员进阶攻略
- [什么是架构？架构师的职责是什么？](https://www.zhihu.com/question/19558112)