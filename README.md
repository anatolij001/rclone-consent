# rclone-consent

Статические страницы для экрана согласия OAuth (Branding) личного клиента
rclone к Google Drive. Других функций у репозитория нет.

- `https://consent.sidorov-an.ru/` — Application home page
- `https://consent.sidorov-an.ru/privacy.html` — Application privacy policy link
- Authorized domain в Google Cloud: `sidorov-an.ru`

Хостинг: GitHub Pages, ветка `main`, корень. Кастомный домен задаётся файлом
`CNAME` (после появления DNS-записи) или полем Custom domain в настройках Pages.
DNS: `consent.sidorov-an.ru` → CNAME → `anatolij001.github.io` (панель Джино),
иначе поддомен отдаёт визитку-парковку через wildcard `*.sidorov-an.ru`.

Секретов здесь нет и быть не должно.
