<h1 align='center'>console.log(" Hello devs <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" alt="👋" width="35" height="35">, Rajesh here ")</h1>
<h4 align="center">DEVELOPER. GYM FREAK. CINEPHILE.</h4>


### About Me
```javascript

const Express = require('express');

const app = Express();

app.get("/about", (req , res) => {
  res.status(404).json({
    fullName: "rajesh ande",
    interests: [
      "coding 💻",
      "movie 🎬",
      "gym 🏋🏽",
      "coffee ☕",
    ],
    askMeAbout: ["web dev", "mern", "movies"],
    technologies: {
      programming: [
        "python",
        "javascript",
      ],
      frontEnd: ["html", "tailwindcss", "javascript", "reactjs", "nextjs"],
      backEnd: ["nodejs", "expressjs"],
      database: ["mongodb"],
      other: [
        "adobe lightroom" 
      ],
    },
  });
});

app.get("/contact", (req: Request, res: Response) => {
  res.status(200).json({
    email: "anderajesh15@gmail.com",
    links: {
      linkedin: "https://www.linkedin.com/in/rajesh-ande-2175ab197/",
     
    },
  });
});

export default app;

```


