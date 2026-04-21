## Zephyr 最小工程模板



## 开发环境配置

详见 `Docs/开发环境.md` 

## 硬件适配流程

查看官方soc适配 / 具体开发板适配

* 官方适配开发板：
  1. 查看 `zephyr/boards/` 下 `board.dts` 已有设备节点
  2. 根据需求在 `my_project/boards/` 下创建 `board.overlay` 进行硬件描述修改
* 官方适配 soc ：详见 `Docs/Kconfig && 设备树使用.md` 

## 软件开发流程

* 利用 cmake 组织项目结构，按照一般 rtos 开发即可
* 利用 Kconfig 管理参数，详见 `Docs/Kconfig && 设备树使用.md` 