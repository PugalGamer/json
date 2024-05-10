npm init
npm i json-server

create file --> db.json
{
  "users": [
    {
      "id": "1",
      "name": "pugal gamer",
      "no":46
    }
  ]
}

changes in--> package.json
 "scripts": {
    "server": "json-server --watch db.json --port 3003"
  },

npm run server
http://localhost:5000/Students
