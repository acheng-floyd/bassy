# bassy
quality control (QC) platform

================


<!-- MarkdownTOC -->

- [Bassy 功能概述](#功能概述)
- [系统详述](#系统详述)
    - [功能概览](#功能概览)
    - [我的任务](#我的任务)
    - [项目管理](#项目管理)
        - [贯穿产品项目测试阶段的生命周期](#vera-系统高可用)
        - [项目测试文档相关](#项目测试文档相关)
        - [内部项目运用](#内部项目运用)
    - [测试用例](#测试用例)
    - [智库](#智库)
    - [资源情况](#资源情况)
    - [统计分析](#统计分析)
    - [资产管理](#资产管理)
    - [配置管理](#配置管理)
- [安装部署](#安装部署) 

# 安装部署
1.在bassy-mapper模块下，存放有数据库表和数据初始化sql文件，请先初始化数据库信息。
2.在bassy-web模块下，配置数据库和redis的连接配置
3.在bin目录下，执行install.sh脚本，会自动打包并启动服务。
