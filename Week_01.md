## Guidance

Answer the following questions considering the learning outcomes for

- [Week 01](https://learn.foundersandcoders.com/course/syllabus/developer/week01-project01-basics/learning-outcomes/)
  
Make sure to record evidence of your processes. You can use code snippets, screenshots or any other material to support your answers.

Do not fill in the feedback section. The Founders and Coders team will update this with feedback on your progress.

Assessment
1. Show evidence of some of the learning outcomes you have achieved this week.
- I think the biggest win for me this week was figuring out how to use CSS Flexbox and Grid, and successfully applying them to our project, along with media queries.
```
/* If the screen size is 600px wide or less, hide the element */
@media screen and (max-width: 600px) {
    div.address-footer {
      display: none;
    }
  }
```

- I also gained a lot of insights into how a project can be structured. It was my first time presenting a project in front of everyone, which was a new experience.

- I learned some different CSS techniques from other groups and saw new ways to split tasks within a project. For example, to use CSS modules which help to scope CSS to individual components:
```
import styles from './Button.module.css';
const Button = () => (
  <button className={styles.button}>Click Me</button>
);
```

2. Show an example of some of the learning outcomes you have struggled with and/or would like to re-visit.
- I struggled with JS concurrency—it wasn’t as straightforward as working with regular JS arrays. The way the sequences were explained in Friday’s workshop was pretty tough for me to grasp, even with my prior knowledge in that area. It feels like I forgot everything. 

Feedback (For CF's)
[Course Facilitator name]
[What went well]
[Even better if]
