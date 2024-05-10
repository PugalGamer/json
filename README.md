npm init
npm i json-server

create file --> db.json
{
  "Students": [
    {
      "name": "Pugal",
      "rollno":46
    }
  ]
}

changes in--> package.json
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "server": "json-server --watch db.json --port 5000"
  },

npm run server
http://localhost:5000/Students
