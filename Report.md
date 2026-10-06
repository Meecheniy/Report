# Оценка EverBank по DSOMM

**Дата:** 2026-10-06
**Команда:** (EverBank)

## Что закрыто на уровне 1

### Build and Deployment

- Build: автоматизированная сборка через GitLab CI + Buildah.
- Deployment: автоматизированный деплой на боевую через docker compose.

### Implementation

- Infrastructure Hardening: Terraform + CIS-роль, firewall на уровне облака, SSH только для demo.
- Development & Source Control

## Что закроем до конца курса

1. **SAST** — Static depth for applications.
2. **DAST** — Dynamic depth for applications.
3. **Управление уязвимостями** — Consolidation.
4. **SCA** — Static depth for applications.
5. **IaC** - Static depth for infrastructure.
6. Application Hardening.
