Run the Project
On any OS you need Truffle

npm install -g truffle
and then clone this repository

git clone
and run

bower install
which installs the angular components.

and then run

npm install
which installs the node components.

Additionally you need to have a geth node running (or the ethereumjs-testrpc), then you can simply:

truffle migrate
and

truffle build
or

truffle serve
which opens an HTTP Server on http://localhost:8080
