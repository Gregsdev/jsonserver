# jsonserver
JSON Server 

1. Mkdir jsonserver 
2. cd jasonserver
3. npm init
4. ls
5. npm install json-server ngrok
6. ls
7. Open directory code editor 
8. create new db.js file {“blogpost”: []}
9. In package.json delete “test”
10.  "db": "json-server -w db.json”,
11. "tunnel": "ngrok http 3000"
12. Open two terminals jsonserver and in first npm run db
13. If there is an error change port on package.json -p 3001
14. second window npm run tunnel 
15. In React Native project folder npm install axios
