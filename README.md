##特别声明:
本仓库发布的Script项目中涉及的任何解锁和解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.
<br>您必须在下载后的24小时内从计算机或手机以及所有云端设备中完全删除以上内容.
<br>因脚本使用造成的个人损失及第三方损失，由使用者自担。
<br>您使用或者复制了本仓库的任何脚本，则视为已接受此声明

## 使用说明
1. fork此仓库创建自己仓库.
2. 自己仓库 Settings - Secrets - New repository secret 新增三个secret <br> 
   2.1 JD账户cooke，必填，一行一个（注：获取后不要退出登录账号，退出时cookie即时失效）<br> 
   <strong><span style="color:#E53333;">Name</span></strong>：JD_COOKIE    <br>           <strong><span style="color:#E53333;">Value</span></strong>：京东cookie值 [获取JDcookie教程](https://www.bilibili.com/read/cv7597205/)<br> 
    <br> 
   2.2 server酱消息推送，非必填
   <strong><span style="color:#E53333;">
   <br>Name</span></strong>：PUSH_KEY                
   <span style="color:#E53333;">Value</span></strong>：方糖server酱的SCKEY值   [获取SCKEY值](http://sc.ftqq.com/3.version)  「登入」-「微信推送」-「扫码绑定」-「发送消息页获取SCKEY值
   <br>    <br> 
   2.3 保证代码实时同步（注：勾选所有权限）
   <br> <strong><span style="color:#E53333;">
   Name</span></strong>：PAT     <br>   <strong><span style="color:#E53333;">Value</span></strong>：Github token [获取Github token教程](https://blog.csdn.net/eddie_8023/article/details/106388935)<br> 
   
3. 进入「Actions」页面，开启每一个脚本的工作流「Enable workflow」，脚本会定时任务运行  同时可以手动「Run workflow」运行查看脚本运行状况


 
