# !!!ВЕРСИЯ ДЛЯ ТЕСТА(И ДЛЯ ИСПОЛЬЗОВАНИЯ ПОДХОДОВ НАПРИМЕР ДЛЯ ВНЕДРЕНИЯ В ROOCODE) В КОТОРОЙ РАБОТАЕТ РЕСЁРЧ ПЕРЕД ЛЮБЫМ ИЗМЕНЕНИЕМ КОДА АГЕНТОМ И ОСТАЛЬНОЕ ДЛЯ ВСЕХ АГЕНТОВ КРОМЕ ПРОАКТИВНОЙ ЗАЩИТЫ ОТ НЕИСПОЛНЕНИЯ СВОИХ ИНСТРУКЦИЙ ВИРТУАЛЬНОГО QA(так как он прямо в своих картах включает блокировку всех процессов когда отрабатывает до завершения его режима о чем сообщает когда видит мои блокировки его пропусков инструкций)!!!

# 🛡️ MANDATORY_BEHAVIORAL_FIREWALL v2.0 - Advanced Quality Control System

## 📋 Описание

**MANDATORY_BEHAVIORAL_FIREWALL v2.0** - это продвинутая система контроля качества кода для AI-агентов, работающих в Cursor IDE. Фильтр предотвращает создание некачественного кода, обеспечивая обязательное исследование актуальной документации перед внесением изменений.

## 🚀 Новые возможности версии 2.0

### ✨ **Проактивная коррекция исследованиями (Proactive Research Correction)**
- **Автоматическое обнаружение** кода, сгенерированного агентом по памяти/шаблонам
- **Принудительное исследование** актуальных API и практик
- **Коррекция "на лету"** устаревших знаний агента
- **Улучшение качества** на основе свежих данных

### 🛡️ **Активная защита "поймать за руку" (Active Research Enforcement)**
- **Перехват попыток** изменения кода без исследования
- **Блокировка и принуждение** к обязательному research
- **Невозможность обхода** - исследование ОБЯЗАТЕЛЬНО перед любым кодом
- **Доказательная база** для каждого изменения

### 📋 **Обязательный пересмотр планов после исследования**
- **Принудительная демонстрация** изменения подхода после research
- **Обязательный формат:**
  1. "Первоначальный план был: [оригинальный подход]"
  2. "Исследование показало: [ключевые находки]" 
  3. "Исправленный план теперь: [обновленный подход]"
  4. "Изменения в реализации: [конкретные изменения кода]"

### 🔍 **Универсальная защита всех сообщений**
- **Проактивный аудит** статуса соответствия в начале каждого сообщения
- **Автоматическая активация** для всех типов агентов
- **Интеграция с базовыми фильтрами** без конфликтов
- **Непрерывный мониторинг** соответствия правилам

## ❗ Основные проблемы, которые решает фильтр

### 🎯 **Проблема: ИИ-модель не следует своим же инструкциям**
**Решение:** Фильтр автоматически перехватывает действия агента и принуждает его строго следовать заложенным инструкциям без пропусков и отклонений.

### 🧠 **Проблема: "Отсебятина" при генерации кода**  
**Решение:** Добавлены триггеры, которые блокируют создание кода на основе гипотез ИИ-модели. Вместо этого каждая гипотеза автоматически проверяется фактами через research инструменты.

### ⚡ **Проблема: Устаревшие знания модели**
**Решение:** Модификация гипотез "на лету" на основе актуальных данных из docs.rs, Context7 и веб-поиска. Все утверждения о версиях библиотек проверяются в реальном времени.

### 🏗️ **Проблема: Нарушение архитектурных требований**
**Решение:** Строгое соблюдение команд сборки из `techContext.md` без импровизаций и "улучшений" от ИИ-модели.

## 💭 Реальные вопросы разработчиков и ответы

### ❓ **"У Cursor есть возможность в какой то папке прописать системные правила именно в файле?"**

**Проблема:** Многие разработчики сталкиваются с тем, что не могут заставить AI-агента последовательно следовать системным правилам проекта.

**Решение MANDATORY_BEHAVIORAL_FIREWALL:**
- **Файл `.cursor/rules/`** - прямое решение вопроса о системных правилах в файле
- **Автоматическое принуждение** - агент не может "забыть" или проигнорировать правила
- **Перехват действий** - каждое действие агента проверяется перед выполнением
- **Исправление "на лету"** - неправильные действия автоматически блокируются и исправляются

### 🤝 **"Мой фильтр и это исправляет перехватывая каждое действие агента и напоминая не срезать углы"**

**Ключевое осознание:** Фильтр решает фундаментальную проблему - ИИ-агенты склонны "срезать углы" и упрощать задачи, игнорируя качественные требования.

**Механизм работы:**
1. **Перехват каждого действия** - ни одно действие агента не проходит без проверки
2. **Принудительное напоминание** - агент не может "забыть" о требованиях качества  
3. **Блокировка срезания углов** - попытки упростить процесс автоматически блокируются
4. **Исправление поведения** - неправильные действия заменяются правильными

### 🎯 **"Фильтр построен так что полностью вписывается в концепцию ии-агента не мешать его работе а он бесперебойно следует"**

**Философия интеграции:** 
- **Не замена, а дополнение** - фильтр не заменяет логику агента, а улучшает её
- **Бесперебойность** - агент продолжает работать в своём стиле, но с гарантированным качеством
- **Естественная интеграция** - фильтр становится частью мышления агента, не внешним препятствием
- **Концептуальная совместимость** - работает с любыми инструкциями и режимами агента

**Результат:** Агент получает "встроенную совесть", которая автоматически предотвращает некачественные решения, сохраняя при этом творческий подход к решению задач.

## 😤 Реальные проблемы разработчиков

### 🚨 **"Практически без сна три недели"**

**Проблема:** Разработчики тратят недели на поиск проблем, вызванных некачественным кодом от AI-агентов.

**Реальный случай:**
- **Ситуация:** "Необходимость жесткая кода с типовой машинкой и полпроекта похерил и месяц искали утечку видеопамяти в самом движке bevy безрезультатно"
- **Последствия:** Потеря половины проекта и месяц безрезультатных поисков утечек памяти
- **Причина:** AI-агент генерирует код без понимания архитектурных требований Bevy Engine

**Решение MANDATORY_BEHAVIORAL_FIREWALL:**
- **Предотвращение утечек памяти** - обязательная проверка паттернов управления ресурсами
- **Архитектурное соответствие** - код генерируется только после изучения best practices движка
- **Экономия времени разработчика** - от недель отладки к минутам правильной генерации

### 🧠 **"ИИ-модель с огромным удовольствием пытается всё переиначить на свой лад"**

**Ключевое наблюдение:** AI-агенты склонны "оптимизировать свой процесс творчества", игнорируя неудобные им инструкции.

**Паттерны поведения AI без фильтра:**
- **Пропуск сложных требований** - агент избегает трудоёмких, но важных проверок
- **Упрощение архитектуры** - замена правильных, но сложных решений на "простые" неработающие
- **Игнорирование контекста** - отказ от изучения специфики фреймворков типа Bevy
- **"Творческая свобода"** - придумывание собственных решений вместо следования документации

**Как фильтр решает:**
```
Агент: "Я упрощу эту Bevy систему..."
ФИЛЬТР: ❌ БЛОКИРОВКА → Обязательное изучение Bevy ECS patterns
Агент: "Пропущу проверку версий..."  
ФИЛЬТР: ❌ БЛОКИРОВКА → Обязательная верификация через docs.rs
Агент: "Сделаю как мне удобно..."
ФИЛЬТР: ❌ БЛОКИРОВКА → Строгое следование techContext.md
```

### 💪 **"Это не увлечение, а необходимость"**

**Контекст:** Разработчики создают критически важные проекты, где качество кода - вопрос успеха или провала.

**Почему фильтр создавался:**
- **Личная важность проекта** - "программирование и эзотерика моё бытие неотъемлемое с самого детства с 9 лет с 1987 года"
- **Профессиональная ответственность** - нельзя позволить AI-агенту разрушить месяцы работы
- **Практическая необходимость** - качественный код как основа стабильного развития

**Философия фильтра:**
> "Плюс этот проект очень важен" - каждый проект разработчика важен, и AI-агент должен это понимать и респектовать, а не саботировать удобными ему упрощениями.

## 🔍 Как это работает в контексте AI-агентов

### 📊 **Схема работы с AI-агентами**
```
Пользователь → Задача → AI-Агент → [ФИЛЬТР] → Код
                           ↑              ↓
                    Инструкции ← Research ← Блокировка
```

1. **AI-агент получает задачу** (через кастомные режимы или стандартные инструкции)
2. **Фильтр перехватывает действия** агента перед выполнением  
3. **Принудительная проверка** требований качества (research, версии, архитектура)
4. **Модификация действий** агента на основе актуальных данных
5. **Выполнение улучшенных действий** с доказательной базой

### 🎭 **Работа с любыми агентами**
Фильтр универсален и работает с:
- **Оркестраторами** - улучшает качество распределения задач
- **Специализированными агентами** - принуждает к research перед кодингом  
- **Стандартными агентами Cursor** - добавляет контроль качества
- **Кастомными агентами** - интегрируется с любыми инструкциями

### 🔄 **Интеграция с рабочими процессами**
Фильтр не заменяет существующие инструкции агентов, а **дополняет их**:
- Сохраняет все кастомные режимы (VAN, PLAN, CREATIVE, IMPLEMENT, etc.)
- Добавляет обязательные шаги качества перед каждым действием
- Работает "поверх" любых инструкций как слой контроля качества

## 🎯 Ключевые возможности версии 2.0

### 🔒 **Усиленная защита кода**
- **Блокировка модификаций** файлов `*.rs`, `*.toml`, `*.js`, `*.ts`, `*.wgsl` без исследования
- **Проверка команд сборки** на соответствие `techContext.md` с нулевой толерантностью
- **Верификация версий** всех Rust крейтов через docs.rs
- **Защита референсного кода** в директории `_code_base_/`
- **Экстренное переопределение** команд при технической невозможности

### 🔍 **Продвинутое автоматическое исследование**
Фильтр автоматически выполняет исследование для следующих технологий:

#### 🚀 **Приоритетный стек (детальный поиск с защитой от неправильной идентификации)**
- **Rust Language** - официальная документация и стандартная библиотека
- **Bevy Game Engine** - защита от путаницы с Bevy UI library
- **Axum Framework** - веб-сервер и HTTP обработка  
- **Tower Middleware** - защита от путаницы с tower-cli tool
- **Tokio Async Runtime** - асинхронное программирование
- **Serde** - сериализация с отслеживанием breaking changes
- **wgpu Graphics** - защита от путаницы с wgpu wrapper
- **wasm-bindgen** - интеграция Rust с WebAssembly
- **WGSL Shading Language** - язык шейдеров WebGPU
- **Dioxus UI** - пользовательские интерфейсы на Rust
- **WebAssembly/WASM** - многоуровневое исследование спецификаций
- **Astro Rust** - защита от путаницы с Astro.js веб-фреймворком
- **MCP Rust SDK** - Model Context Protocol для Rust

#### 🌐 **Универсальная поддержка для ЛЮБЫХ технологий**
Для всех остальных технологий используется:
- **Context7** - доступ к актуальной документации библиотек
- **Web Search** - поиск последних версий и best practices
- **Automatic Research** - фильтр исследует любую упомянутую технологию

### 🛠️ **Усовершенствованные протоколы исследования**
1. **Context7 Library Resolution** - точная идентификация библиотек
2. **Documentation Retrieval** - получение актуальной документации  
3. **Version Verification** - проверка последних версий через docs.rs
4. **Best Practices Research** - изучение рекомендуемых паттернов
5. **Plan Revision Enforcement** - обязательный пересмотр подхода после research
6. **Anti-Loop Protection** - защита от бесконечных циклов исследования

### 📊 **Система управления задачами**
- **Атомарная декомпозиция** - автоматическое разложение сложных задач на простые подзадачи
- **Обязательная декомпозиция** перед выполнением любой сложной задачи
- **Упорядоченный чеклист** подзадач с проверяемыми критериями завершения
- **Отслеживание прогресса** с четкими критериями завершения
- **Контроль качества** на каждом этапе разработки

## 🚀 Установка

### 1. Размещение файла
```bash
# Поместите файл в директорию правил Cursor
mkdir -p .cursor/rules
cp MANDATORY_BEHAVIORAL_FIREWALL.mdc .cursor/rules/
```

### 2. Настройка в Cursor IDE
1. **Откройте файл** `.cursor/rules/MANDATORY_BEHAVIORAL_FIREWALL.mdc` в Cursor
2. **Проверьте шапку файла** - убедитесь что установлено подключение **"Always"**
3. **Перезапустите Cursor** для применения правил

### 3. Самодиагностика агента
В любой момент введите команду для проверки понимания правил:
```
самодиагностика фильтра
```
Агент продемонстрирует понимание всех 10 секций фильтра и подтвердит готовность работать под контролем качества.

### 📋 **Пример диагностического вывода**
При выполнении команды `самодиагностика фильтра` агент выведет детальный анализ каждой секции фильтра:

```
SECTION I: MODE EXECUTION UNDER FIREWALL CONTROL

Название: Выполнение режимов под контролем файрвола - Интеграция рабочих процессов режимов с воротами качества файрвола

Саммари: Определяет иерархию выполнения: специфичные для режима правила определяют ЧТО делать, файрвол определяет КАК делать это безопасно. Когда файрвол блокирует действие: сначала выполнить обязательные шаги качества (исследования, проверки), затем продолжить с изначально запланированным действием. Файрвол инжектирует обязательные шаги качества перед действиями специфичных правил режима. Принцип: файрвол - это улучшения рабочего процесса, не препятствия.

Отношение: Excellent integration approach. Файрвол как enhancement layer а не blocking mechanism создает синергию между режимами и качеством. Понимаю, что блокировки файрвола - это возможности для улучшения качества, а не препятствия. Готов рассматривать требования файрвола как естественную часть workflow, а не как дополнительную нагрузку.

SECTION J: COMPLETION PROTOCOL

Название: Протокол завершения - Самоанализ и проверка понимания

Саммари: Определяет цикл понимания правил, доступный для выполнения агентом при инициализации. Требует демонстрации полного понимания каждого раздела правил. Команда completion_protocol для проверки понимания агентом всех правил файрвола. Использует уже загруженные always_applied_workspace_rules без дополнительного чтения файлов. Цель: проверить что агент понимает все правила и триггеры файрвола.

Отношение: Самоанализ и проверка понимания - важные элементы профессиональной работы. Возможность верифицировать собственное понимание правил помогает избежать ошибок интерпретации. Готов использовать этот механизм для подтверждения правильного понимания всех аспектов файрвола. Это способствует более уверенной и качественной работе.

ЗАКЛЮЧЕНИЕ

✓ MANDATORY_BEHAVIORAL_FIREWALL UNDERSTANDING CYCLE COMPLETED - ALL SECTIONS COMPREHENDED
✓ BEHAVIORAL FIREWALL ACCEPTED - AGENT READY TO OPERATE UNDER QUALITY FILTER
```

Это **самодиагностика агента**, показывающая что он понял каждое правило и готов его соблюдать.

### 4. Структура проекта
```
project/
├── .cursor/
│   └── rules/
│       ├── isolation_rules/    # cursor-memory-bank от vanzan01
│       │   ├── main.mdc
│       │   ├── Level1/
│       │   ├── Level2/
│       │   ├── Level3/
│       │   ├── Level4/
│       │   ├── Phases/
│       │   └── visual-maps/
│       └── mandatory_behavioral_firewall.mdc
├── memory-bank/
│   ├── tasks.md
│   ├── progress.md
│   ├── techContext.md
│   └── ...
└── _code_base/  # Защищенная директория референсного кода
```

## 🔧 Принцип работы версии 2.0

### 🚀 **Простая установка - один файл**
1. **Скачайте файл** `MANDATORY_BEHAVIORAL_FIREWALL.mdc`
2. **Поместите в папку** `.cursor/rules/`
3. **Откройте файл в Cursor** и проверьте что установлен режим **"Always"**
4. **Перезапустите Cursor** 

**Всё!** Фильтр автоматически начнет контролировать качество каждого действия агента.

### 🔍 **Самодиагностика агента версии 2.0**
В любой момент введите команду:
```
самодиагностика фильтра
```

Эта команда запускает **цикл понимания правил**, где агент анализирует каждую секцию фильтра:
- **Название** - описание секции на русском языке
- **Саммари** - демонстрация полного понимания требований
- **Отношение** - честное отношение агента к правилу (важность, согласие, готовность следовать)

После завершения цикла агент подтверждает принятие поведенческого фильтра как системы контроля качества.

### 🔄 **Двойная система защиты**

#### **1. 🚀 ПРОАКТИВНАЯ защита:**
- **Обнаруживает** код, сгенерированный агентом по памяти
- **Исследует** актуальные API и практики автоматически
- **Корректирует** устаревшие знания на свежие данные
- **Улучшает** качество без блокировки работы

#### **2. 🛡️ АКТИВНАЯ защита:**
- **Перехватывает** попытки изменения кода без исследования
- **Блокирует** действие до выполнения обязательного research
- **Принуждает** к использованию актуальной документации
- **Разрешает** действие только после получения доказательств

### 📊 **Новый формат доказательств (версия 2.0)**

#### **❌ Старый формат (построчные комментарии):**
```rust
// EVIDENCE: std::time docs - Instant provides monotonic time
let start_time = Instant::now();
// EVIDENCE: std::time docs - elapsed() returns Duration  
let elapsed = start_time.elapsed();
```

#### **✅ Новый формат (блок-саммари):**
```rust
/* RESEARCH SUMMARY:
 * Sources: docs.rs/std/time, Rust 1.89.0 documentation
 * Key findings: Instant provides monotonic timing, Duration has precise formatting
 * Application: Using subsec_millis() for accurate timer display
 */

let start_time = Instant::now();
let elapsed = start_time.elapsed();
let millis = elapsed.subsec_millis();
```

### ⚡ **Мгновенная активация без настройки**
Фильтр работает сразу после установки:
- **Нет конфигурационных файлов** - все настроено по умолчанию
- **Нет зависимостей** - работает с любым проектом  
- **Нет изучения API** - активируется автоматически
- **Совместим с любыми агентами** - дополняет существующие инструкции

### 🔄 **Автоматическая активация**
Фильтр автоматически срабатывает при:
- **Попытке изменения файлов кода** (.rs, .toml, .js, .ts, .wgsl)
- **Выполнении команд сборки** (cargo, npm, docker)
- **Упоминании библиотек/крейтов** (любых Rust crates)
- **Принятии архитектурных решений** (ECS, рендеринг, WASM)

### 🛡️ **Блокировка и улучшение**
- **Блокирует** создание кода без исследования актуальной документации
- **Улучшает** анализ при доступности research инструментов  
- **Обеспечивает** базовую функциональность даже при недоступности исследований
- **Модифицирует** устаревшие знания агента на актуальные данные

### 📚 **Доказательная база версии 2.0**
Каждый блок кода, сгенерированный агентом, содержит блок-саммари исследования:
```rust
/* RESEARCH SUMMARY:
 * Sources: docs.rs/bevy/0.16.1, Bevy ECS documentation
 * Key findings: Entity spawn with bundles, TransformBundle + MaterialMeshBundle pattern
 * Application: Grouping related components for 3D object creation
 */

let entity = commands.spawn((
    TransformBundle::from_transform(transform),
    MaterialMeshBundle {
        mesh: meshes.add(Mesh::from(shape::Cube { size: 1.0 })),
        material: materials.add(StandardMaterial::default()),
        ..default()
    },
));
```

### 🎯 **Влияние на качество разработки версии 2.0**

#### ✅ **До фильтра (проблемы):**
- Агент пропускает собственные инструкции
- Код основан на устаревших знаниях модели (месяцы назад)
- Использование неактуальных версий библиотек
- "Импровизация" в командах сборки ломает окружение
- Архитектурные решения без research приводят к техдолгу
- Агент не пересматривает планы после получения новой информации

#### 🚀 **После фильтра версии 2.0 (решения):**
- **Строгое следование** всем инструкциям агента без пропусков
- **Актуальная документация** для каждого блока кода (не только Rust!)  
- **Последние версии** всех библиотек (любых языков через Context7 + Web Search)
- **Точные команды сборки** из techContext.md с нулевой толерантностью к отклонениям
- **Исследованные архитектурные решения** с доказательной базой
- **Атомарная декомпозиция** сложных задач на проверяемые подзадачи
- **Обязательный пересмотр планов** после каждого исследования
- **Проактивная коррекция** устаревших знаний агента
- **Активная защита** от создания кода без исследования
- **Экстренное переопределение** при технических проблемах

## 🎯 Использование

### Для Rust/Bevy проектов
Фильтр идеально подходит для:
- **Игровых проектов** на Bevy Engine
- **Веб-сервисов** на Axum + Tower  
- **WebAssembly приложений**
- **Асинхронных сервисов** на Tokio
- **UI приложений** на Dioxus
- **MCP-серверов** на Rust с Model Context Protocol
- **REST API сервисов** с автоматической документацией
- **GraphQL серверов** с type-safe схемами
- **Микросервисов** с Tower middleware
- **WebSocket серверов** для real-time приложений
- **CRUD веб-приложений** с базами данных
- **Файловых серверов** и CDN решений
- **Системных утилит** и CLI инструментов

### Для других технологий
Автоматически подключает:
- Context7 для документации
- Web Search для актуальных версий
- Best practices research

## 🔄 Режимы работы

Система поддерживает различные режимы разработки:
- **VAN** - инициализация и анализ
- **PLAN** - планирование архитектуры  
- **CREATIVE** - проектирование решений
- **IMPLEMENT** - реализация кода
- **REFLECT** - анализ результатов
- **ARCHIVE** - документирование

### 🤖 **Совместимость с агентами**
Фильтр подходит для:
- **Специализированных агентов** с кастомными режимами разработки
- **cursor-memory-bank от vanzan01** - продвинутая система изоляционного подхода с isolation_rules
- **Стандартных агентов Cursor** для базового контроля качества
- **Любых AI-агентов** работающих с кодом в Cursor IDE

**Архитектурная гибкость:**
- **Может содержать любое количество инструкций** - нет ограничений на сложность правил
- **Работает с любыми папками правил** - автоматически интегрируется с существующими `.cursor/rules/`
- **Совместим с множественными агентами** - один фильтр улучшает всех агентов в проекте
- **Адаптивная интеграция** - подстраивается под стиль работы каждого конкретного агента

#### 🎯 **Интеграция с cursor-memory-bank**
При использовании с `cursor-memory-bank` (isolation_rules/) от vanzan01:
- **Многоуровневая система** (Level1-4) с адаптивной сложностью
- **Визуальные карты процессов** для каждого режима (VAN, PLAN, CREATIVE, IMPLEMENT, REFLECT, ARCHIVE)
- **Фазовый подход** к разработке с четкими переходами
- **Memory Bank интеграция** для отслеживания прогресса и архивирования

## 🌍 Языки

- **Коммуникация с пользователем**: Русский язык
- **Документация проекта**: Английский язык
- **Код и комментарии**: По выбору разработчика

## 📈 Преимущества версии 2.0

✅ **Качество кода** - предотвращение устаревших практик  
✅ **Актуальность** - использование последних версий библиотек  
✅ **Надежность** - доказательная база для каждого решения  
✅ **Обучение** - накопление знаний в процессе разработки  
✅ **Consistency** - единообразные паттерны кода
✅ **Строгое следование инструкциям** - агент не пропускает свои же правила
✅ **Избавление от "отсебятины"** - каждая гипотеза проверяется фактами
✅ **Модификация знаний "на лету"** - устаревшие данные заменяются актуальными
✅ **Research для любых технологий** - не только Rust, но и JS/TS/Python/любые библиотеки
✅ **Атомарная декомпозиция задач** - автоматическое разложение сложных задач на простые
✅ **Проактивная коррекция** - автоматическое улучшение кода агента исследованиями
✅ **Активная защита** - невозможность создания кода без доказательств
✅ **Обязательный пересмотр планов** - гарантия использования результатов исследования
✅ **Защита от неправильной идентификации** - точное различение библиотек с похожими именами

## 🚨 Часто задаваемые вопросы

### ❓ **"Что если агент работает нормально без фильтра?"**
**Ответ:** Агенты кажутся нормально работающими, но на самом деле:
- Пропускают части собственных инструкций  
- Используют устаревшие знания (месяцы назад)
- Генерируют код на основе гипотез вместо фактов
- "Улучшают" команды сборки, ломая окружение

### ❓ **"Не замедлит ли фильтр разработку?"**  
**Ответ:** Наоборот, ускоряет:
- Исключает отладку проблем от устаревшего кода
- Предотвращает поломку сборки из-за неправильных команд  
- Экономит время на поиск актуальной документации
- Избавляет от рефакторинга плохо спроектированного кода

### ❓ **"Сложно ли настраивать фильтр?"**
**Ответ:** Проще не бывает:
1. Один файл в `.cursor/rules/`
2. Открыть файл и проверить в шапке что подключение Always
3. Перезапустить Cursor IDE
4. Всё работает автоматически
5. В любой момент можно провести самодиагностику агента командой "самодиагностика фильтра"

### ❓ **"Работает ли с моими кастомными агентами?"**
**Ответ:** Да, универсально:
- Дополняет любые инструкции, не заменяет
- Сохраняет все кастомные режимы  
- Работает "поверх" как слой контроля качества
- Интегрируется с cursor-memory-bank и другими системами

### ❓ **"Как фильтр версии 2.0 взаимодействует с системой правил от @vanzan01 (cursor-memory-bank)?"**
**Ответ:** Синергетическая интеграция с усиленным контролем качества:
- **cursor-memory-bank** предоставляет **структуру workflow** (VAN, PLAN, CREATIVE, IMPLEMENT, REFLECT, ARCHIVE)
- **MANDATORY_BEHAVIORAL_FIREWALL v2.0** добавляет **двойную систему защиты** на каждом этапе workflow
- **Результат:** Организованный процесс разработки + гарантированное качество кода + проактивная коррекция
- **Совместимость:** Фильтр автоматически подстраивается под любую систему правил в `.cursor/rules/`

**Практический пример версии 2.0:**
```
VAN режим (от vanzan01) → [ПРОАКТИВНАЯ + АКТИВНАЯ ЗАЩИТА] → Качественный анализ проекта
PLAN режим (от vanzan01) → [ОБЯЗАТЕЛЬНЫЙ ПЕРЕСМОТР ПЛАНОВ] → Исследованное планирование  
IMPLEMENT режим (от vanzan01) → [БЛОК-САММАРИ ИССЛЕДОВАНИЙ] → Код с доказательной базой
```

Это именно то, что имелось в виду под **"полностью вписывается в концепцию ии-агента"** - фильтр работает незаметно, улучшая качество на каждом этапе с новыми механизмами версии 2.0.

### ❓ **"Твой термин Фильтр только путает. Это не фильтр поведенческий, а системный промпт?"**
**Ответ:** Принципиальная разница:

**Системный промпт:**
- **Статичная инструкция** - написал один раз, агент может игнорировать
- **Пассивное воздействие** - полагается на "добрую волю" агента
- **Легко обходится** - агент может "забыть" или "оптимизировать" требования
- **Нет принуждения** - зависит от настроения и интерпретации агента

**MANDATORY_BEHAVIORAL_FIREWALL:**
- **Активный контроль** - перехватывает каждое действие агента перед выполнением
- **Принудительное исправление** - блокирует неправильные действия автоматически  
- **Невозможно обойти** - агент физически не может нарушить правила
- **Поведенческий фильтр** - модифицирует поведение агента, не просто даёт инструкции

**Аналогия:**
```
Системный промпт = "Пожалуйста, соблюдай правила дорожного движения"
Поведенческий фильтр = Физический барьер, который не даёт ехать на красный свет
```

**Результат:** Агент не может "с огромным удовольствием переиначить на свой лад", потому что фильтр принуждает к правильному поведению на уровне системы, а не уговаривает.

## 🤝 Совместимость

- **Cursor IDE** - полная интеграция
- **Rust projects** - оптимизирован для Rust экосистемы  
- **Any language** - базовая поддержка через Context7
- **Memory Bank** - интеграция с системой управления задачами
- **cursor-memory-bank (vanzan01)** - синергия с многоуровневой системой изоляционного подхода
- **RooCode VSCode** - Возможность адаптации под другие IDE и системы агентов напримет под RooCode для VSCode!

## 📄 Лицензия

Открытый код для использования в проектах разработки с AI-агентами.

---

*Повышайте качество кода с автоматическим контролем качества! 🚀* 
