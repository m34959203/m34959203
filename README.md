<h1 align="center">Дмитрий Миронов</h1>

<p align="center">
  <b>Full-stack инженер · прикладной AI · телематика</b><br>
  Жезказган, Казахстан · UTC+5
</p>

<p align="center">
  <a href="https://technokod.kz"><img src="https://img.shields.io/badge/TechnoKod-technokod.kz-C6F24E?style=flat-square&labelColor=111111"></a>
  <a href="https://portfolio.technokod.kz"><img src="https://img.shields.io/badge/Портфолио-live-111111?style=flat-square"></a>
  <img src="https://img.shields.io/badge/RU%20·%20KK%20·%20EN-2b2b2b?style=flat-square">
</p>

---

Довожу продукты до прода целиком.

- Руководитель **Центра ИИ** Жезказганского университета им. О. А. Байконурова
- Основатель **TechnoKod** — AI-решения для организаций Казахстана

---

## В проде

| Проект | Что это | Стек |
| --- | --- | --- |
| **[Telematics Data Gateway](https://tdg.technokod.kz)** | Мультитенантный шлюз-ретранслятор телематики: приём device-протоколов с терминалов, нормализация, транскодинг, раздача потребителям | TypeScript · TCP/UDP · Postgres · Docker |
| **[Тіл-құрал](https://til-qural.kz)** | Платформа изучения казахского языка с ИИ-учителем и геймификацией | Next.js 16 · Postgres · LLM |
| **[Smart Library ЦБС](https://satlib.kz)** | Экосистема централизованной библиотечной системы: билингвальный каталог, AI-помощник, бронирование | Next.js · Postgres · Groq · TTS |
| **[Детская библиотека Сатпаев](https://dubsatpaev.kz)** | Каталог, генератор сказок, голосовой диалог, автопостинг | Next.js 16 · Postgres · Gemini |
| **[Вестник ЖезУ](https://vestnik.zhezu.kz)** | Сайт научного журнала: OJS 3.4 + собственный фронт, требования ККСОН МОН РК | Next.js · OJS REST · Vertex AI |
| **[Расчёт учебной нагрузки](https://loadcalc.zhezu.kz)** | Автоматизация распределения нагрузки кафедр: учебный план → решатель → выгрузка | Python · OR-Tools CP-SAT |
| **[TechnoKod](https://technokod.kz)** | Платформа агентства: CMS, блог, автопостинг, контроль расхода AI-бюджета | Next.js 16 · Prisma · Postgres |

Ещё около двадцати систем — CRM, биллинг для медицинской ИС, омниканальный контакт-центр, боты, генераторы отчётов — под NDA или во внутреннем контуре заказчиков.

---

## Что умею

**Телематика и промышленные протоколы**
Приём device-протоколов напрямую с терминалов (Teltonika Codec 8/12, Omnicomm), ретрансляция и транскодинг между форматами, мультитенантность, лицензирование, карантин неизвестных устройств.

**Прикладной AI**
Дообучение открытых моделей (Gemma 31B) и борьба с утечкой обучающего датасета, RAG, self-hosted инференс на Ollama, продакшн-интеграции Vertex AI / Gemini / Groq, синтез речи на русском и казахском. Псевдонимизация персональных и корпоративных данных перед отправкой в облачный LLM. Принцип: знания — детерминированно, модель — только слой формулировок.

**Бэкенд и данные**
NestJS, FastAPI, Prisma, PostgreSQL. Годовые агрегаты телеметрии, версионированная сегментация треков, доменная логика поверх шумных промышленных данных, миграции схем без простоя.

**Фронтенд**
Next.js 15/16 App Router, React 19, TypeScript strict, Tailwind v4. Двуязычные RU/KK интерфейсы, оптимизация payload дашбордов, PWA, генерация PDF и видео-роликов.

**Инфраструктура**
Docker, Caddy, PM2, Cloudflare Tunnel и Workers, GitHub Actions. Умею выжимать продакшн из 2 ГБ RAM: кеш-стратегия, снявшая 40–60 % нагрузки на CPU; тюнинг пулов соединений; деплой в ограниченные среды вроде Plesk и FastCGI.

**Безопасность**
Ротация секретов и очистка истории репозиториев, argon2 + JWT, подписанные сессионные токены для разграничения пользователей под общей учётной записью, ролевые guard'ы.

---

## Инженерные цифры

```
1000 устройств одновременно на 2 ГБ RAM,  p99 = 426 мс
 781 автотест + soak-тесты на 2000 подключений в CI
  40–60 % снижение нагрузки на CPU после кеш-стратегии
   ~20 систем доведено до продакшна в одиночку
```

---

## Стек

`TypeScript` `Python` `Next.js` `React` `NestJS` `FastAPI` `Prisma` `PostgreSQL` `Docker` `Cloudflare` `Vertex AI` `Gemini` `Ollama` `OR-Tools`

---

<p align="center">
  <a href="mailto:mdtech.top@gmail.com">mdtech.top@gmail.com</a> ·
  <a href="https://technokod.kz">technokod.kz</a> ·
  <a href="https://portfolio.technokod.kz">портфолио</a>
</p>

<p align="center"><sub>Репозитории закрыты — код клиентских и рабочих проектов под NDA. Показываю по запросу.</sub></p>
