# Review policy

Перед merge проверяется один зафиксированный diff.

- Security и privacy: секреты, PII, публичность ссылок и generated artifacts.
- Correctness: Markdown, ссылки, language switch и согласованность имени/контактов.
- Maintainability: структура разделов, source/generated boundary и навигация.
- Performance/resources: размер и формат generated files, отсутствие временного мусора.
- Types/regressions: markdown lint, генераторы, ссылки и чтение опубликованной страницы.

Quota или инфраструктурный сбой внешнего review не считается review. В отчёте фиксируются
base/head SHA, команды, результат и оставшиеся риски.
