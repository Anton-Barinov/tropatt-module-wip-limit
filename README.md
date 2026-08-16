# WIP Limit

Limit work-in-progress (WIP) tasks per user with live load counting, per-user limits, and overload checks.

A module for the [TropaTT](https://github.com/Anton-Barinov/TropaTT) self-hosted CRM and work platform.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**Languages:** [English](#english) · [Русский](#русский) · [中文](#中文)

## English

### About

Limit work-in-progress (WIP) tasks per user. Current WIP load is always computed live from the task list, so it never drifts. Per-user limits, configurable WIP statuses, role exclusions, overload checks on task status / assignee changes, and a WIP panel on the task detail sidebar that lets you edit the assignee's limit inline.

### Module info

| Field | Value |
|---|---|
| Module | `crm.wip-limit` |
| Version | `1.3.0` |
| Category | Productivity |
| Core | `>=1.0.0` |
| Required permissions | — |
| Author | [Anton Barinov](https://github.com/Anton-Barinov) |

### Installation

1. In TropaTT open **Admin → Modules → Install**.
2. Choose one of:
   - **Install from URL:** `https://github.com/Anton-Barinov/tropatt-module-wip-limit/releases/download/v1.3.0/crm.wip-limit-1.3.0.zip`
   - **Upload archive:** download the release `.zip` and upload it manually.
3. Activate the module and configure it in **Admin → Modules**.

### Repository layout

- `upload/` — the module itself (what gets installed).
- `LICENSE` — MIT license.
- `SECURITY.md` — how to report vulnerabilities.

### Requirements

- TropaTT (PHP 8.1+, MySQL), `core_version` `>=1.0.0`.

### License

[MIT](LICENSE) © Anton Barinov

## Русский

### О модуле

Ограничение количества задач в работе (Work In Progress) на пользователя. Текущая WIP-нагрузка всегда считается в реальном времени из списка задач, поэтому счётчик не расходится. Индивидуальные лимиты, настраиваемые статусы учёта, роли-исключения, контроль превышения при смене статуса или исполнителя задачи и панель WIP в сайдбаре карточки задачи, где лимит исполнителя можно изменить прямо на месте.

### Информация о модуле

| Поле | Значение |
|---|---|
| Модуль | `crm.wip-limit` |
| Версия | `1.3.0` |
| Категория | Продуктивность |
| Ядро | `>=1.0.0` |
| Требуемые права | — |
| Автор | [Anton Barinov](https://github.com/Anton-Barinov) |

### Установка

1. В TropaTT откройте **Админ → Модули → Установка**.
2. Выберите один из вариантов:
   - **Установка по URL:** `https://github.com/Anton-Barinov/tropatt-module-wip-limit/releases/download/v1.3.0/crm.wip-limit-1.3.0.zip`
   - **Загрузка архива:** скачайте `.zip` из релиза и загрузите вручную.
3. Активируйте модуль и настройте его в **Админ → Модули**.

### Структура репозитория

- `upload/` — сам модуль (то, что устанавливается).
- `LICENSE` — лицензия MIT.
- `SECURITY.md` — как сообщать об уязвимостях.

### Требования

- TropaTT (PHP 8.1+, MySQL), `core_version` `>=1.0.0`.

### Лицензия

[MIT](LICENSE) © Anton Barinov

## 中文

### 关于

限制每个用户进行中的任务数量。当前 WIP 负载始终直接从任务列表实时计算，因此不会出现偏差。支持按用户设置限制、自定义统计状态、排除角色，在任务状态或负责人变更时检查是否超限，并在任务详情侧边栏显示 WIP 面板，可直接在面板中修改负责人的限制。

### 模块信息

| 字段 | 值 |
|---|---|
| 模块 | `crm.wip-limit` |
| 版本 | `1.3.0` |
| 类别 | 效率 |
| 内核 | `>=1.0.0` |
| 所需权限 | — |
| 作者 | [Anton Barinov](https://github.com/Anton-Barinov) |

### 安装

1. 在 TropaTT 中打开 **管理 → 模块 → 安装**。
2. 选择以下方式之一：
   - **从 URL 安装：** `https://github.com/Anton-Barinov/tropatt-module-wip-limit/releases/download/v1.3.0/crm.wip-limit-1.3.0.zip`
   - **上传压缩包：** 下载 release 中的 `.zip` 并手动上传。
3. 在 **管理 → 模块** 中激活并配置模块。

### 仓库结构

- `upload/` — 模块本身（被安装的内容）。
- `LICENSE` — MIT 许可证。
- `SECURITY.md` — 如何报告漏洞。

### 要求

- TropaTT（PHP 8.1+、MySQL），`core_version` `>=1.0.0`。

### 许可证

[MIT](LICENSE) © Anton Barinov
