# <img src="Frontend/public/logo.png" alt="Tokenizer logo" width="28" style="vertical-align: middle;" /> Tokenizer

**See how AI reads text.**

Tokenizer is a free, open-source playground for how language models understand text. Cut a sentence into tokens, fly through thousands of words in 3D, do arithmetic with meaning, and learn how it all fits together, right in your browser. No sign-up, no ads.

➡️ **Repository:** [github.com/orewachetas/Tokenizer](https://github.com/orewachetas/Tokenizer)

---

## 🧭 Features

| Feature | Description |
|---|---|
| **🔤 Tokenizer** | See exactly how a model splits text into tokens and IDs. Compare GPT (o200k, cl100k, p50k, r50k, GPT-2) and LLaMA tokenizers on the same text. |
| **🌌 Embedding Explorer** | Thousands of words from GloVe, Word2Vec and FastText in an interactive 3D map, projected with PCA or UMAP. Search a word, see its neighbours, pin two words to compare. |
| **➕ Vector Playground** | `king − man + woman ≈ queen`. Do arithmetic with word vectors and watch the analogy play out as vectors in 3D space. |
| **📚 Learn** | Beginner-friendly articles on tokens, embeddings and transformers, with interactive diagrams and figures. |

---

## ✨ Highlights

- **Real data:** Token IDs come from the real tokenizers; embeddings are real 300-dimensional GloVe, Word2Vec, and FastText vectors.
- **Honest 3D:** PCA or UMAP for visualization, while similarity and analogies always use all 300 dimensions.
- **Runs in your browser:** Tokenizers run locally (WebAssembly) and your text is never sent to any external server.
- **Fast to load:** Highly compressed datasets, with vector playground data packed to ~2.5 MB per model.
- **Responsive & touch-friendly:** Full touch gestures (orbit, pinch, tap to inspect) on desktop, tablet, and mobile.
- **Multi-language support:** Available in English, 中文, 日本語, and Español.

---

## 🧰 Tech Stack

- **Framework:** Next.js 16 (App Router) & React 19
- **Styling:** Tailwind CSS 4, Radix UI primitives
- **3D Graphics:** Three.js, React Three Fiber
- **Tokenizers:** `@dqbd/tiktoken`, `gpt-tokenizer`, `llama-tokenizer-js`
- **Internationalization:** `next-intl`
- **Data & Compression:** `pako`, `jszip`

---

## 🏃 Run it Locally

```bash
git clone https://github.com/orewachetas/Tokenizer.git
cd Tokenizer/Frontend
npm install
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000).

| Command | What it does |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Production build |
| `npm start` | Start production server |
| `npm run lint` | Run ESLint checks |

---

## 📄 License

MIT. Made with ❤️ by [@orewachetas](https://github.com/orewachetas).
