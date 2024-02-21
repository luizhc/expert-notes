# Expert Notes

## 🚧 Sobre

- É uma aplicação que pemite gravar notas através de áudio ou texto, totalmente responsiva e acessível
- Essa aplicação é construida com [Vite](https://vitejs.dev/)
- Faz uso do framework [React](https://react.dev/) para o front-end
- E utiliza a biblioteca [Tailwind](https://tailwindcss.com/) para criação e estilização do layout
- Contemple e usufrua dessa belezura em https://expert-notess.vercel.app

## 🛠️ Construção

### 🚀 [Vite](https://vitejs.dev/)

- Automatiza e acelera o processo de criação de estrutura de projetos front-end (como route module replacement, typescript, jsx, importação de css, etc).
- Siga: https://vitejs.dev/guide/#scaffolding-your-first-vite-project
- Criação do projeto: `npm create vite@latest`

### 🎨 [Tailwind](https://tailwindcss.com/)

- Utilite classes para HTML;
- Thin First API;
- Padronização CSS;
- Instalação (baseada no vite): https://tailwindcss.com/docs/guides/vite

### 📚 [Radix](https://www.radix-ui.com/)

- Biblioteca de componentes comuns no uso web
- Fornece apenas o funcionamento de componentes (sem estilo)
- Utilizado o [dialog](https://www.radix-ui.com/primitives/docs/components/dialog) nos modais dessa aplicação
  - Instalação: `npm install @radix-ui/react-dialog`

### 🍞 [Sonner](https://sonner.emilkowal.ski/)

- Biblioteca para componente toast
- Instalação: `npm i sonner`

### 🎤 [Speech Recognition](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API#speech_recognition)

- Biblioteca nativa do navegador para converter áudio em texto
  - Verifique quais navegeadores oferecem suporte: https://caniuse.com/?search=speechrecognition
- Instalação para reconhecimento da tipagem em `window`: `npm i -D @types/dom-speech-recognition`

### 🔥 Outros

- [date-fns](https://date-fns.org/) para formatação de datas : `npm i date-fns`
- [lucide](https://lucide.dev/) para obter componentes prontos (utilizado component "X"): `npm i lucide`
- [Material complementar](https://efficient-sloth-d85.notion.site/ReactJS-3a14f6311fbd481eae78462c5a06e9db)

---

## 🐞 Melhorias / Bugs

- Encontrou melhorias e/ou bugs?
  - Abra uma bela [Issue](https://github.com/luizhc/expert-notes/issues)
  - Ou contribua com um lindo [Pull Request](https://github.com/luizhc/expert-notes/pulls)

---

## 🔌 Desenvolvimento

- Instale as dependências: `npm i`
- Execute o projeto: `npm run dev`
- Acesse em: http://localhost:5173
