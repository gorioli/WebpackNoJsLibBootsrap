Available commands:
#0:
    npm install
#1:
    npm run build

#2:
    npm run dev
Go to - http://127.0.0.1:8080/webpack-dev-server/   

#3:
    npm run sass
    
#~ ~ ~
Run webpack:
		node node_modules/webpack/bin/webpack.js --progress --colors --watch

Run webpack w/t config file:
		node node_modules/webpack/bin/webpack.js ./js/entry.js ./build/bundle.js

#~ ~ ~ 
Run dev-server:
		node node_modules/webpack-dev-server/bin/webpack-dev-server.js --progress --colors

Site is available from:
		http://localhost:8080/webpack-dev-server/bundle