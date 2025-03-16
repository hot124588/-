《尘飞图片压缩工具专业版使用手册》

一、产品概述
尘飞图片压缩工具是一款针对Windows平台开发的智能图像优化软件，支持JPG/JPEG/PNG/BMP等常见图片格式的批量处理。本工具采用先进的压缩算法，在保证视觉效果的前提下，最高可减少图片文件体积达80%，适用于电商图片管理、摄影作品存档、网页素材优化等场景。当前版本V1.1具备智能化批量处理、深度压缩优化、安全替换机制、空间节省统计四大核心功能。

二、安装与启动

系统要求：
Windows 10/11 64位操作系统
4GB以上内存
500MB可用硬盘空间
.NET Framework 4.8运行库
安装步骤：
(1) 从尘飞航模官方淘宝店获取安装包
(2) 双击运行CF_ImageOptimizer_Setup.exe
(3) 选择安装路径（建议保持默认）
(4) 完成安装后自动创建桌面快捷方式
启动方式：
双击桌面"尘飞图片工具"图标
通过开始菜单快捷方式启动
右键图片文件夹选择"使用尘飞工具优化"
三、核心功能详解

单文件优化模式
操作流程：
① 点击"选择图片文件"按钮，支持Ctrl多选/Shift连选
② 在质量设置栏输入1-100的压缩值（建议60-80）
③ 点击"开始优化"启动处理
④ 查看实时进度条和时间预估
⑤ 完成后自动弹出优化报告
文件输出：

在原文件同目录生成"CFOK"优化文件夹
保留原始文件名，格式统一转为JPG
自动生成"summary.txt"统计报告
安全替换模式
操作流程：
① 完成单文件优化后
② 点击"替换原文件"按钮
③ 确认二次弹窗警告
④ 系统自动完成：
将CFOK文件覆盖原始文件
删除CFOK临时目录
保留原始文件的时间戳属性
注意事项：
! 此操作不可逆，建议提前备份
! 原PNG/BMP文件将被永久删除
! 系统盘文件需要管理员权限

批量处理模式（高危操作）
适用场景：
网站图片目录优化
摄影作品集归档
社交媒体素材整理
操作流程：
① 点击"替换目录所有"按钮
② 阅读并确认高危操作提示
③ 选择目标根目录
④ 查看文件扫描结果
⑤ 启动深度处理：

递归处理所有子文件夹
自动转换图片格式
智能覆盖原始文件
清除所有临时目录
风险控制：
✓ 支持ESC键紧急终止
✓ 每个文件独立容错处理
✓ 异常操作记录详细日志

四、高级功能说明

智能统计系统
实时显示本次节省空间（MB）
累计节省统计（GB）
使用次数计数器
详细报告存储路径：程序目录\TJSJ\
自动更新机制
每次启动自动检测更新
支持断点续传下载
数字签名验证（MD5校验）
静默安装无需干预
专业日志系统
实时记录操作事件
错误代码说明系统
日志路径：程序目录\image_optimizer.log
支持日志导出分析

