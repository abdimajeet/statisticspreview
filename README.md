# Statistics & Probability for ML Academy — Preview

A self-study web platform that teaches **statistics and probability from absolute beginner level up to the foundations needed for Machine Learning, AI and Data Science**. **Live site: [statistics-self-omega.vercel.app](https://statistics-self-omega.vercel.app/)**

This repository is a visual preview of the app; the source code is kept in a private repository.

## Highlights

- **12 complete modules, 57 lessons** — from "What is statistics?" to MLE/MAP and the bias–variance trade-off.
- **A consistent 12-part lesson format** — objectives, simple explanation, theory, formulas, worked examples, ML applications, interactive visualisation, Python, exercises, knowledge check, summary and resources.
- **42 interactive tools** — simulators and calculators for distributions, the Central Limit Theorem, confidence intervals, hypothesis tests, regression, Bayes' theorem and more.
- **228 exercises, a 162-question assessment bank and 36 Python exercises**, with weak-topic analysis that points back to the lessons to revise.
- **Progress tracking** — study streaks, quiz averages, module completion and a learning record.
- **Google sign-in and cloud sync** — progress is saved to MongoDB Atlas and follows you to any device.
- **Dark and light themes**, fully responsive down to phone screens.

## Tech stack

| Area | Technology |
| --- | --- |
| Frontend | React 18, Vite 6, Tailwind CSS v4, React Router |
| Charts & maths | Recharts, KaTeX, highlight.js |
| Backend | Node.js, Express |
| Database | MongoDB Atlas |
| Auth | Google Identity Services, JSON Web Tokens |
| Hosting | Vercel (website), Render (API) |

## Screenshots

All screenshots are captured at 2× resolution (2880×1800 on desktop, 1170×2532 on mobile) and show a demo learner partway through Module 3.

### Dashboard
Progress overview, study streak, quiz average, the current module on the learning path and the recommended next lesson.

![Dashboard](screenshots/01-dashboard.png)

### Courses
All twelve modules with durations, completion state and sequential unlocking.

![Courses](screenshots/02-courses.png)

### Learning roadmap
Four phases — Foundations, Probability, Inference and Modelling — with why each module matters for machine learning.

![Learning roadmap](screenshots/03-roadmap.png)

### Lesson
Every lesson follows the same twelve-part structure, with an outline to jump between sections.

![Lesson page](screenshots/04-lesson.png)

### Formulas
Formulas rendered with KaTeX, each with its symbols explained.

![Lesson formulas](screenshots/05-lesson-formulas.png)

### Worked examples
Step-by-step examples with real numbers, so every result can be reproduced by hand.

![Worked example](screenshots/06-worked-example.png)

### Central Limit Theorem simulator
5,000 sample means of size 30 drawn from a skewed population line up with the normal curve the CLT predicts.

![Central Limit Theorem simulator](screenshots/07-playground-clt.png)

### Linear regression visualiser
Fit a least-squares line, inspect residuals and see how slope and R² respond to the data.

![Linear regression visualiser](screenshots/08-playground-regression.png)

### Bayes' theorem
A medical-test example showing why a positive result can still mean a low probability of disease.

![Bayes' theorem tool](screenshots/09-playground-bayes.png)

### Quizzes & assessments
A foundations diagnostic, one quiz per module and three difficulty-level assessments.

![Quizzes and assessments](screenshots/10-quizzes.png)

### Python practice
Exercises with starter code, expected output, hints and full solutions using NumPy, pandas and scikit-learn.

![Python practice](screenshots/11-python-practice.png)

### Learning record
Lessons completed per module, study days and accuracy by topic.

![Progress](screenshots/12-progress.png)

### Light theme

![Dashboard, light theme](screenshots/13-dashboard-light.png)

![Courses, light theme](screenshots/14-courses-light.png)

### Google sign-in
Lessons ask learners to sign in with Google so their progress is saved to their account.

![Google sign-in](screenshots/15-sign-in.png)

### Mobile

<p>
  <img src="screenshots/16-mobile-dashboard.png" alt="Mobile dashboard" width="260">

  <img src="screenshots/17-mobile-lesson.png" alt="Mobile lesson" width="260">

  <img src="screenshots/18-mobile-courses.png" alt="Mobile courses" width="260">
</p>

## Try it

Open the live site at **[statistics-self-omega.vercel.app](https://statistics-self-omega.vercel.app/)**. Browsing is open to everyone; sign in with Google to start lessons and save your progress.

## Source

The source code is kept in a private repository.
