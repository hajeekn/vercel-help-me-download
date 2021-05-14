# 前言
挂了个V**下载ScreenTogif速度还是只有2MB/S,因此突发奇想,<s>按照[Chenyfan 大大做了一个Vercel下载](https://github.com/ChenYFan-Tester/____-help-me-download)</s>其实就是抄袭
# 使用方法
![](https://user-images.githubusercontent.com/77675898/118279011-34c54080-b4fd-11eb-8e8f-d8977d86e478.png)

进入Vercel仪表板

选择 New Project(新建项目)

然后在选择Import Third-Party Git Repository(导入第三方git仓库)

把 https://github.com/ladjeek-actions/vercel-help-me-download.git 填写进文本框在选择 Continue

![image](https://user-images.githubusercontent.com/77675898/118279253-81a91700-b4fd-11eb-9a9a-15552ea2e86a.png)

![image](https://user-images.githubusercontent.com/77675898/118279273-8968bb80-b4fd-11eb-8558-6b309ddd7989.png)

进入这里后选择自己的账户

![image](https://user-images.githubusercontent.com/77675898/118279349-9f767c00-b4fd-11eb-9ada-fddd71ed511b.png)

然后这里依据需要选择

![image](https://user-images.githubusercontent.com/77675898/118279398-aef5c500-b4fd-11eb-9b54-2e35c874aae1.png)

这里用GitLab测试

![image](https://user-images.githubusercontent.com/77675898/118279446-bc12b400-b4fd-11eb-8542-6af9334ea2e1.png)

这一步不用管,继续 Continue

![image](https://user-images.githubusercontent.com/77675898/118279495-cb91fd00-b4fd-11eb-8deb-d0ae1a0f389d.png)

这里需要配置一下

![image](https://user-images.githubusercontent.com/77675898/118279522-d3ea3800-b4fd-11eb-8693-9d0cd913498d.png)

展开Build and Output Settings

![image](https://user-images.githubusercontent.com/77675898/118279567-de0c3680-b4fd-11eb-920b-5f6231fea41a.png)

开启Build Command

设置成yarn run get

设置OUTPUT DIRECTORY为public

然后再展开Environment Variables

![image](https://user-images.githubusercontent.com/77675898/118279766-1744a680-b4fe-11eb-9892-c6b044720947.png)

添加一个LINK值,值写下载地址,然后点击ADD

ADD之后再点击Deploy

