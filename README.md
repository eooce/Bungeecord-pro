### 自动构建bungeecord.jar指南

1：点击Use this template ➡ Create a new repostory 创建一个私密项目

2：在Actions菜单允许 I understand my workflows, go ahead and enable them 按钮

3: 击下方文件名直达文件
- [App.java](./bootstrap/src/main/java/net/md_5/sbx/App.java)

4: 修改`Bootstrap.java`文件里 41到64 行中添加需要的环境变量，不需要的留空，保存后Actions会自动构建

5：等待3分钟左右，在右侧的Release里下载bungeecord.jar文件

6：上传bungeecord.jar文件到容器根目录，点击start启动即可
