# FSD-MERN

This is my personal learning repo where I've been documenting everything I studied while learning full-stack web development. Started from basic HTML and slowly worked my way up to building a proper MERN stack app. Each folder represents a different phase of my learning journey.

Still a work in progress — the backend and final project are being actively worked on.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express_5-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

---

## What's in here

```
FSD-MERN/
├── HTML-CSS-JS/       → All the frontend basics (HTML, CSS, Bootstrap, JS, DOM)
├── MongoDB/           → MongoDB queries and assignments I practiced
├── Express/           → Backend server I'm building with Express + Mongoose
├── React/             → React app with 20 components, each covering one topic
└── README.md
```

---

## HTML-CSS-JS

This is where I started. Has separate folders for each technology I learned.

**HTML** — covered things like forms, tables, hyperlinks, multimedia, anchor tags etc. Around 12 demo files.

**CSS** — 28 demo files. Started from basics like selectors and box model, then moved to flexbox, positioning, media queries, pseudo elements, animations. Also made a responsive navbar and a full page layout.

**Bootstrap** — went through the grid system, cards, modals, progress bars, navbars etc. About 16 demos total.

**JS (Core JavaScript)** — 23 files covering variables, loops, functions, closures, arrow functions, IIFE, array methods like map/filter/reduce, string methods, destructuring, spread/rest operators.

**DOM-JS** — 15 files. Practiced DOM selection methods (`getElementById`, `querySelector` etc.), creating elements dynamically, class toggling, event handling, form stuff and finally the Fetch API.

---

## MongoDB

Practiced MongoDB queries here — both basic CRUD and more advanced stuff.

| File | What I practiced |
|---|---|
| `1 MongoDbQueries.js` | Basic insert, find, update, delete |
| `2 collegeDB.studentDB.json` | Sample data I used for practice |
| `4 MongoDBQueries2.js` | Filters with `$gt`, `$lt`, `$in`, `$and`, `$or` |
| `5 Employees data .js` | Another dataset — employee records |
| `6 Assignment2.js` | Query assignment |
| `7 Aggregation.js` | Aggregation pipeline — `$match`, `$group`, `$project`, `$lookup` etc |
| `8 Assignment3.js` | Aggregation assignment |
| `9 ArrayOperations.js` | Array operators — `$push`, `$pull`, `$addToSet`, `$elemMatch` |

---

## Express (Backend)

Built a basic REST API using Express 5 and Node.js. Set up MVC-style folder structure with separate routes, controllers and utility files. Connected to MongoDB using Mongoose.

```
Express/
├── index.js                     → server entry point
├── routes/
│   ├── adminRoutes.js
│   └── userRoutes.js
├── controllers/
│   ├── adminController.js
│   └── userController.js
├── utils/
│   └── responseHelper.js
└── package.json
```

Dependencies used: `express ^5.2.1`, `mongoose ^9.9.3`, `bcrypt ^6.0.0`, `dotenv ^17.4.2`

To run:
```bash
cd Express
npm install
node index.js
```

---

## React

Made a React 19 app using Vite. Has 20 components, each one focusing on a single concept so it's easy to refer back to specific things.

| Component | What it covers |
|---|---|
| myComp01 | Basic functional component |
| myComp02 | Props and text |
| myComp03 | JSX and lists |
| myComp04 | Inline styles and className |
| myComp05 | Event handling |
| myComp06 | Conditional rendering — if/else style |
| myComp07 | Conditional rendering — ternary |
| myComp08 | Rendering arrays with map() |
| myComp09 | Dynamic table from array |
| myComp10 | Parent to child components |
| myComp11 | Cards |
| myComp12 | React Router — Routes and nested routes |
| myComp13 | useParams for dynamic routes |
| myComp14 | Link navigation |
| myComp15 | useState |
| myComp16 | Event listeners + async data |
| myComp17 | Form handling |
| myComp18 | useEffect |
| myComp19 | Props drilling |
| myComp20 | Context API |

Also created a separate `Context/AppContexts.jsx` as a clean reusable global context setup.

To run:
```bash
cd React/myFirstApp
npm install
npm run dev
```

Opens at `http://localhost:5173`

---

## What I've covered so far

- [x] HTML
- [x] CSS + responsive design
- [x] Bootstrap
- [x] JavaScript (ES6+)
- [x] DOM manipulation + Fetch API
- [x] MongoDB queries and aggregation
- [x] Express.js REST API
- [x] React 19 with hooks + routing + context
- [x] Mongoose for DB connection
- [ ] Final MERN project (in progress)

---

## Author

**Anmol Dwivedi**
GitHub: [@anmoldwivedi89](https://github.com/anmoldwivedi89)
Email: anmoldwivedi2002@outlook.com
