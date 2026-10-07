### Привет, я Влад 👋

**Junior ML / Data Scientist** из Москвы, студент 2 курса РТУ МИРЭА (программная инженерия).

Мне интересны LLM-приложения: RAG, агенты, тулы, память. ML-проекты стараюсь доводить до рабочего
сервиса: от анализа данных и обучения модели до API, интерфейса и деплоя.

- 🏆 Призёр **True Tech Hack от МТС** (апрель 2026): в команде делал роутер запросов к LLM и голосовой
  пайплайн ASR → LLM → TTS ([true_tech](https://github.com/aeondf/true_tech))
- 🔭 Сейчас делаю RAG-ассистента по учебным материалам и MCP-сервер к API hh.ru
- 💬 Telegram: [@pogl6](https://t.me/pogl6) · ✉️ vladkosolapovpogba@gmail.com

---

### 🤖 LLM, агенты и RAG

| Проект | Что это | Стек |
|---|---|---|
| [**Study Assistant**](https://github.com/pogl2007/langGraph_studyAssistant) | Отвечает на вопросы только по загруженным лекциям, со ссылкой на файл и страницу. Если ответа в материалах нет, так и говорит. Сейчас MVP, дальше гибридный поиск, реранкер и LangGraph | Qdrant, bge-m3, Ollama / vLLM, Streamlit, Docker |
| [**career-mcp**](https://github.com/pogl2007/career_mcp) | MCP-сервер к официальному API hh.ru: поиск вакансий, срез рынка по навыкам и зарплатам, сравнение резюме с вакансией, план подготовки к собесу. Работает с живым API, только на чтение | FastMCP, LangGraph, httpx, pytest |
| [**DATAPOST**](https://github.com/pogl2007/datapost) · [datapostai.ru](https://datapostai.ru) | Аудит датасета перед обучением: пропуски, дубликаты, выбросы, дисбаланс, утечка таргета. LLM объясняет проблемы, есть чат по датасету и автоочистка. Если LLM недоступна, работает rule-based аудит | FastAPI, pandas, OpenAI API, Next.js |
| [**GRIND ML**](https://github.com/pogl2007/grind-ml) · [grindml.ru](https://grindml.ru) | AI-симулятор технических собеседований по ML и Data Science со стримингом ответов | Next.js, OpenAI, Vercel AI SDK, Prisma |
| [**Госплан: Диалог эпох**](https://github.com/pogl2007/history-bot) | Telegram-бот, исторический симулятор: игрок становится министром пятилетки и спорит с NPC-министрами на LLM | aiogram 3, OpenAI API, Redis |

### 📊 Классический ML и DL

| Проект | Что это | Стек |
|---|---|---|
| [**PIPEFORGE**](https://github.com/pogl2007/pipeforge) | Конструктор ML-пайплайнов из блоков. Сервис сам обучает модель, подбирает гиперпараметры (Optuna, CV) и объясняет её через SHAP, а потом выгружает модель и код пайплайна | FastAPI, scikit-learn, XGBoost, LightGBM, CatBoost, Optuna, SHAP |
| [**EMOTIX**](https://github.com/pogl2007/emotix) | Распознавание эмоций на фото и видео: дообученный ResNet-18 на FER-2013, 7 классов | PyTorch, FastAPI, Next.js |
| [**MEMORIX**](https://github.com/pogl2007/memorix) | Исследование катастрофического забывания: naive, random replay и replay, которым управляет LLM-учитель. Эксперименты на MNIST и CIFAR-10 | PyTorch, FastAPI, WebSocket, Jupyter |
| [**EPL Predictor**](https://github.com/pogl2007/epl-predictor) | Прогноз исходов матчей АПЛ: 19 признаков формы и статистики команд, 1 061 матч, тесты в GitHub Actions | XGBoost, pandas, pytest |

### ⚙️ Бэкенд и веб

| Проект | Что это | Стек |
|---|---|---|
| [**Атмосфера Мебель**](https://github.com/pogl2007/atmosheremeb) · [atmospheremeb.ru](https://atmospheremeb.ru) | Сайт мебельной мастерской в продакшене: каталог на 137 моделей, заявки, ИИ-консультант, админка. Статическая сборка в 148 страниц и небольшой бэкенд для заявок и админки | SQLite, HTML/CSS/JS |
| [**Wallet API**](https://github.com/pogl2007/wallet) | REST API кошельков: 10 эндпоинтов, JWT, асинхронный PostgreSQL, миграции, тесты с подменой БД | FastAPI, SQLAlchemy 2.0, Alembic, Docker, pytest |

---

### 🛠 Стек

**ML и DL:** PyTorch · scikit-learn · XGBoost · LightGBM · CatBoost · Optuna · SHAP · pandas · NumPy

**NLP и LLM:** Hugging Face Transformers · sentence-transformers · OpenAI API · vLLM · Ollama · Pydantic AI · Whisper / faster-whisper · edge-tts

**Агенты и RAG:** LangChain · LangGraph · LlamaIndex · CrewAI · FastMCP · Qdrant · pgvector · Chroma · FAISS

**Бэкенд и инструменты:** FastAPI · SQLAlchemy 2.0 · Alembic · PostgreSQL · Redis · Docker · pytest · Linux · Git · Streamlit

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,postgres,redis,docker,linux,ts,nextjs,git" />
</p>
