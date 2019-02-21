## **Session 1**

### **1. Web Developer & Technology**

**_Front-End vs Back-End vs Full-Stack_**

**_Front-End_**

Front-end developers are responsible for a website’s user-facing code and the architecture of its immersive user experiences. In all, a front-end dev is responsible for the interior design of a house that’s been built by a back-end dev. 

Skills/Tools/languages: HTML, CSS, Javascript programming. Addition: Bootstrap, Foundation, Backbone, AngularJS, ReactJS, EmberJS, jQuery, LESS, Ajax, etc.

**_Back-End_**

A back-end developer builds and maintains the technology that powers those components which, together, enable the user-facing side of the website to even exist in the first place.

Skills/Tools/languages: PHP, Ruby, Python, Java, .Net, MySQL, Oracle, SQL Server, PHP frameworks (Zend, Symfony, and CakePHP), etc.

**_Full-Stack_**

A full stack developer can work cross-functionally on the full “stack” of technology, i.e. both the front end and back end. Full stack developers offer the full package.

Skills/Tools/languages: setting up and configuring Linux servers, writing server-side APIs, diving into the client-side JavaScript powering an application, and turning a “design eye” to the CSS.


![Frameworks-Libraries-Languages for Frontend, Backend, Fullstack](http://www.inventivewheel.com/wp-content/uploads/2016/02/Frameworks-1.png)

#### **_Reference Links_** 

- [Explanation about Frontend, Backend, Fullstack //by: Udacity](https://blog.udacity.com/2014/12/front-end-vs-back-end-vs-full-stack-web-developers.html)

- [Explanation about Frontend, Backend, Fullstack //by: Makers Institute](https://medium.com/@makersinstitute/front-end-back-end-full-stack-apa-artinya-36e0f25e8142)

---

### **2. Web Architecture**

![Rendering on The Web Infographic](https://developers.google.com/web/updates/images/2019/02/rendering-on-the-web/infographic.png)

There are two main, different approaches to rendering a website — on the server or on the client:

1. Server-side rendering (SSR) means a website is rendered on the server, so it offers quicker first load, but navigating between pages requires downloading everything every single time. SSR renders the React components on the server. The output is HTML content.

![SSR Process](https://cdn-images-1.medium.com/max/1600/1*jJkEQpgZ8waQ5P-W5lhxuQ.png)

2. Client-side rendering (CSR) allows the website to be updated in the browser almost instantly when navigating to different pages, but requires more of an initial download hit and extra rendering on the client at the beginning. The website is slower on an initial visit, but much faster on subsequent visits. Your browser downloads a minimal HTML page. It renders the JavaScript and fills the content into it.

![CSR Process](https://cdn-images-1.medium.com/max/1600/1*CRiH0hUGoS3aoZaIY4H2yg.png)

**_Single Page Application (SPA) vs Server Side Rendering (SSR) vs Progressive Web App (PWA)_**

- Single page applications are JavaScript heavy websites that by pure definition rely on a single web page with client-side, dynamically rendered markup. Instead of loading individual pages (HTML) completely from the server, either partial markup or data is loaded from the server and composed in the browser before rendering markup in the DOM.

- PWAs are web apps developed using a number of specific technologies and standard patterns to allow them to take advantage of both web and native app features. For example, web apps are more discoverable — it's a lot easier and faster to visit a website than install an application, and you can also share web apps via a link.

PWAs can be built using any approach you like, but some will work better than the others. The most popular approach is the "app shell" concept, which mixes SSR and CSR, and in addition follows the "offline first" methodology. Mixing SSR with CSR can lead to the best results — you can render a website on the server, cache its contents, and then update the rendering on the client-side as and when needed. The first page load is quick because of the SSR, and the navigation between pages is smooth because the client can re-render the page with only the parts that have changed.

There is also a new approach involving the [Streams API](https://developer.mozilla.org/en-US/docs/Web/API/Streams_API)

_Example_

SPA: mail.google.com (no need SEO)

SSR: majority sites using SSR

PWA: traveloka, bukalapak (similar SPA)

#### **_Reference Links_** 

- [Explanation about PWA Architecture //by: Dev Google](https://developers.google.com/web/ilt/pwa/introduction-to-progressive-web-app-architectures)

- [Explanation about PWA Architecture //by: Dev Mozilla](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/App_structure)

- [Explanation about PWA and SPA //by: Blog Love2dev](https://love2dev.com/blog/pwa-spa/)

- [Explanation about SSR or CSR for PWA //by: Blog Krusche Company](https://kruschecompany.com/blog/post/ssr-or-csr-for-progressive-web-app)

- [Explanation about SSR for React App //by: Freecodecamp](https://medium.freecodecamp.org/server-side-rendering-your-react-app-in-three-simple-steps-7a82b95db82e)

---

### **3. Framework JS** 

React vs Vue vs Angular 

- React:

(+) High performance, render pixel detail (using component)

(-) Bad documentation lifecycle, not available good framework recommended from developer React (only 3rd party)

- Vue:

(+) good documentation lifecycle, good framework recommended from developer Vue (similar html)

(-) Little bit low performance

- Angular -> Typescript

![React vs Vue vs Angular](https://dzone.com/storage/temp/10880637-inforgrafic-react-angular-vue.jpg)

- [Explanation about React vs Vue vs Angular //by: Dzone](https://dzone.com/articles/react-vs-angular-vs-vuejs-a-complete-comparison-gu)

- [Explanation about React vs Vue vs Angular //by: Vuejs](https://vuejs.org/v2/guide/comparison.html)

### **4. Nodejs**

Server side (Now Js can compile, not only client side)

### **5. Git Intro**

Git Basic syntax (config, status, remote, add, commit, push)

![Git Development Process](https://livablesoftware.com/wp-content/uploads/2017/11/Github-EN.jpg)

![Git Cheat Sheet](https://raw.githubusercontent.com/hbons/git-cheat-sheet/master/preview.png)

### **7. Working directory**

CLI Basic syntax (cd, mkdir, touch, nano)

### **8. Html intro**

Create simple web & push to Gitlab


#### **_Notes_** 

##### **1. SPA vs MPA**

![SPA vs MPA](https://www.mindk.com/blog/wp-content/uploads/2018/03/1.png)

- [Explanation about Comparison SPA vs MPA //by: Ruby Garage](https://rubygarage.org/blog/single-page-app-vs-multi-page-app)

- [Explanation about Comparison SPA vs MPA //by: Medium @NeotericEU](https://medium.com/@NeotericEU/single-page-application-vs-multiple-page-application-2591588efe58)

##### **2. ReactJs vs React Native**

![ReactJs vs React Native](https://www.konstantinfo.com/blog/wp-content/themes/konstantinfo/imageC.php?image=/2018/03/ReactJS-and-React-Native-1.jpg)

- [Explanation about ReactJs vs React Native //by: Refactory](https://refactory.id/post/39-reactjs-vs-react-native)

- [Explanation about ReactJs vs React Native //by: Cognitive Clouds](https://www.cognitiveclouds.com/insights/what-is-the-difference-between-react-js-and-react-native/)

- [Explanation about React Native vs Real Native App //by: Hackernoon](https://hackernoon.com/react-native-vs-real-native-apps-which-is-better-a8383d6f7ca5)

##### **3. Framework vs Library**

![Framework vs Library](https://i2.wp.com/www.dunebook.com/wp-content/uploads/2018/06/choosing-your-pearl-in-jocean-5-638.jpg?w=638&ssl=1)

Martin Fowler said:
> A library is essentially a set of functions that you can call, these days usually organized into classes. Each call does some work and returns control to the client.

> A framework embodies some abstract design, with more behavior built in. In order to use it you need to insert your behavior into various places in the framework either by subclassing or by plugging in your own classes. The framework's code then calls your code at these points.

- [Explanation about Framework vs Library //by: Freecodecamp](https://medium.freecodecamp.org/the-difference-between-a-framework-and-a-library-bd133054023f)

---
