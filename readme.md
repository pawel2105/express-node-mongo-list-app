Setup
=====
Clone this repository and then run `npm install` or `yarn install`.

Ensure `mongod` is running and then run the following command to import some user listing data into a database called `test`:

    mongoimport --db test --collection users --drop --file user_list.json

Running the app
===============
Once everything is ready, run `npm run dev` and navigate to `localhost:3000` in your browser.