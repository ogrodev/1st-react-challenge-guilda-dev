# 1st React Challenge - Guilda Dev
Welcome everyone! This is our first code challenge and we are very proud to do it.
Below you will find all the instructions needed to build the app, but try to be creative and surprise us, why not.

We are building our website and all projects will be displayed as our members portfolio.

All projects will be reviewed by senior professionals and will have immersive feedback at each point of improvement/optimization culminating in an individual mentorship with each participant. We target junior devs but mid-levels can and will be accepted as well.

This challenge is based on a company test, so you could end up seeing this in an interview 😉

<Good luck & have fun />

## First of all

Read these before starting your challenge:

 - Read all the instructions
 - Projects will be accepted until August 31, 2022. After that, we will not review it.
 - Mentorship are going to be scheduled between the mentor and mentee.
 - Join our discord to send in your project for review: https://discord.gg/hVZ6YZJNH3
 - **You must use: React, Typescript & create-react-app**, all other technologies are up to you.

## Your challenge is to create a 10 question, true or false, trivia app with React Web.  
  
  
The application code will be reviewed and scored on these key areas with many subset areas for each:  
  
- Functionality  
- Code Format  
- Project Structure  
- Scalability  
- Maintainability  
- Use of industry best practices  
  
  

## **Specifications**
  
The api url is:  [https://opentdb.com/api.php?amount=10&difficulty=hard&type=boolean  
](https://opentdb.com/api.php?amount=10&difficulty=hard&type=boolean)  
Sample returned json:  
```json
{
  "response_code": 0,
  "results": [
    {
      "category": "Entertainment: Video Games",
      "type": "boolean",
      "difficulty": "hard",
      "question": "Unturned originally started as a Roblox game.",
      "correct_answer": "True",
      "incorrect_answers": [
        "False"
      ]
    },…]}
```
   
  ---
**Intro / Home Screen:**  

![](https://raw.githubusercontent.com/g2i/code-challenge-static-assets/master/Intro.png)

-   Static Text
-   BEGIN button navigates to the Quiz screen and starts the Quiz

**Quiz Screen:**  

![](https://raw.githubusercontent.com/g2i/code-challenge-static-assets/master/Quiz.png)

-   The headline is from question category
-   The card element contains the current question
-   The next question should appear after the current question is answered True or False
-   After all questions have been answered, navigate to the Results Screen

**Results screen:**  

![](https://raw.githubusercontent.com/g2i/code-challenge-static-assets/master/Score.png)

-   The Score shows correct and total
-   Displays a list of the questions and whether the answer was correct or not
-   PLAY AGAIN starts over and navigates to the Home Screen

## What will be considered as delivered?

-   Completed the challenge requirements stated above.
-   Implemented an organised and easily understandable React code following best practices
-   Included clear instructions and requirements for how to run the app in a Development environment.
-   Follow JavaScript best practices
  

## Some tips about best practices   

-   Code Style Practices  [https://github.com/goldbergyoni/nodebestpractices#3-code-style-practices](https://github.com/goldbergyoni/nodebestpractices#3-code-style-practices)
-   Uses async-await or promises for async error handling  [https://github.com/goldbergyoni/nodebestpractices#-21-use-async-await-or-promises-for-async-error-handling](https://github.com/goldbergyoni/nodebestpractices#-21-use-async-await-or-promises-for-async-error-handling)
-   Use only built-in error object  [https://github.com/goldbergyoni/nodebestpractices#-22-use-only-the-built-in-error-object](https://github.com/goldbergyoni/nodebestpractices#-22-use-only-the-built-in-error-object)
-   Always awaits promises  [https://github.com/goldbergyoni/nodebestpractices#-212-always-await-promises-before-returning-to-avoid-a-partial-stacktrace](https://github.com/goldbergyoni/nodebestpractices#-212-always-await-promises-before-returning-to-avoid-a-partial-stacktrace)
-   Handling of API Errors
-   Follow clear naming convention -  [https://github.com/kettanaito/naming-cheatsheet](https://github.com/kettanaito/naming-cheatsheet)
-   Handle navigation and routing properly
-   Follow the principles of thinking in React  [https://reactjs.org/docs/thinking-in-react.html](https://reactjs.org/docs/thinking-in-react.html)
-   JavaScript best practices -  [https://exploringjs.com/deep-js/toc.html](https://exploringjs.com/deep-js/toc.html)  and  [https://exploringjs.com/impatient-js/toc.html](https://exploringjs.com/impatient-js/toc.html)
-   Separation of concerns between UI, Server Data, Business Logic -  [https://khalilstemmler.com/articles/client-side-architecture/introduction/](https://khalilstemmler.com/articles/client-side-architecture/introduction/)
-   Declarative style of programming - for inspiration  [https://betterprogramming.pub/write-delightful-declarative-javascript-a83c91111e12](https://betterprogramming.pub/write-delightful-declarative-javascript-a83c91111e12).',
-   UI Responsiveness & User Experience.
