# 像素小伴（PixelPal） - 桌面像素宠物伴侣

![项目图标](img/icon.png)

一个轻量级的桌面宠物应用，为您的数字生活增添乐趣。PixelPal会在您的桌面上展示可爱的像素宠物，陪伴您的工作与学习。

## ✨ 主要功能

- 🐾 多种像素宠物可选
- 🖱️ 拖拽移动宠物位置
- 🎭 流畅的动画效果
- 📌 置顶/固定位置选项
- 🗂️ 宠物管理系统
- ⏳ 自动闲逛行为
- 🔄 开机自启动

## 🛠️ 安装指南


| **功能** |         **说明**         |
| :------: | :----------------------: |
|   置顶   | 设置窗口是否保持在最上层 |
| 固定不动 |       锁定宠物位置       |
| 管理宠物 |      打开宠物管理器      |
| 更换宠物 |       切换不同宠物       |
|   隐藏   |       暂时隐藏宠物       |
|   退出   |         关闭应用         |

## 🖼️ 自定义宠物
1. 准备一组连续编号的PNG图片（如1.png, 2.png...）,并放入一个文件夹中。
2. 通过"管理宠物"功能导入，直接选中该文件夹，点击"导入"即可。
3. 设置宠物名称，保存即可。
4. 在桌宠右击，即可在应用中使用。
### 方法一：源码运行

1. 确保已安装Python 3.6+
2. 安装依赖库：

```bash
pip install -r requirements.txt
```

3. 克隆本仓库：

```bash
git clone https://github.com/LispTex-f/PixelPal.git
```

4. 运行应用：

```bash
python main.py
```

### 方法二：安装包安装

1. 蓝奏下载 `PixelPal_Setup.exe`：https://www.ilanzou.com/s/4nrZYScM
2. GitHub release中下载`PixelPal_Setup.exe`：https://github.com/LispTex-f/PixelPal/releases

## 🏗️ 项目结构

- `main.py`：主程序入口
- `pixel_pet.py`：像素宠物类定义
- `manager.py`：管理工具类定义
- `db_manager.py`：数据库管理类定义
- `config.py`：配置函数定义
- `pets.db`：数据库
- `img/`：图标文件

## 📝 贡献指南

欢迎贡献代码或提出问题！请先fork本仓库，然后提交pull request。

## 📜 许可证

MIT License

## 📞 联系方式

如有问题，请提交GitHub Issues或联系开发者邮箱

- 邮箱： 3014906370@qq.com
- GitHub Issues： https://github.com/LispTex-f/PixelPal/issues
