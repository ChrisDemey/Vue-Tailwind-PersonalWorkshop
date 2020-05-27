# Vue.js & Tailwind

#### <a href="README.md">Version française</a>

![Tailwind and Vue logo](assets/img/tailwindvue.jpeg)
This mini-workshop aims to show the steps to follow in order to create the basics of a Vue.js project coupled with the Tailwindcss framework.

### VueJS

This is a Javascript framework. So far I think everyone is following it. But we're not going to dwell too much on the details.

If you want good documentation, what better than the <a href="https://fr.vuejs.org/index.html">Vue</a> website !

And for those who are not yet familiar with Vue, here is the <a href="https://github.com/jeandavidwuilquot/VueJS-workshop">workshop</a> of a former BeCodien learner who explains the basics of this framework. Go ahead and read it! And come back when you're ready.

As for the others, we're moving on.

Here we will not use CDN but go through the CLI (Command Line Interface). But don't worry, everything will be fine.

#### Configure and create a Vue project
First of all we will install the Vue package in order to use the required commands (This said with the workshop given above it should already be done!). Open a terminal and type:
```
$ npm install -g @vue/cli
```
Now, still with the terminal, go wherever you want to create your first project that we will call my-app (long live originality) and type:
```
$ vue create my-app
```
You're going to have a choice that will be displayed in the terminal.
- **'default'** : includes babel and eslint.
- **'manually select features'** : allows you to choose what you need for your project.

Let's choose ***Manually select features***.

Then we'll leave ***Babel*** and ***Linter / Formatter*** checked. This will only be for the base, but you are free to choose what else you need. (check and uncheck with the space bar).

Concerning linter, I choose ***ESLint + Standard config***, but to each his choice.
Then ***Lint on save*** is a must.
And finally, the most important! Choose ***In dedicated config files***. This is absolutely necessary for the following.

### TailwindCSS

What the heck is that thing? It is a CSS framework without touching a line of CSS.
Bootstrap aficionados will find their way around pretty quickly, but for the more curious, here's the <a href="https://tailwindcss.com/">website</a>.

Here our ultimate goal, if you didn't understand it, is to make a Vue project **WITHOUT TOUCHING A SINGLE CSS LINE**. This might sound crazy for some people, but you'll see, the magic will work ;)

#### Installation and configuration

As with Vue, open your terminal again, or return to it. But you will have to go back to the root of the previously created project. Then put in this command line:
```
$ vue add tailwind
```
During installation a file **tailwind.config.js** will be created, but with a choice:
- **'none'** : does not create the file.
- **'minimal'** : create the file in minimal version. Allows you to customize only what you need from the framework.
- **'full'** : create the full version of this file. And this allows you to customize the whole Tailwind in your project.

But the best way to start is to choose the ***minimal*** option. No need to import what you won't need to use.

And...... **DONE!!!**

Now it's up to you to play and (re)discover **Vue.js** and **tailwindcss**.