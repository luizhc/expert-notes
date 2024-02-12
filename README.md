# Expert Notes

## 🚧 Sobre

- É uma aplicação que pemite gravar notas através de áudio, totalmente responsiva e acessível
- Essa aplicação é construida com [Vite](https://vitejs.dev/)
- Fazendo uso do framework [React](https://react.dev/) para o front-end
- Usando biblioteca [Tailwindcss](https://tailwindcss.com/) para criação e estilização de layouts

## 🛠️ [Vite](https://vitejs.dev/)

- Automatiza e acelera o processo de criação de estrutura de projetos front-end (como route module replacement, typescript, jsx, importação de css, etc).
- Siga: https://vitejs.dev/guide/#scaffolding-your-first-vite-project
- Criação do projeto: `npm create vite@latest`

## 🎨 [Tailwind](https://tailwindcss.com/)

- Utilite classes pra html;
- Thin First API;
- Padronização css;
- Instalação (com base no vite): https://tailwindcss.com/docs/guides/vite

## 📚 [Radix](https://www.radix-ui.com/)

- Biblioteca de componentes comuns no uso web
- Trás apenas funcionamento dos componentes (sem estilo)
- Usado o [dialog](https://www.radix-ui.com/primitives/docs/components/dialog) nos modais dessa aplicação
  - Instalação: `npm install @radix-ui/react-dialog`
  - Trablhar com datas: `npm i date-fns`
  - Trabalhar com fontes: `npm i lucide-react`

## 🍞 [Sonner](https://sonner.emilkowal.ski/)

- Biblioteca para componente toast
- Instalação: `npm i sonner`

## 🎤 [Speech Recognition](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API#speech_recognition)

- Biblioteca nativa do navegador para converter áudio em texto
  - Verifique quais navegeadores oferecem suporte: https://caniuse.com/?search=speechrecognition
- Instalação para reconhecimento da tipagem em `window`: `npm i -D @types/dom-speech-recognition`
