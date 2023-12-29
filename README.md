## Descripton

Linux 下的字体完善。

## Usage

克隆本仓库：

```bash
git clone https://github.com/yuanj82/linux-fonts.git
```

复制到字体文件夹（Debian 为例）：

```bash
cd linux-fonts
sudo cp -r ./windows-fonts /usr/share/fonts/
sudo cp -r ./wps-fonts /usr/share/fonts/
sudo cp -r ./ubuntu-fonts /usr/share/fonts/
```

创建索引并刷新字体缓存：

```bash
sudo mkfontscale
sudo mkfontdir
sudo fc-cache 
```