# youtube-typescript-nodejs
Código do projeto produzido durante o vídeo sobre TypeScript no NodeJS

* Node + Typescript (https://www.youtube.com/watch?v=aTf8QTjw4RE)

 
 -- Criar package.json
 yarn init -y

-- Adicionando dependências
yarn add -D typescript sucrase nodemon


sucrase > Gera o bundle js (transpila o código typescript para js)


sucrase não é recomendado para fazer a geração do build em produção.


yarn add -D eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin

yarn eslint --init

yarn add prettier eslint-config-prettier eslint-plugin-prettier -D

yarn add express cors mongoose

yarn add @types/express @types/cors @types/mongoose -D
