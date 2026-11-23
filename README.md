# KINGYTON Observatory

## О проекте / токене

Is an ecosystem token in the TON blockchain with a large Telegram community.

Самоописание из метаданных токена; заявления проекта не проверены независимо.

Источники (проверены 2026-11-23):

- <https://kingy.wtf> — официальный сайт содержит ссылку на этот контракт и канал.
- <https://tonapi.io/v2/jettons/EQC-tdRjjoYMz3MXKW4pj95bNZgvRyWwZ23Jix3ph7guvHxJ>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Снимок содержит реальные данные KINGY из TonAPI и GeckoTerminal. Исторические данные и проверки доменов накапливаются постепенно; полнота и актуальность указаны в снимке.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
GitHub Actions: резервное расписание на 07 и 37 минут каждого часа (UTC); запуск может задерживаться. Подключение к общему Cloudflare-планировщику не подтверждено.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.
