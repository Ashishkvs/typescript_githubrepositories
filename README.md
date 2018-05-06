Step 1
===============
-> npm install request lodash --save

# it will add request api to call rest services into our project
# node_modules folder will be created

# this will be added in our dependecy 
  "dependencies": {
    "lodash": "^4.17.10",
    "request": "^2.85.0"
  }
# in order to autocomplete and see library built in function we add this libaray only for development
-> npm install @types/lodash @types/request --save -dev