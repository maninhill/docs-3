
## 1 登录阿里云官方网站

!!! Abstract ""
    在您的浏览器中打开阿里云的官方网站（https://www.aliyun.com/）并登录您的账号。

!!! info "服务器优惠"
    如果你还没有服务器，欢迎在[此页面选购](https://www.aliyun.com/daily-act/ecs/activity_selection?userCode=j57gyupo)，阿里云服务器0元试用，首购低至0.9元/月起。

    [点此查看更多云产品优惠](https://www.aliyun.com/minisite/goods?userCode=j57gyupo)。

## 2 选择 ECS 实例

!!! Abstract ""
    在阿里云管理控制台中，点击左侧菜单栏的 **云服务器 ECS** 选项。

## 3 创建 ECS 实例

!!! Abstract ""
    点击页面上方的 **创建实例** 按钮，并按照以下步骤进行配置：

    - 地域及可用区：选择适合您的地理位置和可用区域。
    - 实例配置：选择适合您需求的实例规格和网络类型。
    - 镜像：点击 **云市场镜像** 选项卡，然后在搜索框中输入 **1Panel** 并选择镜像。
    - 存储：配置系统盘和数据盘的大小和类型。
    - 网络和安全组：根据您的需求配置网络和安全组。
    - 其他选项：根据您的需求配置其他选项。
    - 确认订单：确认您的配置信息并点击"立即购买"按钮。

## 4 等待实例创建完成

!!! Abstract ""
    等待片刻，直到 ECS 实例创建完成。您可以在 ECS 实例列表中看到新创建的实例。

## 5 登录 ECS 实例

!!! Abstract ""
    点击 ECS 实例列表中对应实例的 **远程连接** 按钮，选择 **立即登录**，然后输入登录密码。

## 6 1Panel 使用步骤

### 1 安全组放行 8090 端口

!!! Abstract ""
    端口放行教程：https://help.aliyun.com/document_detail/25471.html

### 2 获取面板用户信息

!!! Abstract ""
    
    - 输入获取默认密码命令：1pctl user-info
    - 输入完，回车即可获取用户信息

![img.png](../../img/installation/用户信息.png)

### 3 访问面板

!!! Abstract ""

    - 通过 http://服务器外网IP:8090/安全入口 访问面板管理页面，如：http://172.16.10.1:8090/mm4h9iucdn
    - 输入帐号密码

### 4 面板设置

!!! Abstract ""

    - 修改面板默认帐号密码
    - 开始使用面板
