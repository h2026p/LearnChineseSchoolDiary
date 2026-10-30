# 🚀 中文日记 · Китайский Дневник (zhōngwén rìjì)

---

## 🇷🇺 Русский

### 📋 Основные характеристики
- **Версия:** v2.0 (Full-Stack)
- **Тип:** Электронный дневник
- **Предметы:** Китайский язык (中文) и другие языки
- **Языки интерфейса:** Русский
- **Бэкенд:** Xano (PostgreSQL, REST API, JWT Auth)
- **Фронтенд:** HTML5, CSS3, Vanilla JavaScript
- **Privacy:** Имеется
- **Статус:** BETA-версия
- **Дата создания:** 29.10.2026
- **Последнее обновление:** 30.10.2026
- **Разработчик:** h2026p
- **AI Coding Assistants:** DeepSeek-V4-Pro & Xano Agent

### 📝 Описание проекта
**中文日记 (Китайский Дневник)** — это полноценная веб-платформа для школьников и преподавателей, созданная по мотивам МЭШ (Московской электронной школы).
Проект закрывает полный цикл учебного процесса: от выставления оценок и проверки домашних заданий до общения в чатах и привязки учеников к учителям по реферальным кодам.
Интерфейс выполнен в современном стиле с использованием градиентов, плавных анимаций и адаптивной верстки для мобильных устройств.

### ✨ Ключевые возможности
- **Роли пользователей:** Ученик, Учитель, Модератор и даже «Призрак» (одноразовый аккаунт-невидимка на 1 час).
- **Электронный журнал:** Выставление оценок (2-5) с возможностью оставлять текстовые комментарии (за что оценка).
- **Домашние задания:** Публикация ДЗ с дедлайнами, текстом и прикреплёнными ссылками.
- **Система реферальных кодов:** Учителя генерируют до 3 уникальных кодов, по которым ученики привязываются к классу.
- **Мультичат:** Общение один-на-один, групповые чаты и личный дневник (заметки для себя).
- **Панель модератора:** Управление аккаунтами, бан/разбан пользователей, загрузка видеоуроков.
- **Безопасность:** Защита секретного кода модератора (PBKDF2), JWT-авторизация и изоляция данных на стороне Xano.

### 🔄 История обновлений
#### v2.0 (30.10.2026 20:30) — Full-Stack
- 🔌 **Интеграция с Xano:** Полностью переписан фронтенд под REST API. Удален `localStorage` для критических данных.
- 🛡️ **Безопасность:** Внедрена JWT-авторизация, настроен CORS, добавлена защита от брутфорса для секретных кодов.
- 💬 **Чат:** Реализованы личные, групповые чаты и режим «заметки для себя» с выбором участников.
- 🔑 **Реферальная система:** создана реферальная система.
- 👻 **Роль «Призрак»:** Добавлена роль "Призрак".
- ⚙️ **Настройки профиля:** Созданы базовые настройки профиля.
- 🎨 **UI/UX:** Полностью обновлен дизайн (стиль МЭШ), добавлены красивые градиенты, тени, анимации и иконки.
- 📄 **Юридическая часть:** Добавлен `privacy` и локальный Cookie-баннер.
- 🐛 **Исправления:** Устранены баги с рендерингом списка оценок и отображением имен отправителей в чате.
- 🔗 **Прикрепление медиа:** Добавлена возможность прикреплять медиафайлы к ДЗ.

#### v1.0 (30.10.2026 15:00) — Первое обновление!
- Создан базовый макет и структура дневника.
- Реализована локальная авторизация и выставление оценок.
- Добавлены базовые разделы: Главная, Расписание, Оценки.
- Добавлен фавикон.
- Дописан Frontend.

---

## 🇺🇸 English

### 📋 Specifications
- **Version:** v2.0 (Full-Stack)
- **Type:** Electronic Diary
- **Subjects:** Chinese language (中文) and other languages
- **Interface Languages:** Russian
- **Backend:** Xano (PostgreSQL, REST API, JWT Auth)
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Privacy:** Available
- **Status:** BETA version
- **Created on:** October 29, 2026
- **Last updated:** October 30, 2026
- **Developer:** h2026p
- **AI Coding Assistants:** DeepSeek-V4-Pro & Xano Agent

### 📝 Project Description
**中文日记 (Chinese Diary)** is a comprehensive web platform for students and teachers, heavily inspired by the Moscow Electronic School (MESH) system.
The project covers the entire educational cycle: from grading and homework assignments to chatting and linking students to teachers via referral codes.
The interface features a modern design with gradients, smooth animations, and fully responsive layouts for mobile devices.

### ✨ Key Features
- **User Roles:** Student, Teacher, Moderator, and "Ghost" (a one-time invisible account lasting 1 hour).
- **Electronic Gradebook:** Assigning grades (2-5) with the ability to leave textual comments explaining the grade.
- **Homework:** Publishing assignments with deadlines, descriptions, and attached links.
- **Referral Code System:** Teachers generate up to 3 unique codes that students use to link to their class.
- **Multi-Chat:** One-on-one messaging, group chats, and a personal diary (notes to self).
- **Moderator Panel:** Account management, user ban/unban, and uploading video lessons.
- **Security:** Moderator secret code protection (PBKDF2), JWT authorization, and data isolation on the Xano side.

### 🔄 Changelog
#### v2.0 (October 30, 2026 20:30) — Full-Stack
- 🔌 **Xano Integration:** Completely rewritten frontend to use REST API. Removed `localStorage` for critical data.
- 🛡️ **Security:** Implemented JWT authorization, configured CORS, added brute-force protection for secret codes.
- 💬 **Chat:** Implemented direct, group chats, and "notes to self" mode with member selection.
- 🔑 **Referral System:** Referral system created.
- 👻 **"Ghost" Role:** Added the "Ghost" role.
- ⚙️ **Profile Settings:** Basic profile settings created.
- 🎨 **UI/UX:** Completely revamped design (MESH style), added beautiful gradients, shadows, animations, and icons.
- 📄 **Legal:** Added `privacy` and a local Cookie banner.
- 🐛 **Fixes:** Fixed bugs with grade list rendering and sender names in chat.
- 🔗 **Media Attachment:** Added the ability to attach media files to homework.

#### v1.0 (October 30, 2026 15:00) — First Update!
- Created the basic layout and diary structure.
- Implemented local authorization and grading.
- Added basic sections: Dashboard, Schedule, Grades.
- Added favicon.
- Frontend completed.

---

## 🇨🇳 中文

### 📋 规格说明
- **版本:** v2.0 (全栈)
- **类型:** 电子日记
- **学科:** 中文 (Chinese) 及其他语言
- **界面语言:** 俄语
- **后端:** Xano (PostgreSQL, REST API, JWT Auth)
- **前端:** HTML5, CSS3, 原生 JavaScript
- **隐私政策:** 已提供
- **状态:** BETA 测试版
- **创建日期:** 2026年10月29日
- **最后更新:** 2026年10月30日
- **开发者:** h2026p
- **AI 编程助手:** DeepSeek-V4-Pro & Xano Agent

### 📝 项目描述
**中文日记** 是一个面向学生和教师的综合性网络平台，灵感来源于莫斯科电子学校 (MESH) 系统。
该项目覆盖了完整的教育周期：从评分和作业布置，到聊天以及通过推荐码将学生绑定到教师。
界面采用现代设计，包含渐变色彩、平滑动画，并完全适配移动端设备。

### ✨ 核心功能
- **用户角色:** 学生、教师、管理员以及“幽灵”（Ghost——有效期仅1小时的临时隐形账号）。
- **电子成绩册:** 评分（2-5分）并可留下文字评语说明评分理由。
- **家庭作业:** 发布带有截止日期、描述和附件的作业。
- **推荐码系统:** 教师最多可生成3个唯一代码，学生使用代码绑定班级。
- **多重聊天:** 一对一私聊、群聊以及个人日记（给自己留言）。
- **管理员面板:** 账号管理、封禁/解封用户以及上传教学视频。
- **安全性:** 管理员密钥保护 (PBKDF2)、JWT 授权以及 Xano 端的数据隔离。

### 🔄 更新日志
#### v2.0 (2026年10月30日 20:30) — 全栈更新
- 🔌 **Xano 集成:** 前端完全重写以使用 REST API。移除了关键数据的 `localStorage`。
- 🛡️ **安全:** 实现了 JWT 授权，配置了 CORS，为密钥添加了防暴力破解保护。
- 💬 **聊天:** 实现了私聊、群聊以及可选择成员的“个人日记”模式。
- 🔑 **推荐系统:** 创建了推荐系统。
- 👻 **“幽灵”角色:** 添加了“幽灵”角色。
- ⚙️ **个人资料设置:** 创建了基础的个人资料设置。
- 🎨 **UI/UX:** 完全更新了设计（MESH风格），添加了漂亮的渐变、阴影、动画和图标。
- 📄 **法律:** 添加了 `privacy` 页面和本地 Cookie 提示横幅。
- 🐛 **修复:** 修复了成绩列表渲染和聊天中发送者姓名的错误。
- 🔗 **媒体附件:** 添加了将媒体文件附加到作业的功能。

#### v1.0 (2026年10月30日 15:00) — 首次更新！
- 创建了基本布局和日记结构。
- 实现了本地授权和评分功能。
- 添加了基本板块：主页、课程表、成绩。
- 添加了网站图标 (favicon)。
- 完成了前端开发。
