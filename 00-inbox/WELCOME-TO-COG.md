---
type: guide
created: 2026-10-13
tags: ["#welcome", "#getting-started", "#cog"]
---

# Welcome to Your COG Second Brain, Алексей!

Your COG is now personalized and ready to use. Here's how to get started:

## Your Profile Documents

- **[[MY-PROFILE]]** - Your basic info, role pack, and workflow preferences
- **[[MY-INTERESTS]]** - Topics for your daily briefs
- **[[MY-INTEGRATIONS]]** - Your active and disabled integrations

**You can edit these files anytime.** COG reads them when you use skills, so your changes take effect immediately.

## Skills for Your Role

As a **Founder** (solo founder of your own teaching business), these skills are ordered by relevance for you. Skills that depend on integrations (team-brief, comprehensive-analysis) are moved down, because no integrations are active yet.

1. **daily-brief** — Новости по тестированию, автоматизации, edtech и продаже курсов
2. **braindump** — Быстро записать идеи по курсам, сайту и системе учёта студентов; COG сам разложит их по проектам
3. **weekly-checkin** — Еженедельный обзор: прогресс по проектам, обучению и продажам
4. **knowledge-consolidation** — Собрать разрозненные заметки в программы курсов, методики и журнал решений
5. **url-dump** — Сохранять статьи и инструменты с автоматически извлечёнными выводами
6. **meeting-transcript** — Разбор записей созвонов со студентами или партнёрами: решения и задачи
7. **comprehensive-analysis** — Глубокий анализ за 7 дней; полезнее после подключения интеграций
8. **team-brief** — Ежедневная сводка по GitHub/Linear/Slack; требует интеграций
9. **update-cog** — Keep your COG framework current

## Your Integrations

Активная интеграция: **Telegram** (бот `barancev_claude_bot`). Добавить или отключить интеграции можно в `00-inbox/MY-INTEGRATIONS.md`.

## Quick Start

### 1. Daily Morning Routine
Invoke the daily-brief skill to get your personalized intelligence briefing covering:
- Тестирование ПО и обучение тестировщиков
- Автоматизация тестирования
- AI в тестировании
- AI в образовании
- Онлайн-образование и edtech
- Продажа и маркетинг онлайн-курсов
- Home Assistant и умный дом

### 2. Capture Your Thoughts
Use the braindump skill to quickly capture ideas, insights, and thoughts. Your braindumps will automatically be categorized into personal, professional, or project domains.

Choose from your active projects:
- [[04-projects/courses/PROJECT-OVERVIEW|Разработка и доработка курсов]]
- [[04-projects/stqa-infrastructure/PROJECT-OVERVIEW|Инфраструктура software-testing.ru]]
- [[04-projects/home-maintenance/PROJECT-OVERVIEW|Обслуживание дома]]

### 3. Weekly Reflection
Every week, use the weekly-checkin skill to review your week's insights and patterns.

## How COG Uses Your Profile

**Daily Briefs**: Uses [[MY-INTERESTS]] to curate relevant news
**Braindumps**: Offers your projects from [[MY-PROFILE]] as options
**Weekly Check-ins**: Reviews progress across your domains

## Next Steps

1. **Try your first braindump**: Use the braindump skill and start writing
2. **Get your daily brief**: Invoke the daily-brief skill to see curated intelligence
3. **Explore your vault**: All your files are organized in the sidebar
4. **Edit your profile**: Open [[MY-PROFILE]] and customize anytime

## Keeping COG Updated

COG separates your content from framework files. When new versions are released:
- Run `/update-cog` to check for and apply updates
- Or use the shell script: `./cog-update.sh --check`
- Your braindumps, profiles, and notes are **never** touched by updates

Check your current version: `cat COG-VERSION`

## Tips for Success

- **Don't overthink it**: Just dump your thoughts, COG will help organize
- **Be consistent**: Daily briefs and braindumps work best as habits
- **Review weekly**: Use the weekly-checkin skill to see patterns emerge
- **Evolve your setup**: Edit your profile files anytime or run onboarding again to add projects
- **Stay updated**: Run `/update-cog` periodically to get new skills and improvements

## Getting Help

- Check `SETUP.md` for detailed guides
- Visit the GitHub repo for documentation

**Your second brain is learning about you. Let's begin!**

---

*You can archive or delete this welcome guide once you're comfortable with COG.*
