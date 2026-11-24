Перед вами собранное Vue 2 приложение (production-билд) интернет-магазина «Технозавррр».
1. Билд — это статика. Нужен любой HTTP-сервер.
2. Запустите сервер
Через Python (если установлен):
bash
cd project-root
python3 -m http.server 8080
# открыть http://localhost:8080/vue-app/
Через Node.js (http-server):
bash
npx http-server project-root -p 8080
# http://localhost:8080/vue-app/
Через VS Code: 
расширение Live Server → правый клик на index.html → Open with Live Server
