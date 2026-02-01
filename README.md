# miraya-vite-react-starter

This is my **personal React starter**.

I clone this repo **every time** I build:

* UI demos
* micro-interactions
* motion experiments
* small showcase projects I post on social media

No setup drama. No boilerplate bloat.
Just clone → install → build.

---

### 📦 Stack

* **React** (Vite)
* **TypeScript**
* **Tailwind CSS**
* **Framer Motion**
* **clsx + tailwind-merge**
* **lucide-react**

Opinionated, modern, and fast to work with.

---

### ☁️ Why this repo exists

I got tired of:

* setting up Tailwind again
* re-installing Framer Motion
* rewriting the same `cn()` utility
* wasting energy before I even started building

So this repo is my default starting point.

If you see a UI demo or animation from me online,
**it probably started here.**

---

### ⚙️ Quick start

```bash
git clone https://github.com/mirayatech/miraya-vite-react-starter.git
cd miraya-vite-react-starter
npm install
npm run dev
```

That’s it.

---

### ✨ Utility: `cn()`

Located in `src/utils.ts`

```ts
import { clsx, type ClassValue } from "clsx";
import { twMerge } from "tailwind-merge";

export function cn(...inputs: ClassValue[]) {
  return twMerge(clsx(inputs));
}
```

Used everywhere for clean Tailwind class composition.

---
### 📄 How I use this repo

My usual flow:

1. Clone this repo
2. Build one focused component or interaction
3. Polish visuals + motion
4. Share on social media
5. Move on

(no long term maintenance & no premature abstractions)

---

### 💭 Philosophy

* Build small
* Make it look great
* Ship fast
* Repeat

---

### 🙂 Author

**Miraya Tech**
[https://github.com/mirayatech](https://github.com/mirayatech)
