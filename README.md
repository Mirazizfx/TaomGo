const express = require("express");
const cors = require("cors");

const app = express();
app.use(cors());
app.use(express.json());

const menu = [
  { id: 1, name: "Burger", price: 30000 },
  { id: 2, name: "Pizza", price: 45000 },
  { id: 3, name: "Lavash", price: 28000 },
];

app.get("/menu", (req, res) => {
  res.json(menu);
});

app.post("/order", (req, res) => {
  const order = req.body;
  console.log("Yangi buyurtma:", order);
  res.json({ success: true, message: "Buyurtma qabul qilindi!" });
});

app.listen(5000, () => {
  console.log("Server 5000-portda ishlayapti...");
});