### Hi there 👋
```javascript
const bio = {
  name: "Reza Gholizadeh",
  title: "Frontend Developer",
  yearsOfExperience: 2,
  currentEmployer: "Snappfood"
};
const greet = () => {
  const currentTime = new Date().getHours();
  const greeting = currentTime < 12 ? "Good morning" : currentTime < 18 ? "Good afternoon" : "Good evening";
  return `${greeting}, I'm ${bio.name}, a ${bio.yearsOfExperience}-year ${bio.title} at ${bio.currentEmployer}`;
};
console.log("welcome", greet());
<!--
**Reza-Gholizadeh/Reza-Gholizadeh** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
