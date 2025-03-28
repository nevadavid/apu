# APU (Aliases that are Probably Useful)

## File system
| Alias | Command |
|-|-|
| ll    | ls -lAGh |
| ..    | cd .. |
| ...   | cd ../.. |

## Docker
| Alias | Command |
|-|-|
| docp  | docker-compose ps |
| doce  | docker-compose exec |
| doc   | docker-compose |

## Git
| Alias | Command |
|-|-|
| gpom  | git pull origin master |
| gco  | git checkout -b |
| ga   | git add . |
| gc   | git commit -m |
| gs   | git status |
| gf   | git fetch |
| gp   | git push origin $(git rev-parse --abbrev-ref HEAD) |

## Node
| Alias | Command |
|-|-|
| node-lts  | nvm install --lts && $NODE_LTS=node -v && nvm alias default $NODE_LTS |

## IP
| Alias | Command |
|-|-|
| ip  | curl ipinfo.io/ip |
