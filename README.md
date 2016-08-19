1 nova的policy配置文件修改方法
	(1)将所有控制节点上的如下文件修改成该文件。
	/etc/nova/policy.json
2、keystone的policy配置文件修改方法
	(1) 使用admin用户创建project_admin角色。
	(2) 将keystone所在节点的配置文件修改成该文件。
	/etc/keystone/policy.json