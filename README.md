# zsh-configs
## Пример использования
```bash
mkdir ~/.zshconfigs
cd ~/.zshconfigs
git clone THIS_REPO
touch local
```
### Добавить в ~/.zshrc
```bash
source $HOME/.zshconfigs/zsh-configs/common
source $HOME/.zshconfigs/zsh-configs/pydev
source $HOME/.zshconfigs/zsh-configs/js
source $HOME/.zshconfigs/zsh-configs/docker
source $HOME/.zshconfigs/local
```
