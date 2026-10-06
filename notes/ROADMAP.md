# SOC Roadmap — 12 недель

Цель: получить практические навыки для Junior SOC Analyst / SOC Analyst L1
и собрать 3–5 работ, которые можно показать при откликах на вакансии.

## Недели 1–2 — Alert triage

Цель:
- Научиться разбирать алерты и выносить verdict.

Задачи:
- Зарегистрироваться в LetsDefend.
- Разобрать 15–20 security alerts.
- Для каждого алерта выписывать IP, domain, URL, hash, user, hostname, process.
- Определять verdict: True Positive, False Positive, Benign True Positive или Needs Investigation.
- Связывать события с MITRE ATT&CK.
- Сделать 2 подробных отчёта в `01-alert-triage/`.

Результат:
- 15–20 triage cases.
- 2 подробных case reports.
- Понимание IOC, evidence и escalation.

## Недели 3–4 — Phishing analysis

Цель:
- Научиться расследовать подозрительные письма.

Задачи:
- Разобрать 5–10 phishing cases на CyberDefenders или аналогичной лаборатории.
- Проверять sender, reply-to, email headers, SPF, DKIM и DMARC.
- Анализировать URL, domain, attachments и file hash.
- Вести таблицу IOC.
- Сделать один полный phishing incident report.

Результат:
- 5–10 phishing cases.
- 1 подробный phishing report.
- Понимание процесса: письмо → IOC → verdict → response.

## Недели 5–6 — SIEM и incident response

Цель:
- Научиться искать события в логах и собирать timeline инцидента.

Задачи:
- Пройти SOC/Splunk/Elastic лаборатории на TryHackMe.
- Научиться искать failed logins и successful logins.
- Разбирать PowerShell, DNS, HTTP, process creation.
- Сделать 2–3 расследования.
- Для каждого расследования собрать timeline.
- Сопоставлять поведение с MITRE ATT&CK.

Результат:
- 2–3 SIEM investigation reports.
- Первые SPL, KQL или Elastic queries.
- Умение объяснить цепочку событий.

## Недели 7–9 — Threat hunting

Цель:
- Научиться искать угрозу по гипотезе, а не ждать алерта.

Задачи:
- Написать минимум две hunting hypotheses.
- Искать подозрительное использование PowerShell.
- Проверять encoded commands и необычные parent/child processes.
- Сохранить запросы и результаты.
- Оформить два hunt reports.

Результат:
- 2 hunting reports.
- Понимание hypothesis-driven hunting.
- Набор поисковых запросов для портфолио.

## Недели 10–11 — Detection engineering

Цель:
- Научиться превращать наблюдения в правила детекта.

Задачи:
- Понять структуру Sigma rule.
- Написать 2 простых Sigma rules.
- Добавить MITRE ATT&CK tags.
- Указать false positives и severity.
- Описать, какие логи нужны для каждого правила.
- При возможности написать одну базовую YARA rule.

Результат:
- 2 Sigma rules.
- Понимание logsource, selection, condition, level и false positives.

## Неделя 12 — Портфолио и отклики

Цель:
- Подготовиться к Junior SOC Analyst / SOC Analyst L1 вакансиям.

Задачи:
- Выбрать 3–5 лучших работ из репозитория.
- Проверить, что в GitHub нет ключей, токенов, реальных логов и личных данных.
- Улучшить главный `README.md`.
- Составить резюме.
- Подготовить короткий рассказ о каждом проекте по STAR.
- Искать вакансии: Junior SOC Analyst, SOC Analyst L1, Security Operations Analyst, Cybersecurity Analyst Intern / Trainee.
- Начать отправлять отклики.

Результат:
- GitHub-портфолио.
- Резюме.
- Первые заявки на вакансии.
