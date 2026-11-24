# Hi, I'm Sania 

I'm a Computer Science undergrad (B.Tech CSE–AI) interested in **AI, backend development,
and software engineering**. Most of what I build lives on this profile as small,
self-contained, heavily commented experiments — I'd rather write a from-scratch perceptron
once than call an API fifty times.

### 🚀 Currently Building

* 🤖 RAG-based AI applications
* ⚙️ Microservices and backend systems
* 🐳 Containerized applications with Docker
* 💻 Strengthening my Data Structures & Algorithms fundamentals

### 🛠️ Tech Stack

**Languages:** Python · C++ · Java · TypeScript · JavaScript

**AI / Data:** PyTorch · TensorFlow · scikit-learn · Hugging Face Transformers · NLTK · spaCy · pandas · NumPy

**Frontend:** React · TypeScript · Vite · HTML · CSS · Tailwind CSS

**Backend & Tools:** Git · GitHub · Docker · Linux · WSL · Jupyter

---

## 📂 What's in my repos

### 🧠 AI & Machine Learning

| Repo | What it is |
| --- | --- |
| [**Exploring-NLP**](https://github.com/sania0507/Exploring-NLP) | The full classical-to-modern NLP pipeline: tokenization, stemming, lemmatization, BoW/TF-IDF, Word2Vec & GloVe, BERT sentence embeddings, HMM part-of-speech tagging, and Whisper speech-to-text with Hindi→English translation |
| [**Exploring-Deep-Learning**](https://github.com/sania0507/Exploring-Deep-Learning) | One Colab notebook spanning PCA, linear/logistic regression, SVM, learning curves, CNNs, RNNs, and Keras NLP — plus single-layer ANN, multilayer ANN, ADALINE, RBF, and backpropagation written from scratch in NumPy |
| [**ML_Mini_algo_projects**](https://github.com/sania0507/ML_Mini_algo_projects) | 24 numbered experiments from first-look-at-a-dataset to transformers: perceptron, k-NN, k-Means, and gradient descent implemented from scratch, plus regularization, cross-validation, ensembles, transfer learning, and a bias-detection demo |
| [**Exploring-Data-Analysis**](https://github.com/sania0507/Exploring-Data-Analysis) | DVA lab in a single Colab notebook — EDA on car prices, California housing, and hotel bookings, time series analysis with rolling windows, decomposition with SMA/EMA, linear regression, and k-NN |

### 💻 Software Engineering

| Repo | What it is |
| --- | --- |
| [**StudyStack**](https://github.com/sania0507/StudyStack) | A TypeScript web application for organising study material |
| [**MiniAITutorDemo**](https://github.com/sania0507/MiniAITutorDemo) | A Python GUI tutor for K-12 science and maths — answers drawn from a curated in-app knowledge base, so it runs completely offline with no API key |
| [**E-commerce-Product-Page**](https://github.com/sania0507/E-commerce-Product-Page) | A responsive product page built with HTML and CSS |


### 🤝 Open Source

Contributor to **GirlScript Summer of Code 2026**.

**[AlgoMate](https://github.com/PankajSingh18/AlgoMate)** — merged
[PR #186](https://github.com/PankajSingh18/AlgoMate/pull/186) *(May 2026)*, fixing race
conditions and a broken OAuth login flow in a Next.js + Supabase app:

- **Supabase OAuth callback** — added `app/auth/callback/route.js` to perform the PKCE
  authorization-code exchange server-side with `@supabase/ssr`, writing session tokens as
  `httpOnly` cookies so they're never exposed to client JavaScript.
- **Post-login hydration race** — removed a brittle `getUser()` check that fired
  immediately after sign-in and intermittently redirected to a broken dashboard. The route
  now trusts the API's `success: true` and lets `UserContext` handle hydration where it
  has the full state to do so correctly.
- **Broken asset path** — fixed the Google icon reference in `app/login/page.jsx` to an
  absolute root path so it resolves from nested routes.

Wrote it up as a self-contained fix rather than a feature PR — two files, +44/−14.

**[AlgoBuddy-Sania](https://github.com/sania0507/AlgoBuddy-Sania)** — my fork from the same
program, kept as a reference copy.

---

### 🏆 Achievements

* GirlScript Summer of Code 2026 — Open Source Contributor (merged PR into AlgoMate)
* CGPA: 9.3/10


## 🐍 My Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sania0507/sania0507/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sania0507/sania0507/output/github-snake.svg">
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/sania0507/sania0507/output/github-snake.svg">
</picture>

*Always learning, building, and experimenting.*
