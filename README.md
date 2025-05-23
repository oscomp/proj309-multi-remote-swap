# 构建基于RDMA的多节点异质内存系统
**项目名称**

构建基于RDMA的多节点异质内存系统

**支持单位 （可选内容）**

南开大学计算机学院

**项目描述**

RDMA是一种新型网络技术，CPU可以通过Infiniband RDMA网卡设备对连接的另一个设备上的内存发起访问。我们希望通过RDMA网卡、RDMA交换机构建一个3-5节点的原型系统。该系统应拥有2-3个远程内存节点和1-2个计算节点，我们希望可以在Linux内核层面，探索未来如何在更复杂RDMA拓扑连接上实现更高性能的内存池系统。

**所属赛道**

2025全国大学生操作系统比赛的“OS功能挑战”赛道

参赛要求
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求
### 项目导师

宫晓利
- email: gongxiaoli@nankai.edu.cn 


### 难度

高

**说明**
1. 基于>6.1版本的linux发行版开发
2. 组成实际的原型系统
3. 可运行在86架构上
4. 性能开销、稳定性高

**文档**
1. linux kernel:https://kernel.org/

**License**
- GPLv2 (https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

## 赛题分类
内核完善

## 预期目标

**注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标**

**第一题**

在内核上完成基于Swap子系统frontswap接口的RDMA页面置换机制。

**第二题**

尝试适配2个远程内存设备

**第三题**

在远程内存设备性能出现差异时使用调度手段优化

## 备注（可选内容）

