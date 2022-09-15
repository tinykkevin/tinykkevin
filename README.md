- 👋 Hi, I’m @kkevin
- 👀 I’m interested in Java / Emacs / Linux / macos
- 🌱 I’m currently learning elisp
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
tinykkevin/tinykkevin is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->



** 安装zsh并启用autosuggestion
```shell
yum install zsh -y; yum install git -y; sh -c "$(curl -fsSL [https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"](https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)")
```

mac
```shell
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```



**二、下载插件到对应的文件夹**
安装autosuggestion
```shell
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
```

安装highlight
```shell
git clone [https://github.com/zsh-users/zsh-syntax-highlighting.git](https://github.com/zsh-users/zsh-syntax-highlighting.git) ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

**三、启用插件**
```shell
omz plugin enable zsh-autosuggestions
```

```shell
omz plugin enable zsh-syntax-highlighting
```

你也可以直接编辑.zshrc，加入这两个插件

```shell
source .zshrc
```
