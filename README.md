# inspiration — transfer buffer

Пустой по умолчанию. Это НЕ склад, а конвейер передачи картинок в Pinterest.

Как используется:
1. Перед bulk-upload сюда кладутся новые фото (`images/`) из приватного вэлта `Sync/Inspiration/images/`.
2. Генерится CSV с публичными URL `raw.githubusercontent.com/.../images/<file>`.
3. Pinterest скачивает фото к себе (re-host на pinimg) → пины на доске Hard Light.
4. Фото отсюда удаляются — репо снова пустой.

Постоянный источник правды (карточки + принципы + оригиналы фото) — приватный вэлт `Sync/Inspiration/`.
