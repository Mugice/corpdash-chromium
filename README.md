# corpdash-chromium

Готовые бинарники для чекера CorpDash (Playwright в закрытой сети). Оба — свободно распространяемые.

## chrome-headless-shell-linux64.tar.xz
Chrome for Testing **153.0.8010.12** = playwright chromium **v1243**, linux/amd64 (целым файлом).
```bash
python3 -c "import tarfile; tarfile.open('chrome-headless-shell-linux64.tar.xz','r:xz').extractall('/opt')"
chmod +x /opt/chrome-headless-shell-linux64/chrome-headless-shell
```

## node-linux-x64.tar.xz
Node.js **v22.23.3** linux-x64 (vite 8 требует node>=20.19).
```bash
python3 -c "import tarfile; tarfile.open('node-linux-x64.tar.xz','r:xz').extractall('/opt')"
export PATH=/opt/node-v22.23.3-linux-x64/bin:$PATH
```
