# 第二次迭代会议记录

## Week 10 - May. 9

### 会议内容
 - 总结了前面工作的不足，分配了这周的任务
 - 具体
    - 前端第二次迭代进度较快，后端需要跟上
    - 周五前补好文档，活动图、用例图
    - 建议周五晚上在群上写一个阶段性分享，汇报完成了什么<br>
      若进度较赶其他人可以帮帮忙
    - 周末完成团队作业
    - 全员补一下看板的内容，写一下自己之前完成的任务
    - 下周尽量完成第二次迭代（多人点餐功能）

### 任务分配
 - 林景仰  根据模型修改数据库
 - 刘钟涛  实现api，之前的评审文档看着修改一下（如果需要要拆成两份，写详细一些）
 - 彭高    ui设计文档等其他
 - 彭彩莹  项目愿景，拆分会议记录
 - 马晓鹤  待安排
 - 罗剑杰  待安排
 
---

## Week 7 - Apr. 16

### 会议背景
 - 前端界面需要大改
 - 后台功能增加：多人点餐
 - 第一次迭代后工作基本停滞
 
### 会议内容

 - 多人点餐的交互
 - 拓展业务
 - 当前业务的细节
 - 此次迭代完成的时间
 
### 会议结论

 - 当前业务的细节
   - 在单人点餐的基础上实现后台存放图片和菜名
   - 数据库暂时不保存已上菜状态
   - 评价功能待定
   - 推荐菜单页面可以添加菜品至购物车
   - 主菜单的菜品小图点击可以放大
   
 - 拓展业务
   - 保存每一桌的上菜情况
   - 添加服务员管理页面，餐馆管理系统
   - 与后厨实时交互，告知厨房煮菜顺序
   
- 多人点餐
  - 主菜单页面只显示当前点餐用户的订单信息（我的订单）
  - 在购物车页面同时显示（我的订单）与当前桌号全部订单，<br>
  但是只能编辑（我的订单）,总订单不能改变
  - 其他细节由产品经理兼UI设计师整理后再商讨决定，<br>
  如UI界面的设计，是否增加确认订单功能，是否支持现金结账
  
- 这次迭代完成的时间
  - 暂定从4月16日到5月13日,5月14日前完成

---

## Week 6 - Apr.12
### 讨论的内容
**技术栈**
1. 由于无法调用微信支付api，讨论前端技术栈换不换


**功能**
1. 中途退出的页面保存
2. 多人同时点餐 :fork_and_knife: :family:
3. 加菜

**文档**
1. 给每个人分配负责的文档

### 讨论的结果
**技术栈**

1. 前端技术栈不换
2. 暂时放弃微信支付


**功能**
1. 中途退出
- 退出时前端发送一个表单给后台记录，再次打开时后台返回表单
- 若切后台的时间较短可以由前端缓存
	
2. 多人同时点餐	
- 全部缓存在购物车不区分用户
- 保留是否正在吃饭的状态

3. 加菜
- 每次确认订单后重新生成订单选购新点的菜品


**文档分工**
1. 用例图       longjj先探索出一个例子，之后再分工一起完成
2. UI           Ecer23
3. 规范         后台用谷歌的规范，前端用ESlint，BeAShaper
4. 技术博客     dashboard，每人一篇
5. 前期调研     实地考察并写出报告，Nition
6. 将文档整合   Yunglinjy
7. 会议记录     Arurururu
8. 愿景等其他    BeAShaper




