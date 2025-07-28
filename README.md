

<img width="868" height="487" alt="{FAF978DD-2B73-4E87-B226-BEF872EDDF31}" src="https://github.com/user-attachments/assets/36ef6224-3e61-47aa-8b1e-bf0504aa5f6a" />


# React Tailwindcss Boilerplate build with Vite

This is a boilerplate build with Vite, React 18, TypeScript, Vitest, Testing Library, TailwindCSS 3, Eslint and Prettier.

## What is inside?

This project uses many tools like:

- [Vite](https://vitejs.dev)
- [ReactJS](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org)
- [Vitest](https://vitest.dev)
- [Testing Library](https://testing-library.com)
- [Tailwindcss](https://tailwindcss.com)
- [Eslint](https://eslint.org)
- [Prettier](https://prettier.io)


## Getting Started


### 1. Create a New Project

Clone the boilerplate using Git:

```bash
git clone https://github.com/makozi/react-vite-tailwindcss-boilerplate my-app
cd my-app
```

### 2. Install Dependencies


Install all required packages:

Using npm:
```bash
npm install
```
Or using yarn:
```bash
yarn install
```

### 3. Start the Development Server

Run the app locally with hot reload:


Using npm:
```bash
npm run dev
```
Or using yarn:
```bash
yarn dev
```
Visit [http://localhost:5173](http://localhost:5173) in your browser.

### 4. Project Structure

```
├── index.html                # Main HTML entry point
├── package.json              # Project metadata and scripts
├── postcss.config.mjs        # PostCSS config for Tailwind
├── tailwind.config.mjs       # TailwindCSS config
├── tsconfig.json             # TypeScript config
├── vite.config.ts            # Vite config
├── public/                   # Static assets
│   ├── favicon.svg
│   └── robots.txt
├── src/                      # Source code
│   ├── index.tsx             # App entry point
│   ├── assets/               # Images, icons, etc.
│   ├── components/           # React components
│   │   ├── App.tsx           # Main App component
│   │   ├── test.tsx          # Example/test component
│   │   └── Avatar/           # Example nested component
│   │       ├── index.tsx
│   │       ├── test.tsx
│   │       └── __snapshots__/
│   │           └── test.tsx.snap
│   └── utils/                # Utility functions
│       └── index.ts
```

### 5. Scripts & Commands


- **Start Dev Server:**
  - Using npm:
    ```bash
    npm run dev
    ```
  - Using yarn:
    ```bash
    yarn dev
    ```
- **Build for Production:**
  - Using npm:
    ```bash
    npm run build
    ```
  - Using yarn:
    ```bash
    yarn build
    ```
- **Lint Code:**
  - Using npm:
    ```bash
    npm run lint
    ```
  - Using yarn:
    ```bash
    yarn lint
    ```
- **Typecheck:**
  - Using npm:
    ```bash
    npm run typecheck
    ```
  - Using yarn:
    ```bash
    yarn typecheck
    ```
- **Run Tests:**
  - Using npm:
    ```bash
    npm run test
    ```
  - Using yarn:
    ```bash
    yarn test
    ```
- **Test UI:**
  - Using npm:
    ```bash
    npm run test:ui
    ```
  - Using yarn:
    ```bash
    yarn test:ui
    ```

### 6. Customization

- **Add Components:** Place new React components in `src/components/`.
- **Update Styles:** Edit `tailwind.config.mjs` and use Tailwind utility classes in your JSX.
- **Static Assets:** Add images and icons to `src/assets/` or `public/`.
- **Configuration:**
  - Change Vite settings in `vite.config.ts`.
  - Update TypeScript options in `tsconfig.json`.
  - Modify ESLint rules in `.eslintrc` (if present).

### 7. Testing

- **Unit & Component Tests:**
  - Write tests in `src/components/__tests__/` or alongside components.
  - Run tests with `pnpm run test`.
  - Use `pnpm run test:ui` for an interactive test runner.

### 8. Troubleshooting

- If you encounter issues:
  - Ensure you have [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) installed.
  - Delete `node_modules` and run `npm install` or `yarn install` again.
  - Check your Node.js version (recommended: >=16).
  - Review config files for typos or misconfigurations.

### 9. Deployment


- Build the app for production:
  - Using npm:
    ```bash
    npm run build
    ```
  - Using yarn:
    ```bash
    yarn build
    ```
- Deploy the contents of the `dist/` folder to your preferred static hosting (e.g., Vercel, Netlify, GitHub Pages).

### 10. License

This project is licensed under the MIT License.
