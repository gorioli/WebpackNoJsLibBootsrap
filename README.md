Available commands:
#Init and download:
    npm install
#Start realtime building:
    npm run build
#Run with ruby server (requires preinstalled serve):
(Serve is a rapid prototyping framework for Web applications - http://get-serve.com/)
    serve
Go to - http://localhost:4000/
#Run with webpack server:
    npm run dev
Go to - http://127.0.0.1:8080/webpack-dev-server/   
#Compile scss files to css:
    npm run sass

#Other info:
Run webpack:
    node node_modules/webpack/bin/webpack.js --progress --colors --watch

Run webpack w/t config file:
    node node_modules/webpack/bin/webpack.js ./js/entry.js ./build/bundle.js

Run dev-server:
    node node_modules/webpack-dev-server/bin/webpack-dev-server.js --progress --colors

Site is available from:
http://localhost:8080/webpack-dev-server/bundle