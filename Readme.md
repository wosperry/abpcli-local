# AbpCli 本地版

## 简介

改动说明

- 移除了npm、nuget等需要访问网络的功能
- 在线下载模板修改为直接从cli项目内获取模板
- 在线还原npm包修改为直接复制wwwroot文件夹
- abp版本固定为7.2.2了，不支持-v参数调整

命令参考

- 为避免与正式cli冲突，使用cli时，命令由 `abp` 改为 `abp-local`

   ``` shell
   abp-local new Demo -o Demo
   ```

## 准备工作

- 将 `abp-local` 移动到合适的位置
- 将 `abp-local` 设置到系统环境变量Path中
- 如果不会设置环境变量，用管理员权限运行文件夹内的 `设置环境变量.exe` ，按A自动设置


## 使用帮助

   - 见官方文档  
   [https://docs.abp.io/zh-Hans/abp/latest/CLI-New-Command-Samples](https://docs.abp.io/zh-Hans/abp/latest/CLI-New-Command-Samples)

   - 如果网不好，可以访问 
   [https://abp.wosperry.com/documents/zh-Hans/abp/latest/CLI-New-Command-Samples](https://abp.wosperry.com/documents/zh-Hans/abp/latest/CLI-New-Command-Samples)

   - 同样，abp文档也可以访问这个地址，图片什么都能正常显示，但过一阵子版本可能落后
   [https://abp.wosperry.com/documents/zh-Hans/abp/latest/](https://abp.wosperry.com/documents/zh-Hans/abp/latest/)
