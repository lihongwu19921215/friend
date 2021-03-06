# 人脉管理系统

## 公众号：全栈程序员之路
![输入图片说明](https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzIzMTE0NTE5Mg==&mid=2651421365&idx=1&sn=ec2b310f1888fca3560ba504af0077f5&send_time= "在这里输入图片标题")

## 产品预览图：
1 朋友圈
![输入图片说明](https://git.oschina.net/uploads/images/2017/0716/083828_b5eecffe_3018.png "屏幕截图.png")
2 交往记录
![输入图片说明](https://git.oschina.net/uploads/images/2017/0716/083837_fdbdd1cf_3018.png "屏幕截图.png")
3 统计

4 台账
![输入图片说明](https://git.oschina.net/uploads/images/2017/0716/083904_d803a016_3018.png "屏幕截图.png")

## 产品定位
管理人脉圈

## 产品解决的痛点
随着朋友，客户越来越多，需要一款软件来统一管理人脉圈

## 产品潜在客户
1. 大众用户

## 需求描述
1. 管理朋友圈
2. 记录与朋友的交流
3. 能根据技能，年龄等，做综合统计

## 需求分析
1. 朋友管理
2. 交流记录管理
3. 综合查询，

## 技术架构
1. Java：Nutz框架
2. 缓存：EhCache，
3. 静态模板框架：Beetl
4. 后台UI框架：B-JUI
5. 数据库：MySql
6. 后台服务器：阿里云centos6

## 数据模型(数据字典中有详细信息)
台账：
1. 性别
2. 关系
3. 联系频率
4. 学历
5. 信用评级
6. 婚姻
7. 血型
8. 政治面貌

朋友：
1. 朋友(姓名,英文名,关系[W],信用评级[w]，联系频率[W],电话，QQ，Email，性别[W],名族,出身日期,学历[W],婚姻[w],血型[w],政治面貌[w],技能,紧急联系方式,爱好，特长，性格描述,)
2. 交往记录(朋友ID[w],主题，内容，性质，状态，开始时间，结束时间，备注)
3. 工作经历
4. 教育经历
5. 项目经历
6. 家庭成员

系统：
1. 菜单
2. 用户
3. 用户权限
4. 用户组
4. 系统设置
