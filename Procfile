web: http-server ./client -p $PORT
watchify: watchify -t coffeeify -t node-lessify -t reactify -v --extension=".coffee" --extension=".litcoffee" client/js/main.litcoffee -o client/app.js
