# TMDB Movie Search

Educational project for movie search through **TMDB API** integration, **Axios**
requests, asynchronous state management using **TanStack Query (React Query)**,
and pagination implementation with **React Paginate**.

---

## 🚀 Demo & Links

- **Live Demo (Vercel):**
  [Live page](https://04-react-query-beryl-two.vercel.app/)
- **Repository:** [GitHub](https://github.com/SerdiukSerhii/04-react-query)

---

## 🛠️ Tech Stack

- **Bundler:** Vite (React + TypeScript)
- **Asynchronous State Management:** TanStack Query (`@tanstack/react-query`)
- **HTTP Client:** Axios
- **Pagination:** React Paginate
- **Styling:** CSS Modules + `modern-normalize`
- **Linter / Formatter:** Prettier & ESLint

---

## 📌 Features

1. **Movie Search:** Sending requests to the TMDB service based on the entered
   search keyword.

2. **Pagination:** Navigating through result pages using the `ReactPaginate`
   component.

3. **State Management:**
   - `QueryClientProvider` setup at the top level in `src/main.tsx`.
   - Using the `useQuery` hook for caching, automatic refetching, and handling
     `isLoading` / `isError` states.

4. **Unified Typing:** Strict use of TypeScript (`interface`, common types in
   `src/types/`, and internal props for components).

---

## 📁 Project Structure

Each React component is located in a separate folder inside `src/components/`
containing the component file (`.tsx`) and its corresponding CSS module file
(`.module.css`).

```text
src/
├── api/
├── components/
│   ├── App/
│   │   ├── App.tsx
│   │   └── App.module.css
│   └── ... (інші компоненти)
├── types/
│   └── movie.ts
├── main.tsx
└── index.css
```

---

## ⚙️ Локальний запуск та встановлення

1. Clone the repository and navigate to the project folder:

git clone https://github.com/SerdiukSerhii/04-react-query

cd 04-react-query

2. Install dependencies:

npm install

3. Create a .env file in the root directory and add your TMDB API key:

VITE_TMDB_API_KEY=your_access_token_here

4. Start development mode:

npm run dev

5. Production build:

npm run build

---

## Автор

**Serhii Serdiuk**
