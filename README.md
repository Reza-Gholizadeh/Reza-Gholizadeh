### Hi there 👋
```javascript
const bio = {
  name: "Reza Gholizadeh",
  title: "Frontend Developer",
  yearsOfExperience: 3,
  currentEmployer: "Snappfood"
};
const greet = () => {
  const currentTime = new Date().getHours();
  const greeting = currentTime < 12 ? "Good morning" : currentTime < 18 ? "Good afternoon" : "Good evening";
  return `${greeting}, I'm ${bio.name}, a ${bio.yearsOfExperience}-year ${bio.title} at ${bio.currentEmployer}`;
};
console.log("welcome", greet());
