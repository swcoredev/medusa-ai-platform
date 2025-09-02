# 🚀 Voice AI Marketplace

**Платформа для разработчиков и бизнеса** - где AI-ассистенты встречаются с реальными потребностями

## 🌟 Что это такое

**Voice AI Marketplace** - это инновационная платформа, которая соединяет:
- **Разработчиков AI** - создающих умных ассистентов
- **Бизнесы** - нуждающихся в автоматизации (отели, автосервисы, стоматологии)

## 🏗️ Архитектура проекта

```
medusa-ai-platform/
├── medusa-backend/          # Backend API (порт 9000)
│   ├── src/                 # Исходный код Medusa
│   ├── medusa-config.ts     # Конфигурация
│   └── package.json         # Зависимости
│
└── medusa-marketplace/      # Frontend (порт 8001)
    ├── src/                 # Next.js приложение
    ├── public/              # Статические файлы
    └── package.json         # Зависимости
```

## 🚀 Быстрый старт

### 1. Запуск Backend
```bash
cd medusa-backend
yarn install
yarn dev
```
**Результат**: API доступен на http://localhost:9000

### 2. Запуск Frontend
```bash
cd medusa-marketplace
yarn install
yarn dev
```
**Результат**: Сайт доступен на http://localhost:8001

## 🛠️ Технологии

### Backend
- **Medusa v2.10.0** - современная e-commerce платформа
- **Node.js** - среда выполнения
- **TypeScript** - типизация
- **PostgreSQL** - база данных
- **MikroORM** - ORM для работы с БД

### Frontend
- **Next.js 15** - React фреймворк с App Router
- **React 19 RC** - последняя версия React
- **Tailwind CSS** - стилизация
- **TypeScript** - типизация
- **Medusa JS SDK** - API клиент

## 📱 Основные функции

### Для разработчиков
- ✅ Регистрация и авторизация
- ✅ Создание AI-ассистентов
- ✅ Управление продуктами
- ✅ Аналитика и статистика

### Для бизнеса
- ✅ Просмотр каталога ассистентов
- ✅ Демо-версии и тестирование
- ✅ Интеграция через API
- ✅ Поддержка 24/7

## 🌐 Доступ к сервисам

- **Backend API**: http://localhost:9000
- **Admin Panel**: http://localhost:9000/app
- **Frontend**: http://localhost:8001
- **API Docs**: http://localhost:9000/store/docs

## 🔑 Переменные окружения

### Backend (.env)
```bash
DATABASE_URL=postgres://medusa_user@localhost:5432/medusa_assistant_marketplace
REDIS_URL=redis://localhost:6379
JWT_SECRET=supersecret
COOKIE_SECRET=supersecret
```

### Frontend (.env.local)
```bash
NEXT_PUBLIC_MEDUSA_API_URL=http://localhost:9000
NEXT_PUBLIC_MEDUSA_PUBLISHABLE_KEY=pk_...
```

## 🚀 Команды для разработки

### Backend
```bash
yarn dev          # Запуск в режиме разработки
yarn build        # Сборка для продакшена
yarn start        # Запуск продакшен версии
yarn seed         # Заполнение демо-данными
```

### Frontend
```bash
yarn dev          # Запуск в режиме разработки
yarn build        # Сборка для продакшена
yarn start        # Запуск продакшен версии
```

## 📊 Текущий статус

- ✅ **Базовая структура** - готова
- ✅ **E-commerce функционал** - работает
- ✅ **Лендинг-страница** - готова
- 🔄 **AI-ассистенты модуль** - в разработке
- 🔄 **Роль разработчика** - в разработке
- 🔄 **Каталог ассистентов** - в разработке

## 🤝 Вклад в проект

1. Fork репозитория
2. Создайте feature branch (`git checkout -b feature/amazing-feature`)
3. Commit изменения (`git commit -m 'Add amazing feature'`)
4. Push в branch (`git push origin feature/amazing-feature`)
5. Откройте Pull Request

## 📄 Лицензия

Этот проект лицензирован под MIT License.

## 👥 Команда

- **Геннадий** - Product Owner & Developer
- **swcoredev** - GitHub организация

## 🆘 Поддержка

Если у вас есть вопросы:
- Создайте Issue в GitHub
- Обратитесь к команде разработки
- Проверьте документацию

---

**🚀 Готово к запуску!** Выберите своего AI-ассистента и начните автоматизировать бизнес уже сегодня!

## 🔗 Ссылки

- **GitHub**: https://github.com/swcoredev/medusa-ai-platform
- **Backend API**: http://localhost:9000
- **Frontend**: http://localhost:8001 