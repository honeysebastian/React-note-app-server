
        ----------------------------------------
                JSON SERVER
        ----------------------------------------
        1. Create a folder to hold json file
        2. Create package.json file inside the folder : npm init -y
        3. Create db.json file inside the folder and resources as key to the json file
        4. To run json file install json-server : npm i json-server / npm i json-server@0.17.4
        5. To run json file in localhost use : npx json-server db.json / node index.js
        -------------------------------------------------
              Deploying A  JSON FILE  using NODE JS
        -------------------------------------------------
        1. Create index.js file server folder
        2. update script in package.json file as "start":"node index.js"
        3. create .gitignore file and add 'node_modules' folder
        4. Define json-server to run json file in index.js
            - import json-server
            - create server run json file using create() method of jsonServer
            - create middleware used by JSON Server.
            - set up route for json file in server
            - use middleware, route in server app
            - listen the app in given port to resolve client request
        5. To run the app, use 'node index.js'

       
