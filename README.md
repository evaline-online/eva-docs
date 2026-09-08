# eva-docs
**Единый хаб документации EvaLine/EvaBot. Один источник правды. Ноль дублей.**

## Структура (модульная)
| Каталог | Содержимое |
|---|---|
| `architecture/` | ARCHITECTURE.md, SEPHIROT_CONSILIUM.md, GOOGLE_ECOSYSTEM_AGENT_FACTORY, CAPABILITIES_MANIFESTO.md |
| `agents/` | GLOBAL_SYSTEM_AGENTS.md — глобальные правила всех AI-агентов системы |
| `ops/` | CLOUD_TTS/STT/TRANSLATE, SECRETS_MANAGER, SAFE_DEPLOY, MODEL_REGISTRY_SYNC, TELEGRAM_BOT, OPENCODE_*, DESKTOP_AUDIT, EVALINE_ONLINE_INGEST |
| `models/` | MODELS_CATALOG, GEMINI_QUOTA_VERIFICATION |
| `domains/` | `*.unui.md` — описания 4 доменов (evabot.online, evaline.network/online/website) |
| `roadmap/` | ROADMAP.md |
| `security/` | SECURITY_AUDIT.md |
| `changelog/` | CHANGELOG.md |
| `kanban/` | KANBAN.md |
| `deployment/` | MONOREPO.md |
| `development/` | CODE_AUDIT_v0.0.2.md |
| root | GLOSSARY.md, UI_SPECIFICATION.md, COMMANDS.md, DOCUMENTATION_INDEX.md, interface*.txt |

## Правила модульности
1. Документация живёт ТОЛЬКО здесь. В кодовых репо — только README уровня модуля.
2. Отчёты — в `eva-reports` (хронология). Здесь их нет.
3. Манифесты сайтов (public/MANIFESTO.md) — контент, живёт в `evabot-online`.
4. Новые доки кладутся в свой каталог по теме; индекс обновляется.

## Связанные репозитории
evabot-online (код) · eva-reports (отчёты) · evaline-agents (worklog'и агентов)
