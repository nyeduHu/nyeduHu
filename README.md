### Hi there 👋

<!--
**nyeduHu/nyeduHu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
```js
const client = require('nyedu.js');
const nyedu = new client.Nyedu();

nyedu.on('wake-up', () => {
  nyedu.Eat();
  nyedu.DoSomeCoding();
  nyedu.Drink();
  nyedu.Sleep();
});

nyedu.on('ask-about-these-stuff', () => {
  let available = [
    '🔭 I’m currently working on ------!',
    '🌱 I’m currently learning 'bout life',
    '💬 Ask me about anything?',
    '📫 How to reach me: by email. nyeso.edu@gmail.com',
    '😄 Pronouns: He/him',
    '⚡ Fun fact: I love woman'
  ];
  
  if(available.includes(your.question.toLowerCase())) return nyedu.AnswerYourQuestion();
  
});

nyedu.login("real-life");
```

