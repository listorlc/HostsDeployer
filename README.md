# HostsDeployer
 自动部署 Windows hosts

 1. 直接将编译好的 HostsDeployer.exe 文件复制到自己指定的目录即可
 2. 在 HostsDeployer.exe 文件的相同路径下创建配置文件 HostsDeploymentConfig.txt
 3. 编辑配置文件，在里面添加要自动处理的 hosts 映射
    # 开头的行表示注释，自动忽略
    + 开头的表示自动在 hosts 中添加该映射
    - 开头的表示自动在 hosts 中删除该映射
