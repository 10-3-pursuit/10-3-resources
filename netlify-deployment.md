# NETLIFY DEPLOYMENT

**Netlify is a great environment for deploying both ReactJS and static applications.
Check out the videos below to see how to connect your Github repo to Netlify**

**SPECIAL NOTE FOR `REACT ROUTER` users:**
If you are using `React Router` in your application, you will need to take an extra step. The default configuration on Netlify only shows a React App's root (home page) view. If you have configured React Router, have an about page (or any other page view), and sent a URL to the /about page to a friend, it will give a 404 or redirect back to the home view.

To configure the ability to send a specific page view URL, you must create a file called `\_redirects` inside your app's public folder.

This file (public/\_redirects) must contain the following text:

```js
/* /index.html 200
```

[Redirect Article & Explanation](https://ridbay.medium.com/react-routing-and-netlify-redirects-fd1f00eeee95)

[Netlify Redirect Docs](https://docs.netlify.com/routing/redirects/redirect-options/)

### VIDEOS

- [Deploy to Netlify](https://drive.google.com/file/d/1rOyr5I9Gir3mt9-NUeQUnM2uOZLknfZr/view?usp=sharing) - upload your Github application to Netlify and have a live site on the web.
- [Update Deployed Application](https://drive.google.com/file/d/1dD07Wut9-NWk_EPayhxAiJ7_IP3DZu_m/view?usp=sharing) - push to your Github main branch and trigger an update on Netlify
- [Add Enveronment Variable](https://drive.google.com/file/d/1StpT3iToip0g9p8SenBlzK5u2lwStgt0/view?usp=sharing) - add an API key to your Netlify application

### DEPLOYMENT INSTRUCTIONS

- [Deploying a Vite React App with Netlify](https://github.com/pursuit-curriculum-resources/guide-deployment/tree/main/netlify-vite-react)

[Home][def]

[def]: README.md
