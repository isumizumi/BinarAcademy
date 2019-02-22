## **Session 2**

### **1. ReactJS vs React Native**

![ReactJs vs React Native](https://www.konstantinfo.com/blog/wp-content/themes/konstantinfo/imageC.php?image=/2018/03/ReactJS-and-React-Native-1.jpg)

**_ReactJS_**

Cognitiveclouds.com said:

> Remember, React.js is just the V part of the MVC framework, **a library meant for rendering your views**.

_Pros_

- DOM (document object model) is a viewing agreement on data inputs and outputs. React’s virtual DOM is faster than the conventional full refresh model, since the virtual DOM refreshes only parts of the page. The interesting part is, the team at Facebook wasn’t aware that partially refreshing a page would prove faster. Facebook was just looking for a way to reduce their re-build time, and partial DOM refresh was just a happy consequence. This increases performance and faster programming.

- You can reuse code components in ReactJS, saving you a lot of time.

- The rendering of your pages completely, from the server to the browser will improve the SEO of your web app.

- It improves the debugging speed making your developer’s life easier.

- Even to those unfamiliar with React, it is easily readable.

- You reap the benefit of all the advancements in the Java language and its ecosystem.

_Cons_

- Poor documentation: Integrating new features can become a headache for some JavaScript developers. Another circle of hell is the creation of documentation and instructions for this new functionality. To make the situation less harmless, some JavaScript developers write their own instructions for particular tools used in projects.

- The high pace of development: Since the environment changes so fast, it may be hard for some developers to adapt to all these changes and feel comfortable with all the continuous updates.

- React uses JSX, some kind of HTML with JavaScript mixed together. This approach to development provides some benefits. For example, it allows protecting the source code from injections. On the other hand,  according to the opinion of some developers, JSX can become a barrier, especially for new developers.


**_React Native_**

Hackernoon.com said:

> The react native is an **open source framework which transfers the concepts of web development into mobile development**.

_Pros_

- React Native comes with Native Modules and Native components that improve performance. Unlike Cordova, PhoneGap, and other cross-platform frameworks that render code via WebView, React Native renders certain code components with native API’s.

- Saves time: you won’t only save time on developing but on testing and updates too because you’ll just need to test run one app.

- Smooth transitioning: it works with JavaScript, you will be familiar with most of the concepts, and instead of having to learn new and tricky rules.

- Flexibility with open source: You can inspect the code, and this will help you understand the framework better.

_Cons_

- Not for All APIs: it doesn’t support all native APIs. Though you can solve this functionality issue with Native Modules, you will need to have knowledge about the language you’re working with, and this may be something you wanted to avoid when you chose the react native structure over real native.

- Smaller community: it is still at its maturing stages and so doesn’t have a community as large as the real native framework. 

- Design difficulties: If you’re a developer who has worked with both iOS and Android platforms, you know that the apps on each of them look different, even when they are from the same business. Each platform follows its own particular guidelines, and this could mean that while the graphical elements do transform to match, the placement may defer.

#### **_Reference Links_** 

- [ReactJs vs React Native //by: Refactory](https://refactory.id/post/39-reactjs-vs-react-native)

- [ReactJs vs React Native //by: Xb Software](https://xbsoftware.com/blog/price-of-popularity-pros-and-cons-of-reactjs-and-react-native/)

- [ReactJs vs React Native //by: Cognitive Clouds](https://www.cognitiveclouds.com/insights/what-is-the-difference-between-react-js-and-react-native/)

- [React Native vs Real Native App //by: Hackernoon](https://hackernoon.com/react-native-vs-real-native-apps-which-is-better-a8383d6f7ca5)

---

### **2. CSS Intro**

Learn CSS:

- [Learn CSS //by: W3School](https://www.w3schools.com/css/)

- [Learn CSS //by: Dev Mozilla](https://developer.mozilla.org/en-US/docs/Learn/CSS)

- [Learn CSS //by: Codecademy](https://www.codecademy.com/learn/learn-css)


The Difference Between ID and Class:

**_Class_**

- Classes are NOT unique: You can use the same class on multiple elements, and you can use multiple classes on the same element.

- Classes have no special abilities in the browser.

**_ID_**

- ID's are unique: Each element can have only one ID, and each page can have only one element with that ID.

- ID's have special browser functionality. This is the "hash value" in the URL. If you have a URL like http://yourdomain.com#comments, the browser will attempt to locate the element with an ID of "comments" and will automatically scroll the page to show that element. It is important to note here that the browser will scroll whatever element it needs to in order to show that element, so if you did something special like a scrollable DIV area within your regular body, that div will be scrolled too. This is an important reason right here why **having ID's be absolutely unique is important**. So your browser knows where to scroll!

- JavaScript depends on there being only one page element with any particular id, or else the commonly used getElementById function wouldn't be dependable. For those familiar with jQuery, you know how easy it is to add and remove classes to page elements. It is a native and built in function of jQuery. Notice how no such function exists for ID's. It is not the responsibility of JavaScript to manipulate these values, it would cause more problems than it would be worth.

**_P.s._** 

- Elements can have BOTH (an ID and a Class on a single element).

- If you don't need them, don't use them

#### **_Reference Links_** 

[Class vs ID](https://css-tricks.com/the-difference-between-id-and-class/)

---

### **3. Practice using Git on Gitlab**

![Git Development Process](https://livablesoftware.com/wp-content/uploads/2017/11/Github-EN.jpg)

- Create new branch

> git checkout -b name_branch

Sample: git checkout -b develop

P.s.

If you want to create a new branch again after creating a branch develop, then **the parent is not the master but the branch develop**.


- Check status branch

> git branch


- Fetching data pasca merge

> git fetch

> git pull origin name_branch

Sample: git pull origin develop 


- Deleting branch

> git branch -d name_branch

Sample: git branch -d develop

![Git Cheat Sheet](https://raw.githubusercontent.com/hbons/git-cheat-sheet/master/preview.png)

---