# js_calls_c-
How to use c++ programs inside javascript with node.js


Totally based on this guide : https://medium.com/jspoint/a-simple-guide-to-load-c-c-code-into-node-js-javascript-applications-3fcccf54fd32


# How to 

Enter following commands in root directory

npm init -y

npm install -S node-addon-api

node-gyp configure

node-gyp build

# Launch

type 

node index.js

