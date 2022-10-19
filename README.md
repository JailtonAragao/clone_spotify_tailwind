Estudo em TAILWIND CSS

Uso de classes para stylizar o projeto front

INICIANDO O NPM

1-npm init -y 
// para iniciar o node

2-npm install tailwindcss@latest postcss@latest autoprefixer@latest
// para instalar o tailwind na pasta

3--criar a arquivo pasta src/index.html / pasta src/css
// depois na pasta raiz criar outro arquivo styles.css e jogar essas linhas de codigos abaixo. 
@tailwind base;
@tailwind components;
@tailwind utilities;

4-npx tailwindcss init 
// para instalar o tailwind e criar o arquivo tailwind.config.js


5-npx tailwindcss-cli@latest build styles.css -o src/css/styles.css

// Criar uma build do arquivo css com -o output para a pasta css dentro de src