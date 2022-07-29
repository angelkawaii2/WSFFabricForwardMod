# Websocket Forward Plugin for Mirai-Console

基于 [Websocket Forward SDK](https://github.com/angelkawaii2/RaincandyWsForwardProtocol)
的 [Mirai-Console](https://github.com/mamoe/mirai) 插件实现

## Version

v1.0.0

## Requirements

- Java 17+
- Mirai 2.10.1 ~ 2.11.1（已测试）

## To-do

- [ ] Optimize config printing on startup
- [ ] 需检查 connectionId 在配置中是否存在

## Installation

放入Mirai Plugins文件夹下，启动后插件会自动生成以下配置文件:

- chatForward.json
    - 配置消息转发是否开启，目标客户端等
- commandForward.json
    - 配置指令转发相关内容
- config.json
    - 配置全局管理员，服务器信息等
- incomingMinecraftChatConfig
    - 配置Minecraft消息（传入）的目的地
- minecraft-chat-servername-rewrite
    - 配置 Minecraft 聊天消息 中的服务器名称重写

## License

AGPLv3
