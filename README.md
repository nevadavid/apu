# APU ⚡ (Aliases that are Probably Useful)

## 💾 File system
| Alias | Command |
|-|-|
| ll    | ls -lAGh |
| ..    | cd .. |
| ...   | cd ../.. |

## 🐳 Docker
| Alias | Command |
|-|-|
| docp  | docker-compose ps |
| doce  | docker-compose exec |
| doc   | docker-compose |

## 🔥 Git
| Alias | Command |
|-|-|
| gpom  | git pull origin master |
| gco  | git checkout -b |
| ga   | git add . |
| gc   | git commit -m |
| gs   | git status |
| gf   | git fetch |
| gp   | git push origin $(git rev-parse --abbrev-ref HEAD) |

## 📟 Node
| Alias | Command |
|-|-|
| node-lts  | nvm install --lts && $NODE_LTS=node -v && nvm alias default $NODE_LTS |

## 📡 IP
| Alias | Command |
|-|-|
| ip  | curl ipinfo.io/ip |

### 🔩 How to use 
#### 🧹 Temporary alias (for the current terminal session only)
Use the alias command:

```sh
alias myalias='command'
```

Example:

```sh
alias ll='ls -lah'
```

This alias will only work until you close the terminal.

#### 📌 Permanent alias (for all future terminal sessions)

You need to add the alias to your shell configuration file.

The file name depends on which shell you are using:

Bash: `~/.bashrc` or `~/.bash_aliases`
Zsh: `~/.zshrc`
Fish: `~/.config/fish/config.fish`

For Bash or Zsh:

```sh
echo "alias ll='ls -lah'" >> ~/.bashrc
source ~/.bashrc  # or `source ~/.zshrc` if you're using Zsh
```

For Fish:

```sh
echo "alias ll 'ls -lah'" >> ~/.config/fish/config.fish
source ~/.config/fish/config.fish
```

Now, the alias will be available every time you open a new terminal. 🚀
