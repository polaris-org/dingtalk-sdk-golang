# Introduce
DingDing SDK implemented with Golang.

DingDing Documents: [https://open-doc.dingtalk.com/microapp/serverapi3](https://open-doc.dingtalk.com/microapp/serverapi3)
# Features
Partial feature structure and completion:
 - [x] 应用授权
   - [x] 获取企业凭证
   - [x] 获取企业授权信息
   - [x] 获取授权应用信息
 - [ ] 身份验证
 - [ ] 通讯录管理
   - [x] 用户管理
     - [x] 获取用户详情
     - [x] 获取部门用户userid列表
	 - [x] 获取部门用户
	 - [x] 获取部门用户详情
	 - [x] 获取管理员列表
	 - [x] 获取管理员通讯录权限范围
	 - [x] 查询管理员是否具备管理某个应用的权限
	 - [x] 根据unionid获取userid
	 - [x] 获取企业员工人数
   - [ ] 部门管理
     - [ ] 获取子部门ID列表
	 - [ ] 获取部门列表
	 - [ ] 获取部门详情
	 - [ ] 查询部门的所有上级父部门路径
	 - [ ] 查询指定用户的所有上级父部门路径
   - [x] 角色管理
     - [x] 获取角色列表
	 - [x] 获取角色下的员工列表
	 - [x] 获取角色组
	 - [x] 获取角色详情
   - [ ] 外部联系人管理
     - [ ] 获取外部联系人标签列表
	 - [ ] 获取外部联系人列表
	 - [ ] 获取外部联系人详情
   - [ ] 通讯录权限范围
     - [ ] 获取通讯录权限范围
 - [x] 消息通知
   - [x] 工作消息通知
     - [x] 发送工作通知消息
	 - [x] 查询工作通知消息的发送进度
	 - [x] 查询工作通知消息的发送结果
	 - [x] 工作通知消息撤回
   - [x] 发送普通消息
     - [x] 发送普通消息
 - [ ] 文件存储
   - [x] 管理媒体文件
     - [x] 上传媒体文件
   - [ ] 管理钉盘文件
     - [ ] 发送钉盘文件给指定用户
	 - [ ] 新增文件到用户钉盘
	 - [ ] 获取企业下的自定义空间
	 - [ ] 授权用户访问企业自定义空间
	 - [ ] 单步文件上传
	 - [ ] 开启分块上传事务
	 - [ ] 上传文件块
	 - [ ] 提交文件上传事务
	 
