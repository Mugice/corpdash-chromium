# corpdash-chromium

Chromium **chrome-headless-shell** для чекера CorpDash (Playwright, закрытая сеть).

- Сборка: Chrome for Testing **153.0.8010.12** = playwright chromium **v1243**, linux/amd64
- Источник: https://storage.googleapis.com/chrome-for-testing-public/153.0.8010.12/linux64/chrome-headless-shell-linux64.zip
- Файл порезан на куски <100 МБ (лимит github). Склейка:

```bash
cat chrome-headless-shell-linux64.zip.part-* > chs.zip
unzip -q chs.zip           # -> chrome-headless-shell-linux64/chrome-headless-shell
```

sha256 (склеенного zip): a9da028861a0cf789ff25c2fed45f5f1aaf969ed9247835b6a7821a4f7af9d1d
