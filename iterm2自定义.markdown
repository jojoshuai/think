### roboto mono字体

下载地址
https://github.com/googlefonts/RobotoMono/tree/main/fonts/variable

### Spaceship Prompt 主题
安装了zsh，并安装了oh-my-zsh后，可以使用本主题，本主题用于现实当前pwd的位置，包括：用户名、主机名、目录、git分支

主题项目地址：https://github.com/spaceship-prompt/spaceship-prompt
前提：
1. echo $ZSH_VERSION #> 5.8.1
2. [Powerline Font](https://github.com/powerline/fonts) or [Nerd Font](https://www.nerdfonts.com/) (even better)必须被安装在终端里

安装：
1. 下载源码：git clone --depth=1 https://github.com/spaceship-prompt/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
2. 修改主题：
   1. vim ~/.zshrc
   2. 修改 ZSH_THEME="spaceship-prompt/spaceship"
3. `source ~/.zshrc` 使之生效
4. 处理表情为的问题: iterm里settings->Profiles->Text->字体选择Roboto Mono for Powerline。PS：任意的For Powerline的字体都能使特殊字符显示

