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

- [Frontend, Backend, Fullstack //by: Udacity](https://blog.udacity.com/2014/12/front-end-vs-back-end-vs-full-stack-web-developers.html)

- [Frontend, Backend, Fullstack //by: Makers Institute](https://medium.com/@makersinstitute/front-end-back-end-full-stack-apa-artinya-36e0f25e8142)

---

### **2. Web Architecture**

![Infographic: Rendering on The Web](https://developers.google.com/web/updates/images/2019/02/rendering-on-the-web/infographic.png)

There are two main, different approaches to rendering a website — on the server or on the client:

1. Server-side rendering (SSR) means a website is rendered on the server, so it offers quicker first load, but navigating between pages requires downloading everything every single time. 

![SSR Process](https://cdn-images-1.medium.com/max/1600/1*jJkEQpgZ8waQ5P-W5lhxuQ.png)

2. Client-side rendering (CSR) allows the website to be updated in the browser almost instantly when navigating to different pages, but requires more of an initial download hit and extra rendering on the client at the beginning. The website is slower on an initial visit, but much faster on subsequent visits. 

![CSR Process](https://cdn-images-1.medium.com/max/1600/1*CRiH0hUGoS3aoZaIY4H2yg.png)


**Server Side Rendering (SSR) vs Single Page Application (SPA) vs Progressive Web App (PWA)**

**_Server Side Rendering (SSR)_**

SSR renders the React components on the server. The output is HTML content. Majority sites using SSR.

_Pros_

- Good for Search Engine Optimization (SEO).

- Improve Performance.

_Cons_

- SSR can improve performance if your application is small. But it can also degrade performance if it is heavy.

- It increases response time (and it can be worse if the server is busy).

- It increases response size, which means the page takes longer to load.

- It increases the complexity of the application.

**_Single Page Application (SPA)_**

SPAs are JavaScript heavy websites that by pure definition rely on a single web page with CSR, dynamically rendered markup. Web browser downloads a minimal HTML page. It renders the JavaScript and fills the content into it. Example: mail.google.com

_Pros_

- Suitable for dynamic content.

- Website more faster on subsequent visits.

_Cons_

- Worse for Search Engine Optimization (SEO).

**_Progressive Web App (PWA)_**

PWAs are web apps developed using a number of specific technologies and standard patterns to allow them to take advantage of both web and native app features. PWAs can be built using any approach you like, but some will work better than the others. The most popular approach is the "app shell" concept, which mixes SSR and CSR, and in addition follows the "offline first" methodology. Mixing SSR with CSR can lead to the best results — you can render a website on the server, cache its contents, and then update the rendering on the client-side as and when needed. Example: Traveloka, Bukalapak.

_Pros_

- Web apps are more discoverable — it's a lot easier and faster to visit a website than install an application. It means, the first page load is quick because of the SSR, and the navigation between pages is smooth because the client can re-render the page with only the parts that have changed.

- Share web apps via a link

- It accessible, both online and offline

- It affordable. It work on multiple platforms, therefore reducing the cost of development, unlike their native counterparts

- It increases user retention. The user doesn’t need to reload it again and again to view it

- Indexable and linkable; SEO techniques are applicable on PWAs just like they are on a website

- No conventional installation process

- Inclusion of Push Notifications

_Cons_

- Missing Out on App Store Traffic

- High Battery Usage

- Unable to Access Various Device Features: NFC, Bluetooth, proximity sensors, ambient light, advanced camera controls, geofencing, wake lock, contacts, and more, which could make the app less personal for users.


Btw, Love2dev said:

> A SPA can be a PWA, but a PWA does not have to be a SPA.

Besides that, Krusche Company said:

> Creating a PWA **doesn’t necessarily imply creating it from scratch**. If you’re developing a modern SPA (Single Page Application), most probably you implement something similar to an app shell. PWA doesn’t include anything extraordinary, considering architecture and items to render: HTML, CSS and JS files, images, media, fonts, data used by JS to create content. Until recently, the most advantageous strategy to migrate was to rely on SSR (Server Side Rendering), a mature technique with rich tooling, which is not only perfect to render static content, but is also suitable for SEO and all connected to it.

P.s. There is also a new approach involving the [Streams API](https://developer.mozilla.org/en-US/docs/Web/API/Streams_API)

#### **_Reference Links_** 

- [PWA Architecture //by: Dev Google](https://developers.google.com/web/ilt/pwa/introduction-to-progressive-web-app-architectures)

- [PWA Architecture //by: Dev Mozilla](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/App_structure)

- [PWA and SPA //by: Blog Love2dev](https://love2dev.com/blog/pwa-spa/)

- [SSR or CSR for PWA //by: Blog Krusche Company](https://kruschecompany.com/blog/post/ssr-or-csr-for-progressive-web-app)

- [SSR for React App //by: Freecodecamp](https://medium.freecodecamp.org/server-side-rendering-your-react-app-in-three-simple-steps-7a82b95db82e)

- [Pros-Cons PWA //by: Freecodecamp](https://clutch.co/app-developers/resources/pros-cons-progressive-web-apps)

---

### **3. Framework JS** 

React vs Vue vs Angular 

- React:

(+) High performance, render pixel detail (using component)

(-) Poor documentation, not available good framework from React developer (framework only from 3rd party)

- Vue:

(+) Simple and rich documentation, good framework recommended from Vue developer 

(-) Little bit low performance

- Angular -> Typescript

![React vs Vue vs Angular](https://dzone.com/storage/temp/10880637-inforgrafic-react-angular-vue.jpg)

#### **_Reference Links_** 

- [React vs Vue vs Angular //by: Dzone](https://dzone.com/articles/react-vs-angular-vs-vuejs-a-complete-comparison-gu)

- [React vs Vue vs Angular //by: Vuejs](https://vuejs.org/v2/guide/comparison.html)

---

### **4. Git Intro**

Git Basic syntax (config, status, remote, add, commit, push)

![Git Cheat Sheet](https://raw.githubusercontent.com/hbons/git-cheat-sheet/master/preview.png)

---

### **5. Working directory**

CLI Basic syntax (cd, mkdir, touch, nano)

---

### **6. HTML Intro**

Create simple web & push to Gitlab

---



#### **_Notes_** 

##### **1. SPA vs MPA**

![SPA vs MPA](http://www.threenetworks.com/blog/wp-content/uploads/2018/01/Single-page-app-or-multiple-page-applications-Three-Networks.jpg)

![Comparasion](https://www.mindk.com/blog/wp-content/uploads/2018/03/1.png)

#### **_Reference Links_** 

- [SPA vs MPA //by: Ruby Garage](https://rubygarage.org/blog/single-page-app-vs-multi-page-app)

- [SPA vs MPA //by: Medium @NeotericEU](https://medium.com/@NeotericEU/single-page-application-vs-multiple-page-application-2591588efe58)

##### **2. ReactJs vs React Native**

![ReactJs vs React Native](https://www.konstantinfo.com/blog/wp-content/themes/konstantinfo/imageC.php?image=/2018/03/ReactJS-and-React-Native-1.jpg)

#### **_Reference Links_** 

- [ReactJs vs React Native //by: Refactory](https://refactory.id/post/39-reactjs-vs-react-native)

- [ReactJs vs React Native //by: Cognitive Clouds](https://www.cognitiveclouds.com/insights/what-is-the-difference-between-react-js-and-react-native/)

- [React Native vs Real Native App //by: Hackernoon](https://hackernoon.com/react-native-vs-real-native-apps-which-is-better-a8383d6f7ca5)

##### **3. Framework vs Library**

![Framework vs Library](https://i2.wp.com/www.dunebook.com/wp-content/uploads/2018/06/choosing-your-pearl-in-jocean-5-638.jpg?w=638&ssl=1)

Martin Fowler said:
> A library is essentially a set of functions that you can call, these days usually organized into classes. Each call does some work and returns control to the client.

> A framework embodies some abstract design, with more behavior built in. In order to use it you need to insert your behavior into various places in the framework either by subclassing or by plugging in your own classes. The framework's code then calls your code at these points.

#### **_Reference Links_** 

- [Framework vs Library //by: Freecodecamp](https://medium.freecodecamp.org/the-difference-between-a-framework-and-a-library-bd133054023f)

---
