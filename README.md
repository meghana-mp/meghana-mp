# Hi there, I'm Meghana 👋

### 🧪 Senior Automation Engineer | 14 Years in QA | 8 Years in Test Automation | Bengaluru, India

I'm a passionate QA engineer specializing in **web, mobile, and API test automation**. I build robust frameworks, lead QA strategy, and help teams ship high-quality software with confidence — now also exploring **GenAI-powered testing** with self-healing locators and LLM-based evaluation pipelines.

---

## 🚀 About Me

- 🔭 Currently working at **Globant** as Senior Test Automation Engineer
- 🛠️ 8+ years building and scaling automation frameworks with **Selenium, Java, Appium, Rest Assured, Playwright, TypeScript, and Python**
- 🤖 Exploring **GenAI in test automation** — Claude API for self-healing locators, RAGAS for LLM evaluation
- 🎯 Focused on **test automation strategy**, CI/CD integration, and reducing regression cycle times
- 🏅 **Certified Scrum Master (PSM I)** — Scrum.org
- 💬 Ask me about **test automation strategy, framework design, AI-assisted testing, or QA best practices**

---

## 🛠️ Tech Stack

### Automation & Frameworks
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-6C63FF?style=for-the-badge&logo=appium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF6C37?style=for-the-badge&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white)
![Rest Assured](https://img.shields.io/badge/Rest_Assured-4DB33D?style=for-the-badge&logoColor=white)
![Allure](https://img.shields.io/badge/Allure_Report-FFCA28?style=for-the-badge&logo=qase&logoColor=black)

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### AI / GenAI in Testing
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-FF6F00?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-7A28F5?style=for-the-badge&logoColor=white)

### CI/CD & DevOps
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Selenium Grid](https://img.shields.io/badge/Selenium_Grid-43B02A?style=for-the-badge&logo=selenium&logoColor=white)

### Tools & Platforms
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![JIRA](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![BrowserStack](https://img.shields.io/badge/BrowserStack-FF6C37?style=for-the-badge&logo=browserstack&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

## 💼 Experience Highlights

| Role | Company | Period |
|------|---------|--------|
| Senior Test Automation Engineer | Globant | Mar 2024 – Present |
| QA Lead | Encora Inc. | Feb 2017 – Mar 2024 |
| Senior Test Analyst | Accenture India | Aug 2016 – Feb 2017 |
| Software Engineer | Tech Mahindra Ltd. | Feb 2012 – Aug 2016 |

---

## 🌟 Featured Projects

### 1. 🎭 [Selenium Automation Framework](https://github.com/meghana-mp/selenium-java-project)
**Selenium automation framework with Self-Healing**

- 🏗️ **5-layer architecture** with 10 design patterns: Page Object Model, Singleton (DCL), ThreadLocal, Factory, Template Method, Facade, Observer, Data Provider, Retry, and Self-Healing
- ⚡ **Parallel execution** via TestNG (2 threads) + ThreadLocal WebDriver isolation
- 🤖 **AI-powered self-healing locators** — Claude API (MCP integration) heals broken locators dynamically at runtime; cached for zero-cost reuse
- 🛡️ **Static + dynamic fallback** — 3-tier locator resilience (primary → static fallback → Claude API healing)
- 🐳 **Full Docker containerisation** with Seleniarm Grid for native ARM64 (Apple Silicon) support
- 🔁 **CI/CD ready** — Jenkins declarative pipeline with credential injection and Allure report publishing
- 📊 **20 end-to-end scenarios** across 10 feature domains (auth, search, booking, payment, hybrid API+UI)
- 🛠️ **Stack:** Java 21, Selenium 4.21, TestNG, RestAssured, Allure, Docker, Jenkins, Claude API

### 2. 🍛 [RAG — Evaluation Pipeline(RAGAS) ](https://github.com/meghana-mp/recipie-ragas-evaluation)
**End-to-end LLM testing framework using the RAG Triad**

- 🧪 **Custom LLM evaluation pipeline** measuring Faithfulness, Answer Relevancy, and Context Precision
- ⚖️ **Claude Sonnet 4.6 as LLM judge** plugged into RAGAS via LangChain wrapper for reliable scoring
- 🗃️ **Semantic retrieval** — ChromaDB vector store with metadata filtering and cosine similarity
- 🎯 **Golden dataset with deliberate failure rows** — sanity-checks the evaluator itself
- 📊 **Interactive Streamlit + Plotly dashboard** for results exploration
- 🧠 **Phi-4 Mini via Ollama** for free local generation — isolates RAG quality from model knowledge
- 🛠️ **Stack:** Python, Pytest, RAGAS, LangChain, Claude API, ChromaDB, Ollama, Streamlit, Plotly, SentenceTransformers

### 3. [REST Assured API Automation Framework](https://github.com/meghana-mp/rest-assured-project)
**REST API test automation framework**

- 🔐 **Multi-authentication coverage** — OAuth 2.0 Bearer Token, Cookie Session
  Token, and JWT Bearer with token refresh; each strategy includes negative tests
  confirming unauthorized access is rejected
- 📋 **JSON Schema validation** — six Draft-07 schema files enforce response
  contracts on structure, field types, enum values, and array constraints
  independently of assertion-level checks
- 🗂️ **Data-driven testing** — all test inputs externalized to JSON files;
  TestNG `@DataProvider` injects rows at runtime with no hardcoded values
  inside test methods
- 🌐 **WireMock embedded mock server** — file-based stubs loaded from
  `mappings/` at startup and programmatic stubs with body and header matching;
  call verification confirms stubs were actually reached
- 📊 **Allure reporting** — full `@Epic / @Feature / @Story / @Step` hierarchy
  with AspectJ load-time weaving; response body and diagnostic attachments
  captured on failing tests
- ⚙️ **CI/CD ready** — credentials loaded from `config.properties` with
  transparent environment variable override; no code changes needed to run
  in any pipeline
- 🛠️ **Stack** — Java 21, REST Assured 5.3.2, TestNG 7.9.0, WireMock 3.5.4,
  Allure 2.27.0, AspectJ, Lombok, Jackson, Maven

### 4. [Playwright — Python Test Automation Framework](https://github.com/meghana-mp/playwright-python-project)
**End-to-end browser automation framework**

- 🔐 **Session-scoped authentication caching** — login runs once per session; auth state is restored for every test, eliminating repeated login roundtrips across 20+ tests
- 📐 **Page Object Model with a Facade layer** — 8 page classes unified into a single PageManager container so each test declares one fixture instead of managing every page individually
- 🔄 **Data-driven and parametrized testing** — all test data lives in JSON files; boundary values, search filters, and registration cases are driven from structured data with zero hardcoded values in test code
- 🔗 **Hybrid UI and API validation** — booking flows verified at both the browser and REST API layer using a dedicated HTTP client with JWT bearer auth; API response bodies attached to the report as JSON
- 📱 **Mobile viewport testing** — a dedicated mobile fixture sets a 375×812 viewport with touch support and a mobile user agent, verifying responsive layout and hamburger navigation under real device conditions
- 🎭 **API mocking for error scenarios** — the booking API is intercepted at the network layer to test error-state notifications deterministically, without depending on live server seat availability
- 📊 **Structured Allure reporting** — every test carries severity, description, and tags; failures auto-attach a screenshot; environment metadata and failure categories are written at session start
- 🐳 **Dockerized parallel CI/CD** — six docker-compose services cover smoke, regression, parallel, and cross-browser runs; a five-stage Jenkins pipeline handles build, test, and report publishing end to end
- 🛠️ **Stack:** Python 3.12, Playwright 1.60.0, pytest, pytest-xdist, Allure, Docker, Jenkins, Faker

### 5. 📱 [Appium Mobile Test Automation Framework](https://github.com/meghana-mp/appium-java-project)
**End-to-end Android test automation framework for the SauceLabs Mobile app**

- 🏗️ **4-layer architecture** — Driver → Utility → Page Object → Test, with no layer reaching past its immediate neighbour
- 🔄 **Resilient session management** — 3-attempt retry with ANR dismissal at session init, page load, and gesture level
- 📊 **Fully data-driven** — zero hardcoded test values; all inputs sourced from JSON via a fluent key-path API
- 🎭 **W3C Actions API gestures** — tap, scroll, swipe, long press, and pinch using the modern pointer input standard
- 🧪 **15 E2E scenarios** across Login, Inventory, Cart, Checkout, and Navigation in 3 configurable TestNG suites
- 📈 **Allure reporting** with compile-time AspectJ step weaving, failure screenshots, severity classification, and environment panel
- ☁️ **BrowserStack-ready** — only driver capabilities change to switch from local emulator to cloud device farm
- 🛠️ **Stack:** Java 17, Appium 2.0, UiAutomator2, TestNG, Allure, AspectJ, Jackson, Maven, Android API 34

---

## 🏆 Key Achievements

- ⚡ Accelerated regression cycles by **25%** through optimized test suites and shift-left reviews
- 📈 Improved release quality by **15–20%** for IoT mobile experiences at Google Home App
- 🔍 Reduced rework by **20%** by identifying high-risk areas early in SDLC
- 🤖 Designed **GenAI-powered self-healing locators** using Claude API — eliminating locator-drift maintenance for top-priority smoke tests
- 🧪 Built a **production-grade RAG evaluation framework** measuring 3 RAG Triad metrics with LLM-as-judge methodology
- 🧑‍🏫 Mentored **4–6 QA engineers** across automation best practices and script quality
- 📊 Boosted automation coverage by **20–30%** through enhanced framework development

---

## 🎓 Technical Strengths

`Test Automation Strategy` &nbsp;|&nbsp; `Framework Architecture` &nbsp;|&nbsp; `Design Patterns` &nbsp;|&nbsp; `CI/CD Integration` &nbsp;|&nbsp; `Parallel Execution` &nbsp;|&nbsp; `Hybrid API + UI Testing` &nbsp;|&nbsp; `LLM Evaluation` &nbsp;|&nbsp; `Self-Healing Test Frameworks` &nbsp;|&nbsp; `Prompt Engineering` &nbsp;|&nbsp; `Mobile Automation`

---

## 🌐 Domain Expertise

`IoT / Smart Devices` &nbsp;|&nbsp; `Subscription Platforms` &nbsp;|&nbsp; `Cloud IT Admin` &nbsp;|&nbsp; `E-Commerce` &nbsp;|&nbsp; `Insurance` &nbsp;|&nbsp; `Telecom Billing` &nbsp;|&nbsp; `GenAI / LLM Testing`

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/meghanamp)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/meghana-mp)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:meghana.mp.19@gmail.com)
