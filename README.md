# Universal-Security-Reporter

Универсальный скрипт для сбора, анализа и уведомлений о результатах проверок безопасности.

## Возможности

- **Автопарсинг** отчетов: SonarQube, OWASP ZAP, Bandit, Flake8, JaCoCo
- **Универсальная обработка** JSON, XML, TXT форматов
- **HTML отчеты** с детальной статистикой
- **Email уведомления** через SMTP
- **Интеграция с CI/CD**

## Быстрый старт

```bash
# Установи зависимости
pip install PyYAML

# Запусти с тестовыми отчетами
python universal_parser.py --reports-dir ./reports --send-email
