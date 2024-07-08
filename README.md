# new3-demo
This is demo for Git &amp; GitHub Class for new3-demo repository.

#Git & GitHub

A Git repository is a version-controlled project folder that tracks changes to files over time.
It enables collaboration and efficient project management by storing the history of modifications.


const express = require('express');
const app = express();
const port = 3000;



const express = require('express');
const app = express();
const port = 3000;

app.use(express.json());


app.get('/users', (req, res) => {
  res.json(users);
});
app.get('/users/:id', (req, res) => {
  const user = users.find(u => u.id === parseInt(req.params.id));
  if (!user) return res.status(404).send('User not found');
  res.json(user);
});


The terms "Internet" and "network" are often used interchangeably, but they refer to ,
different concepts in the realm of computing and telecommunications. Here are the key differences:
