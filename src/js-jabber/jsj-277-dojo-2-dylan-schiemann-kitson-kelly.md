---
layout: layouts/post.njk
title: >
  JSJ 277: Dojo 2 with Dylan Schiemann and Kitson Kelly
date: 2017-09-05 05:00:51
episode_number: 277
duration: 1:02:52
audio_url: https://media.devchat.tv/js-jabber/JSJ_277_Dojo_2_with_Dylan_Schiemann_and_Kitson_Kelly.mp3
podcast: js-jabber
tags:
  - js_jabber
  - podcast
---

# JSJ 277: Dojo 2 with Dylan Schiemann and Kitson Kelly

This episode of JavaScript Jabber features panelists Aimee Knight, Cory House, and Charles Max Wood. They talk with Dylan Schiemann and Kitson Kelly about Dojo 2.**[00:02:03] Introduction to Dylan Schiemann**Dylan is the CEO at Sitepen and co-founder of the Dojo Toolkit.**[00:02:22] Introduction to Kitson&nbsp;**Kitson is the CTO at Sitepen and project lead for Dojo 2.**[00:02:43] Elevator Pitch for Dojo**Dojo 1 has been around forever. Started back in 2004 as a way to solve the challenge of "I want to build something cool in a browser." Promises and web components were inspired by or created by Dojo. It's been a huge influence on the web development community. Dojo 2 is a ground up re-write with ES 2015, TypeScript and modern API's. It's a modernized framework for Enterprise applications.**[00:04:29] How is Dojo different from other frameworks?**There's a spectrum: small libraries like React with an ecosystem and community of things you add to it to Angular which is closer to the MV\* framework with bi-directional data binding. Vue lands somewhere in the middle. Dojo 2 is also somewhere in the middle as well. It's written in TypeScript and has embraced the TypeScript experience.**[00:06:00] Did the Angular 2 move influence the Dojo 2 development and vice-versa?**Dojo 2 had moved to TypeScript and 2 days later Angular announced that they were going to TypeScript. Angular also moved very quickly through their BETA phase, which caused some challenges for the Angular community. With Dojo 2, they didn't start the public discussion and BETA until they knew much better what was and wasn't going to change. They've also been talking about Dojo 2 for 6 or 7 years. The update was held up by adoption of ES6 and other technologies. Dojo 1 was also responsible for a lot of the low-level underpinning that Angular didn't have to innovate on. Dojo 2 was built around a mature understanding of how web applications are built now. People doing Enterprise need a little more help and assistance from their framework. Dojo provides a much more feature rich set of capabilities. Angular could have pushed much more of TypeScript's power through to the developer experience. Dojo much more fully adopts it. It's also easier if all of your packages have the same version number. Call out to Angular 4 vs Angular 2.**[00:12:44] AMD Modules**Why use AMD instead of ES6 modules? You can use both. Dojo 2 was involved in the creation of UMD. James Burke created UMD while working on Dojo. ES6 modules and module loading systems weren't entirely baked when Dojo 2 started to reach maturity, so they went with UMD. It's only been a few months since Safari implemented the ES6 module system. Firefox and friends are still playing catchup. The Dojo CLI build tool uses webpack, so it's mostly invisible at this point. So, at this point, should I be using UMD modules? or ES6? Is there an advantage to using AMD? With TypeScript you'd use ES6 modules, but UMD modules can be loaded on the fly.**[00:16:00] Are you using Grunt?**Internally, for tasks we use Grunt. But for users, we have a CLI tool that wraps around Webpack. For package builds and CI, Grunt is used.**[00:18:30] What is the focus on Enterprise all about?**There are a lot of different challenges and complexities to building Enterprise apps. Dojo was the first framework with internationalization, large data grids, SVG charts, etc. Dojo has spend a long time getting this right. Many other systems don't handle all the edge cases. Internationalization in Angular 2 or 4 seems unfinished. Most Dojo users are building for enterprises like banks and using the features that handle large amounts of data and handle those use cases better.**[00:21:05] If most application frameworks have the features you listed, is there a set of problems it excels at?**The Dojo team had a hard look at whether there was a need for their framework since many frameworks allow you to build great applications. Do we want to invest into something like this? React has internationalization libraries. But you'll spend a lot of time deciding which library to use and how well it'll integrate with everything else. A tradeoff in decision fatigue. In the Enterprise, development isn't sexy. It's necessary and wants to use boring but reliable technology. They like to throw bodies at a problem and that requires reliable frameworks with easily understood decision points. Producing code right is a strong case for TypeScript and they pull that through to the end user. Many frameworks start solving a small set of problems, become popular, and then bolt on what they need to solve everything else... Dojo tried to make sure it had the entire package in a clear, easy to use way. You can build great apps with most of the big frameworks out there. Dojo has been doing this for long enough that they know where to optimize for maintainability and performance.**[00:29:00] Where is Dojo's sweet spot?&nbsp;**[The Sitepen Blog series on picking a framework](https://www.sitepen.com/blog/2017/06/13/if-we-chose-our-javascript-framework-like-we-chose-our-music/)The biggest reason for using Dojo over the years is the data grid component. They also claim to have the best TypeScript web development experience. You may also want a component based system with the composition hassles of React. The composability of components where one team may write components that another uses is a big thing in Dojo where one person doesn't know the entire app you're working on. Theming systems is another selling point for Dojo.**[00:34:10] Ending the framework wars**Try Dojo out and try out the grid component and then export it to your Angular or React app. There are a lot of frameworks out there that do a great job for the people who use them. The focus is on how to build applications better, rather than beating out the competition. Sitepen has build apps with Dojo 2, Angular, React, Dojo + Redux, etc.**[00:39:01] The Virtual DOM used by Dojo**2 years ago or so they were looking for a Virtual DOM library that was small and written in TypeScript. They settled on [Maquette](https://maquettejs.org/). The more you deal with the DOM directly, the more complex your components and libraries become. Makes things simpler for cases like server side rendering getting fleshed out in BETA 3. It also allows you to move toward something like React Native and WebVR components that aren't coupled to the DOM. They moved away from RxJS because they only wanted observables and shimmed in (or polyfilled) the ES-Next implementation instead of getting the rest of the RxJS &nbsp;that they're not using.**[00:46:40] What's coming next?**They're finishing Dojo 2. They're polishing the system for build UI components and architecture and structuring the app. They plan to release before the end of the year. They're also wrapping up development on the Data Grid, which only renders what shows on the screen plus a little instead of millions of rows.**[00:49:08] Testing**They've got[intern](https://theintern.io). It pulls together unit testing, functional testing, continuous integration hooks, accessibility testing, etc. It's rewritten in TypeScript to take advantage of modern JavaScript. The Dojo CLI uses intern as the default test framework. Kitson build the [test-extras](https://github.com/dojo/test-extras) library to help with Dojo testing with intern. **Dojo Links**

- [dojo.io](https://dojo.io)
- [github.com/dojo/meta](https://github.com/dojo/meta)
- [sitepen.com/blog](https://sitepen.com/blog)
- [gitter channel](https://gitter.im/dojo/dojo2)
- [github.com/dylans](https://github.com/dylans)
- [twitter.com/dylans](https://twitter.com/dylans)
- [twitter.com/sitepen](https://twitter.com/sitepen)
- [twitter.com/dojo](https://twitter.com/dojo)
- [github.com/kitsonk](https://github.com/kitsonk)
- [twitter.com/kitsonk](https://twitter.com/kitsonk)
  **Picks** Cory
- [Amateur vs Professional](https://www.farnamstreetblog.com/2017/08/amateurs-professionals)
  Aimee
- [DevFest Florida](https://www.eventbrite.com/e/devfest-florida-2017-tickets-31833188925?discount=JSJABBER) (use code 'jsjabber')
  Chuck
- Taking some time off
- [AudioTechnica ATR2100](https://amzn.to/2j8VKRJ)
- [How to define your life purpose in 5 minutes](https://www.youtube.com/watch?v=vVsXO9brK7M)
  Dylan
- [zenhub](https://www.zenhub.com/)
- [HalfStack Conference](https://halfstackconf.com)
- [How to choose a framework series on the Sitepen Blog](https://www.sitepen.com/blog/2017/06/13/if-we-chose-our-javascript-framework-like-we-chose-our-music/)
  Kitson
- [Dunbar Number](https://en.wikipedia.org/wiki/Dunbar%27s_number)
  &nbsp;

### Transcript