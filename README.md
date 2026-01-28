const express = require('express');
const app = express();
const port = process.env.PORT || 3000;

app.get('/', (req, res) => {
  res.send('<h1>नमस्ते! मेरी Node.js वेबसाइट लाइव हो गई है।</h1><p>मैं वेबसाइट बनाना और AdSense अप्रूवल दिलाना सिखाता हूँ।</p>');
});

app.listen(port, () => {
  console.log(`Server is running on port ${port}`);
});
