1/ Install node.js >> https://www.npmjs.com/package/newman#using-reporters-with-newman
2/ Install extrahtml report >> npm install -g newman-reporter-htmlextra
3/ Copy JSON QANTAS.test collection into the folder where Newman was installed
4/ in Command line run the following from the folder where newman was installed:
 newman run QANTAS.test.json --reporters=cli,htmlextra
 updated
