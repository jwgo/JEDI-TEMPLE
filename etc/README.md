## brew가 오늘따라 말을 듣지 않는다...

```bash
sudo chown -R $(whoami) $(brew --prefix)/*
brew doctor
brew prune
```

편안...

