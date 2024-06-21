# 服务器巡检工具

本项目是一个使用Python构建的服务器巡检工具。它允许用户连接到多个服务器，执行命令，并将输出记录到Excel文件和日志文件中。

## 功能特点

- 使用SSH连接到多个服务器。
- 在所有服务器上执行指定的命令。
- 将命令输出记录到Excel文件中。
- 在GUI中显示命令输出的最后一行。
- 保存和加载服务器配置和IP地址。
- 使用PyQt5构建的用户友好图形界面。

## 前提条件

在开始之前，请确保您已经满足以下要求：

- 在您的本地机器上安装了Python 3.x。
- 安装了以下Python包：
  - `paramiko`
  - `pandas`
  - `PyQt5`

您可以使用`pip`安装所需的包：

```bash
pip install paramiko pandas PyQt5
