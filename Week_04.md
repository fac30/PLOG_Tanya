## Guidance
Answer the following questions considering the learning outcomes for
- [Week 04](https://learn.foundersandcoders.com/course/syllabus/developer/week04-project03-frontend/learning-outcomes/)

Make sure to record evidence of your processes. You can use code snippets, screenshots or any other material to support your answers.

Do not fill in the feedback section. The Founders and Coders team will update this with feedback on your progress.

## Assessment
 ### 1. Show evidence of some of the learning outcomes you have achieved this week.
- I refreshed my knowledge of working with **React components** and created several reusable components, such as neader and footer.
```
import Header from './sections/Header';
import Footer from './sections/Footer';
```

- I **worked with Tailwind** for the first time and found it very convenient. It looks easier for me than CSS because you can immediately see how a component is styled:
```
<div className='bg-[#94CD31] flex justify-center items-center w-full h-full'>
```
- In addition, I installed **IntelliSense** and realized how much it simplifies working with Tailwind styles.

- I **learned about the onNext** function(a custom handler). This function helped the project transition from one stage to another while the backend connection is still being set up.
```
useEffect(() => {
		setTimeout(() => {
		setLoading(false);
    onNext(); //go to the next page
		}, 5000);
	}, []);
```
- I researched animations and ended up using an animation from the **Lotties library**. It was the simplest, most adaptable, and suited the content:
```
import { DotLottieReact } from '@lottiefiles/dotlottie-react';

<DotLottieReact
          src="/src/assets/anime_man.json"
          loop
          autoplay
        />
```

 ### 2. Show an example of some of the learning outcomes you have struggled with and/or would like to re-visit.
- I still **haven't managed to style the entire app**. I couldn't figure out how to combine component styles with the main page style - what should be common for all components and what should be individual. 

- I would like to make the loading page animation more complex and add **more interactivity for the user**.


## Feedback (For CF's)
> [**Course Facilitator name**]  
> [*What went well*]  
> [*Even better if*]
