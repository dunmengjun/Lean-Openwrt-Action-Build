<p align=center>
  <br>
  <span>Openwrt Github Action Build | Xiaomi MIR3 Openwrt 自动编译 </span>
  <br>
  <span>Customize your own OpenWrt firmware for Xiaomi MIR3 using Github Actions.</span>
  <br>
  <br>
</p>

<p align="center">
  <a href="#usage">Usage</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#info">Info</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#features">Features</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#acknowledgments">Acknowledgments</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">License</a>
</p>
## Usage

1. Star and Fork this repository and select a branch that you want to build for.
2. Click the `Action` button of your own forked repository
3. Click the `Build Lean's OpenWrt` under all workflows
4. Click the `Run workflow` button on the right, you can input some logs here (optional)
5. Github Actions workflow will be triggered and run automaticlly
6. Wait completion of the workflow and download files from `Aritifact`

## 使用方法（简体中文）

1. Star and Fork this repository, 选择一个分支，分支名字是你路由器的品牌
2. 在你的forked repo中，点击上方的 `Action` 按钮 
3. 点击左侧的all workflows下方的 `Build Lean's OpenWrt`
4. 点击右侧的 `Run workflow` 按钮，这里可以输入一些日志 (可选的)
5. Github Actions workflow 会被触发并自动运行编译
6. 等待workflow工作完成，从 `Aritifact`中下载生成的文件

## Info

- gateway: 192.168.2.1 (in diy.sh change it)

### Network
- IPv6
- NAT6
- Shadowsocks
- V2Ray
- Trojan

### Tools
- htop
- curl
- wget
- iperf3
- tcpdump
- luci-app-commands
- luci-app-ttyd
- luci-app-webadmin
- luci-app-wrtbwmon

## Acknowledgments

- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [Phicomm-K2P-Openwrt-Autobuild](https://github.com/tjuyy/Phicomm-K2P-Openwrt-Autobuild)

