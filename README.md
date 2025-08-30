const express = require("express");
const app = express();

app.get("/", (req, res) => {
  res.send("Hello Backend from phone!");
});

app.listen(192.168.0.103, () => console.log("Server running on port 192.168.0.103"));