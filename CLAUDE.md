# Fulmo profile repository

## Назначение

Репозиторий хранит профиль, резюме и portfolio-представление Fulmo. Markdown — source
of truth там, где рядом лежат generated HTML, DOCX или PDF.

## Рабочий процесс

Изменение начинается с объяснимого diff и PR. В PR указываются зачем, что изменено,
как проверено и какие generated artifacts обновлены. После merge локальный clone
обновляется, а GitHub Pages или другой publication path проверяется отдельно.

## Безопасность

Не коммитить секреты, cookies, credentials, приватные ссылки и временные файлы.
Персональные данные в публичных материалах публиковать только если они уже являются
осознанной частью profile repository.

## Документы

REVIEW.md содержит обязательные review-фронты; README-LOCAL.md — локальный цикл;
MEMORY.md — краткие факты без секретов; CHANGELOG.md — историю изменений.
