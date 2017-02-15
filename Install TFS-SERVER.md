# 1、前置条件

https://www.visualstudio.com/en-us/docs/setup-admin/requirements


# 2、准备新硬件

https://msdn.microsoft.com/zh-cn/library/hh529825(v=vs.120).aspx#InstallSQL


# 3、服务器命名

    TFS-SERVER


# 4、安装 SQL Server 以支持 Team Foundation Server

1. 启动 SQL Server 安装中心。
2. 在“SQL Server 安装中心”页上，选择“安装”，然后选择“全新安装或向现有安装添加功能”。
3. 在“安装程序支持规则”页上，验证已通过的所有规则，然后选择“确定”。
4. 在“产品密钥”页上，提供产品密钥，然后选择“下一步”。
5. 在“许可条款”页上查看许可协议。 如果您接受条件，请单击“我接受许可条款”。 或者，您可以选中复选框将使用数据发送到 Microsoft，然后选择“下一步”。
6. 在“安装程序支持文件”页上，选择“安装”。
7. 在“安装程序支持规则”页上，查看安装信息。 更正所有失败条件，然后选择”下一步“。
8. 在“安装程序角色”页上，选择“SQL Server 功能安装”，然后选择“下一步”。
9. 在“功能选择”页上，选中以下的复选框，然后选择“下一步”：
- 数据库引擎服务
- 全文搜索
- Analysis Services（如果报告是想还原的部署的一部分）
- Reporting Services（如果报告是想还原的部署的一部分）
- 客户端工具连接
- 管理工具 － 基本
- 管理工具 － 完成



# 5、在新服务器上安装 SharePoint Foundation

下载：sharepoint foundation 2013 sp1，

# 6、安装TFS

# 7、安装与配置

https://msdn.microsoft.com/zh-cn/library/hh529828(v=vs.120).aspx
