![Windows/Ubuntu/MacOS](https://github.com/LeagueRaINi/Aida64-Keygen/workflows/Windows/Ubuntu/MacOS/badge.svg)

# **This is for educational purposes only!**
- this project contains methods for generating and verifying aida64 keys

**Thanks to:**
- approved for helping reverse some of this
- wildbook & veykril for helping me a lot converting this to rust
- moonshadow565 for explaining and simplifying some of the methods

- Build
我使用的环境是 Ubuntu 22.04，理应 Debian 11 也不会有什么问题

# 安装 Rust 编译环境
curl https://sh.rustup.rs -sSf | sh
# 安装其他依赖项
apt update
apt install pkg-config cmake build-essential libxcb-composite0-dev libfontconfig1-dev
# 克隆源码
git clone https://github.com/LeagueRaINi/Aida64-Keys.git
# 编译
cd ./Aida64-Keys
cargo build --verbose



如果想要 Windows 的文件，那就继续这么弄

# 安装 MinGW-w64 作为开发环境
apt install mingw-w64
# 添加 Windows GNU目标
rustup target add x86_64-pc-windows-gnu
# 编译
cargo build --target x86_64-pc-windows-gnu

编译成功的话，可执行文件会在这个目录里面


# 安装 MinGW-w64 作为开发环境
apt install mingw-w64
# 添加 Windows GNU目标
rustup target add x86_64-pc-windows-gnu
# 编译
cargo build --target x86_64-pc-windows-gnu
