## Table of Contents

## Sketchnotes
- [Sketchnotes](#sketchnotes)
 - [Titus Wormer](#Titus-Wormer-x-Git-&-GitHub)
 - [Peter Paul Koch](#Peter-Paul-Koch-x-Wat-een-developer-moet-kunnen)
 - [TamTam/Dept](#TamTam/Dept-x-Frontend-the-TamTam-Way)
 - [Voorhoede](#Voorhoede-x-Frontend-Devs)
 - [Isha Gast & Tom Rovers](#Tom-Rovers-&-Isha-Gast-x-schiphol)
 - [Niels Leenheer](#Niels-Leenheer-x-Bluetooth-Monsters)
 - [Vitaly Friendman](#Vitaly-Friedman-x-Smashing-Magazine)
 - [Bruce Lawson](#bruce-lawson-x-w3c-working-group)
- [Articles](#articles)
  - [Github](#github)
  - [VAR LET & CONST](#var-let-&const)
  - [React](#react)
  - [Working in a Team](#working-in-a-team)


***
###  Titus Wormer x Git & GitHub
<details>
	<summary>Show Sketchnotes</summary>
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned.jpg">
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned2.jpg">
</details>

#### Interessting Subjects

- Github
- Git
- IBM
- OpenSource
- Licenses

***
### Peter Paul Koch x Wat een developer moet kunnen
<details>
	<summary>Show Sketchnotes</summary>
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned3.jpg">
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned4.jpg">
</details>

#### Interessting Subjects

- Natives Apps
- A history of browsers
- Polyfills
- Webkit
- OpenSource

***
### TamTam/Dept x Frontend the TamTam Way
<details>
	<summary>Show Sketchnotes</summary>
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned5.jpg">
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned6.jpg">
</details>

#### Interessting Subjects

- Virtual Reality
- Augmented Reality
- BrowserStack
- BEM conventions

***
### Voorhoede x Frontend Devs
<details>
	<summary>Show Sketchnotes</summary>
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned7.jpg">
</details>

#### Interessting Subjects

- Baseline product
- Acceptable product
- Enjoyable product
- CanIuse
- Pattern Primer

***
### Tom Rovers & Isha Gast x schiphol
<details>
	<summary>Show Sketchnotes</summary>
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned8.jpg">
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned9.jpg">
</details>

#### Interessting Subjects

- Accesability
- Funkyfy
- GOV.UK
- Inclusive Design
- Screenreaders
- Display none vs Visability Hidden

***
### Niels Leenheer x Bluetooth Monsters
<details>
	<summary>Show Sketchnotes</summary>
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned10.jpg">
</details>

#### Interessting Subjects

- Bluetooth in de browser?
- Classic vs Low energie
- Android Decompile
- User experience is better?

***
### Vitaly Friedman x Smashing Magazine
<details>
	<summary>Show Sketchnotes</summary>
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned11.jpg">
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned12.jpg">
</details>

#### Interessting Subjects

- Pixel Perfect
- Mailchimp
- Memorable Websites
- Don't make me think
- Good or bad design? Need context
- Loved or hated

***
### Bruce Lawson x W3C Working Group
<details>
	<summary>Show Sketchnotes</summary>
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned13.jpg">
	<img src="https://github.com/jajan20/weekly-nerd/blob/master/images/weekly-nerd-cleaned14.jpg">
</details>

#### Interessting Subjects
- Webstanderds
- Rails (horse asses)
- W3C
- Extensible Web Manifesto
- React
- Web Dev (not an adult job in the UK)

## Articles
***
## Github
At the start of the semester, Titus Wormer was one of the first lecturers that gave a lecture about the use of Github and Git. During the minor, I've learned to use both but at the end of the final project approaches, I can tell with certainty that I've learned the value that Git and Github add to a project.

### Git versus Github
It is really important to know that Git and Github are different systems. Git is a version control system that tracks your files in a working directory where GitHub is a social platform where people can push their files to. 

### Novice
When the minor started it was difficult for me to follow along and keep track of my files. Stubbornly I kept on saving my files locally and made backups by hand.

### Why Github is nice to use
As I've explained earlier, Github is a social platform where you can push your Git versions too. So when you want to use Github you need to initialize Git in your working directory. Below I've written a couple of easy to follow steps on how to set up your Git together with Github. (I work on a MacBook, the steps below are meant for the terminal.)

#### Step 1:
First, you'll need to navigate to the project directory from which you will start working.  You can do this by opening your terminal and write down the command.  <pre>cd Documents/Projects/scheepvaart-museum/</pre>
This is the path for me, yours can be totally different.

#### Step 2: 
When you're inside the folder you can initialize the version control with the command: <pre>git init</pre> now whenever you change a file inside this folder the version control will keep an eye out for the changes.

#### Step 3: 
Everyone once in a while you need to commit your changes, this will be your roadmap for future references. By using the command: <pre>git add .</pre>
You add every changed file to the stage. Then if you run the command <pre>git commit -m</pre>  You are prompted with a question to add a commit message. Keep these messages short and useful.

These are the three steps you need to do in order for Git to keep track of your files. The next step would be to add them to your Github repo. But before I dive into that I will explain how useful Github is with group projects. The best way to explain would be to use my own project as an example.

#### The use of Github inside a group project
Since a lot of people are going to be working on different bits of code it would be hard to keep track of this manually. Git can track all your files locally but when different people need to use the same code this becomes a bit more complicated.

This is where Github (and the next steps) come in. As a group, you can set up a repo and add everyone that needs access to the project. Once initialize every user can clone that repo to their own computer. Whenever someone writes new pieces of code they can push their changes to the repo and Github will keep track of these files. When a different user "pulls" your changes to their directory. The files get updated.
Github shows all the changes made by every user so it's really easy to see who did what. As a failsafe, you can change some of the settings so that every commit to the group project needs to be reviewed by one of the members. This ensures that code doesn't conflict with each other.

#### Step 4
<pre>git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY</pre>
This will clone the Github repo to your local machine.

#### Step 5
Whenever you've written some code repeat the steps and you'll be committing to Github.

### Conclusion
First starting with Git and Github can be challenging, for me it was partly being too stubborn to grasp the concept cause it felt like to much trouble.
With the last project, I didn't have a choice and was forced to learn all the bits needed to commit code to the project branch. This made me realize that working with Git and Github is a big help during my projects.

## VAR LET & CONST
So at the start of the minor, I hadn't been using ES6 all that much, but at the beginning of the project the teachers said we could try ES6 and see how far we could go.

The first thing that confused me was that var was "gone" and that we could use let and const variables instead. But what they meant? And what the correct way of using was? I didn't know and after some research, I found out that no one knows that correct way, cause there isn't one. Some ways are better than others and with the examples below I'll try to explain why you should use them, but how you implement them is all up to you.

### Differences
Variables declared with VAR can be redeclared throughout your code. This could result in some buggy code which no one wants. LET can't be redeclared, the following example will return the error: 'Identifier 'Points' has already been declared'

```js
const key = 'abc123'
let points = 50
let winner = false

let points = 60
```

But if you change let into var it's allowed. You can't redeclare a LET variable, but you can update one:

```js
points = 60
```

This will update the value to 60. 

There is a difference between LET and CONST and that is const variables cannot be updated let variables are made to be updated.

```js
const person = {
    name: 'Jamie',
    age: '28'
}
```

if we try to change the person object with: 

```js
person = {
    age: '30'
}
```

This will return the already declared error. But you can update the properties of a const by writing the following:

```js
person.age = '30'
```

### Immediately Invoked Function Expression
This is a way for developers to make sure VAR doesn't leak into the parent scope. If you just write code and declare a VAR this means it'll be in the global scope. Problem with this is that other scripts could be using the same variable names and you've just overwritten theirs. In turn, this could make your code buggy. How did they work with this?

```js
(function() {
    var name = 'Jamie'
})()
```

Since VAR is function scoped by writing an IIFE the VAR is contained within the function and it will not leak out to its parents. The difference with LET and CONST is that they are block scoped and instead of writing a function you can just create an object scope.

```js
{
    const name = 'jamie'
}
```

### Loops
Another good example for showing the difference are loops. If you run the code below inside your console the variable i is leaked out into the global scope and can be called upon. We don't need I to be available there, it's just for us so we can use loops.

```js
for (var i = 0; i < 10; i++) {
    console.log(i)
}
```

The next example will set a timeout of a second and will return the number is 10, 10 times. This because right at the start i is looped and being overwritten and when the timeout hits the value is 10.

```js
for (var i = 0; i < 10; i++) {
    setTimeout(function() {
        console.log('The number is ' + i)
    }, 1000)
}
```
The problem is that when the first setTimeout is runned. the variable i is already 10.
One way to fix that is we can change the var into the LET. LET is block scoped, so the variable can't be overwritten.

```js
for (let i = 0; i < 10; i++) {

    setTimeout(function() {
        console.log('The number is ' + i)
    }, 1000)
}
```

### What should I use?
So after trying a couple of things out I still haven't come up with a definitive answer. But VAR is something I try to avoid. After reading some research and watching some really smart people talk about this subject I found two people who explain it best. Links can be found below

- [Kyle Simpson](https://frontendmasters.com/courses/es6-right-parts/const/)
- [Mathias Bynens](https://mathiasbynens.be/notes/es6-const)

### Conclusion
I'll try to keep Mathias Bynes method cause for me this feels like the correct way of using CONST and LET.

## React

### What is react?
React is a framework developed by Facebook. A framework that helps to work in components. With React it's easier to make web pages feel like native app cause of the way the code works. For example, with vanillaJS you'd write a bunch of code use some HTML and add some styling. Once you run the code everything is rendered onto the page. If you change something the page completely reloads even though you just changed one thing.

React is different, a webpage usually has the same containers/modules if you will. Like a header, body, footer etc. Inside the body, you can have different containers as well. Let's say we have a list of names generated from our data. With React we can put that list inside its own container and when we add a new name just render the bits that have changed instead of the whole page. This will cut loading times significantly and it'll feel like an app.

### JSX
React works a bit different compared to VanillaJS. Basically, you write the same code, but for optimal performance and reusability, you write in JSX. The example below shows a simple react component that creates a form.

```jsx
import React from 'react'

class Example extends React.Component {
    render() {
        return (
            <form className="example"></form>
        )
    }
}

export default Example
```

Like I explained earlier, React works in components. To use components on different pages you need to import React and export the module so that you can reuse your components. A couple of other things to know is that the attributes class and for don't work inside JSX. In essence, you're writing JavaScript inside your HTML and those attributes are already reserved for other things inside JavaScript. That's why you use className and htmlFor. These work exactly the same way but are called different.

All tags like 
```html 
<br> <hr> <img> & <input>
```

Are self-closing, so we usually don't write anything behind them. With JSX you need to close them.
```html
<input />
```

### Stateless Function Component
Sometimes components will be so simple, that they will only do one thing. If you don't need any other methods inside your component except the render method we can use a stateless function:

<strong>Stateless Function Component</strong>
```jsx
const Example = (props) => {
    return (
            <header>
                <h1>This will always be the same</h1>
            </header>
        )
}

export default Example
```
<strong>Full React Component (in which you can use more methods)</strong>
``` jsx
class Example extends React.Component {
    render() {
        return (
            <header>
                <h1>This will always be the same</h1>
            </header>
        )
    }
}

export default Example
```
For my project, I tried using both, but after refactoring my code a couple of times I don't have that many separate components.
The biggest aha moment is that inside the class component (inside the render method) you can refer to this. But with the stateless function, there's no this and you can pass props.

---

### States vs Props
With a state, you can only access information that is available inside the component.

``` jsx
class AnotherExample extends React.Component {
    state = {
        name: "Jamie"
    }
    render() {
        return (
            <div>Hello {this.state.name}</div>
        )
    }
}
```

``` jsx
class AnotherExample extends React.Component {
    render() {
        return (
            <div>Hello {this.props.name}</div>
        )
    }
}

<AnotherExample name="Jamie"/>
```

Props or properties we can pass to the component using attributes. Then we can access them inside the component.

### Constructor and Super
This concept is still really abstract for me. But as I understand it. Once you create a react component and you want to add your own methods you need the constructor and super otherwise the methods won't work.

```jsx
constructor(){
    super()
}
```

### Conclusion
A lot of developers pick a side and stay with it, I just recently started experimenting with React and I realized that even though it is really good at what it does you don't always need it. and I think that's something that goes for every framework. So think about what you want to make and make a decision based on your needs rather than just blindly following what you already know.

## Working in a Team
This article will be about the choice I had to make for the last project during the minor everything web. More specifically about how I had a hard time deciding if I should tackle the project alone, or that I would be better off in a group. Spoiler alert! I went for a group project.

### The client
Our first meeting was with the client and all the other classmates who had decided they wanted to be on this project. No group was formed cause that was something we could decide on our own and we thought it would be better to hear the assignment first before making decisions. As we listened to what the client expected from this project it became clear that at the end of the 9 weeks they would like to see a nearly finished product on which they could continue working. This expectation pointed us in the direction of joining hands and work on it together. Because doing it alone wouldn't meet their needs. We started with 8 people, but after the first meeting 2 others dropped out and we were left with 6, including myself. 

### The Pro and Con
Let me tell you, a group of 6 individuals all with different levels of knowledge trying to build a complete project in 9 weeks to meet the needs of their client is quite a challenge. Especially if you don't know them very well. For example, my knowledge level wasn't that high compared to a couple of others, it's easy getting swept up in their ideas. Because you think to yourself, they know so much more it's probably better. I'll talk more about this later.

**Pro**
- Because we were a group of 6 people, idea generation went very well.
- We had people with more experience in visual design, coding and animation.
- Getting to know new people, learning new stuff from other group members.
- Everyone worked well together, so whenever one of us was stuck we could rely on team members.

**Con**
- Some were better at programming than others, which resulted in them having the deciding votes (for example, a feature that would be hard to implement. Someone knowledgeable would know it could take a while to create, so let's not implement)
- Because everyone is new, you don't know how well you can count on each other. Which meant that you'd do a lot more yourself instead.
- At the beginning 6 people are really nice, but once you have the idea on paper and there's coding to be done. 6 people can be really difficult.

### The standups
One of the ways we tried to make our group dynamic work was by using short standups every morning. This way we could express concerns, share ideas, tell other about the progress you've made and what's good and what's not going well. Important about these standups is that they're not for social bonding, keep them short and keep the content meaningful.

### The feedback
Every week we had meetings with our client and our teachers, when you're working alone it's easier to use the feedback. When in a group where everyone gets feedback it'll be a lot harder to implement them. Everyone wants to pass the assignment and everyone wants to finish the project. So how do you work this out? The best way for us was having meetings with our team after we received feedback. This way we could talk about everything we talked about and decide as a group what we could use in our project.

### The conclusion
After 9 weeks of working together, I've learned a lot. I learned about real teamwork, about getting to know new people. But above all, I became better at handling pressure and stress. Would I make the same decision again? With the knowledge, I have now: Yes, but if I would do it over again I don't know. Even though I learned a lot because group members had more experience, I also think that exactly because of this reason that I skipped a few fundamentals. 


