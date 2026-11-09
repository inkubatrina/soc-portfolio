# SOC Analyst Portfolio

Портфолио начинающего аналитика SOC / Blue Team. Здесь я собираю практические разборы алертов, phishing-писем и учебные лаборатории — с IOC, сопоставлением с MITRE ATT&CK и обоснованным вердиктом.

**Цель:** Junior SOC Analyst / SOC Analyst L1
**Начало обучения:** октябрь 2026
**Формат:** бесплатные платформы и открытые материалы

## Что уже сделано

| # | Работа | Тип | Платформа | Ключевые навыки |
|---|--------|-----|-----------|-----------------|
| 1 | [Alert triage: попытка несанкционированного доступа (SOC325)](01-alert-triage/case-001.md) | Разбор алерта | LetsDefend | Triage, IOC, VirusTotal, AbuseIPDB, MITRE ATT&CK, verdict |
| 2 | [Phishing: «Бесплатный купон на кофе»](02-phishing-analysis/case-001.md) | Анализ письма | LetsDefend | Анализ заголовков и вложений, IOC, VirusTotal, verdict |

Оба кейса — учебные лаборатории. Реальные логи, персональные данные, токены и ключи в репозитории не публикуются.

## Навыки

**Применял на практике:**
- Alert triage и определение verdict (True Positive / False Positive / Needs Investigation)
- Сбор и анализ IOC: IP, домены, URL, хеши
- Проверка репутации в VirusTotal и AbuseIPDB
- Сопоставление активности с MITRE ATT&CK
- Анализ phishing-писем, заголовков и вложений

**Изучаю:**
- SIEM: Splunk, Elastic, Wazuh
- Detection engineering: Sigma, YARA
- Threat hunting и incident response
- Автоматизация SOC: SOAR, API, Python

## Структура репозитория

| Папка | Содержание | Статус |
|-------|------------|--------|
| [`01-alert-triage`](01-alert-triage/) | Разбор и расследование security alerts | 1 кейс |
| [`02-phishing-analysis`](02-phishing-analysis/) | Анализ фишинговых писем, URL и вложений | 1 кейс |
| [`03-siem-incident-response`](03-siem-incident-response/) | Расследования в SIEM, timeline инцидента | в плане |
| [`04-ransomware-forensics`](04-ransomware-forensics/) | Forensic-анализ и расследование ransomware | в плане |
| [`05-threat-hunting`](05-threat-hunting/) | Гипотезы, запросы и hunt reports | в плане |
| [`06-detection-engineering`](06-detection-engineering/) | Sigma- и YARA-правила, детекты | в плане |
| [`07-soar-automation`](07-soar-automation/) | Автоматизация SOC-процессов | в плане |

## План обучения

- [Roadmap на 12 недель](notes/ROADMAP.md)
- [Бесплатные ресурсы для обучения](notes/RESOURCES.md)
- [Дневник обучения](notes/learning-log.md)

## Принципы

- Каждый кейс содержит IOC, ход расследования, вердикт и выводы.
- Источники данных — только учебные лаборатории.
- Отделяю факты от предположений и явно помечаю, что ещё в процессе.

## Контакты

- GitHub: [@inkubatrina](https://github.com/inkubatrina)
