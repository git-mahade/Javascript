<h1 align="center">
<br>
  <a href="https://github.com/leonardomso/33"><img src="https://i.imgur.com/dsHmk6H.jpg" alt="33 Concepts Every JS Developer Should Know" width=200" /></a>
  <br>
    <br>
  33 Concepts Every JavaScript Developer Should Know
  <br><br>
</h1>

[![Follow me](https://img.shields.io/twitter/follow/leonardomso.svg?style=for-the-badge)](https://twitter.com/leonardomso)

## Introduction

This repository was created with the intention of helping developers master their concepts in JavaScript. It is not a requirement, but a guide for future studies. It is based on an article written by [Stephen Curtis](https://twitter.com/stephenthecurt) and you can read it [here](https://medium.com/@stephenthecurt/33-fundamentals-every-javascript-developer-should-know-13dd720a90d1).

**🚀 Considered by GitHub as one of the [top open source projects of 2018!](https://blog.github.com/2018-12-13-new-open-source-projects/)**

## Community

Feel free to submit a PR adding a link to your own recaps or reviews. If you want to translate the repo into your native language, please feel free to do so.

All the translations for this repo will be listed below:

- [Shqip (Albanian)](https://github.com/eldrinf/33-js-concepts-albanian.git) — Eldrin Ereqi
- [اَلْعَرَبِيَّةُ‎ (Arabic)](https://github.com/amrsekilly/33-js-concepts) — Amr Elsekilly
- [汉语 (Chinese)](https://github.com/stephentian/33-js-concepts) — Re Tian
- [Português do Brasil (Brazilian Portuguese) ](https://github.com/tiagoboeing/33-js-concepts) — Tiago Boeing
- [한국어 (Korean)](https://github.com/yjs03057/33-js-concepts.git) — Suin Lee
- [Español (Spanish)](https://github.com/adonismendozaperez/33-js-conceptos) — Adonis Mendoza
- [Türkçe (Turkish)](https://github.com/ilker0/33-js-concepts) — İlker Demir
- [русский язык (Russian)](https://github.com/gumennii/33-js-concepts) — Mihail Gumennii
- [Tiếng Việt (Vietnamese)](https://github.com/nguyentranchung/33-js-concepts) — Nguyễn Trần Chung
- [Polski (Polish)](https://github.com/lip3k/33-js-concepts) — Dawid Lipinski
- [فارسی (Persian)](https://github.com/majidalavizadeh/33-js-concepts) — Majid Alavizadeh
- [Bahasa Indonesia (Indonesian)](https://github.com/rijdz/33-js-concepts) — Rijdzuan Sampoerna
- [Français (French)](https://github.com/robinmetral/33-concepts-js) — Robin Métral
- [हिन्दी (Hindi)](https://github.com/vikaschauhan/33-js-concepts) — Vikas Chauhan
- [Ελληνικά (Greek)](https://github.com/DimitrisZx/33-js-concepts) — Dimitris Zarachanis
- [日本語 (Japanese)](https://github.com/oimo23/33-js-concepts) — oimo23
- [Deutsch (German)](https://github.com/burhannn/33-js-concepts) — burhannn
- [украї́нська мо́ва (Ukrainian)](https://github.com/AndrewSavetchuk/33-js-concepts-ukrainian-translation) — Andrew Savetchuk
- [සිංහල (Sinhala)](https://github.com/ududsha/33-js-concepts) — Udaya Shamendra
- [Italiano (Italian)](https://github.com/Donearm/33-js-concepts) — Gianluca Fiore
- [Malagasy (Madagascar)](https://github.com/chrys-elrak/33-js-concepts) — Chrys Rakotonimanana

---

## <a id="table-of-contents">Table of Contents</a>

1. **[Call Stack](#1-call-stack)**
2. **[Primitive Types](#2-primitive-types)**
3. **[Value Types and Reference Types](#3-value-types-and-reference-types)**
4. **[Implicit, Explicit, Nominal, Structuring and Duck Typing](#4-implicit-explicit-nominal-structuring-and-duck-typing)**
5. **[== vs === vs typeof](#5--vs--vs-typeof)**
6. **[Function Scope, Block Scope and Lexical Scope](#6-function-scope-block-scope-and-lexical-scope)**
7. **[Expression vs Statement](#7-expression-vs-statement)**
8. **[IIFE, Modules and Namespaces](#8-iife-modules-and-namespaces)**
9. **[Message Queue and Event Loop](#9-message-queue-and-event-loop)**
10. **[setTimeout, setInterval and requestAnimationFrame](#10-settimeout-setinterval-and-requestanimationframe)**
11. **[JavaScript Engines](#11-javascript-engines)**
12. **[Bitwise Operators, Type Arrays and Array Buffers](#12-bitwise-operators-type-arrays-and-array-buffers)**
13. **[DOM and Layout Trees](#13-dom-and-layout-trees)**
14. **[Factories and Classes](#14-factories-and-classes)**
15. **[this, call, apply and bind](#15-this-call-apply-and-bind)**
16. **[new, Constructor, instanceof and Instances](#16-new-constructor-instanceof-and-instances)**
17. **[Prototype Inheritance and Prototype Chain](#17-prototype-inheritance-and-prototype-chain)**
18. **[Object.create and Object.assign](#18-objectcreate-and-objectassign)**
19. **[map, reduce, filter](#19-map-reduce-filter)**
20. **[Pure Functions, Side Effects, State Mutation and Event Propagation](#20-pure-functions-side-effects-state-mutation-and-event-propagation)**
21. **[Closures](#21-closures)**
22. **[High Order Functions](#22-high-order-functions)**
23. **[Recursion](#23-recursion)**
24. **[Collections and Generators](#24-collections-and-generators)**
25. **[Promises](#25-promises)**
26. **[async/await](#26-asyncawait)**
27. **[Data Structures](#27-data-structures)**
28. **[Expensive Operation and Big O Notation](#28-expensive-operation-and-big-o-notation)**
29. **[Algorithms](#29-algorithms)**
30. **[Inheritance, Polymorphism and Code Reuse](#30-inheritance-polymorphism-and-code-reuse)**
31. **[Design Patterns](#31-design-patterns)**
32. **[Partial Applications, Currying, Compose and Pipe](#32-partial-applications-currying-compose-and-pipe)**
33. **[Clean Code](#33-clean-code)**

---

## 1. Call Stack

### Reference

- 📜 [Call Stack — MDN](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)

### Articles

- 📜 [Understanding Javascript Call Stack, Event Loops — Gaurav Pandvia](https://medium.com/@gaurav.pandvia/understanding-javascript-function-executions-tasks-event-loop-call-stack-more-part-1-5683dea1f5ec)
- 📜 [Understanding the JavaScript Call Stack — Charles Freeborn](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)
- 📜 [Javascript: What Is The Execution Context? What Is The Call Stack? — Valentino Gagliardi](https://web.archive.org/web/20180701233338/https://www.valentinog.com/blog/js-execution-context-call-stack/)
- 📜 [What is the JS Event Loop and Call Stack? — Jess Telford](https://gist.github.com/jesstelford/9a35d20a2aa044df8bf241e00d7bc2d0)
- 📜 [Understanding Execution Context and Execution Stack in Javascript — Sukhjinder Arora](https://blog.bitsrc.io/understanding-execution-context-and-execution-stack-in-javascript-1c9ea8642dd0)
- 📜 [How JavaScript Works: An Overview of the Engine, the Runtime, and the Call Stack — Alexander Zlatkov](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)
- 📜 [The Ultimate Guide to Execution Contexts, Hoisting, Scopes, and Closures in JavaScript — Tyler McGinnis](https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/)
- 📜 [How JavaScript Works Under The Hood: An Overview of JavaScript Engine, Heap and, Call Stack — Bipin Rajbhar](https://dev.to/bipinrajbhar/how-javascript-works-under-the-hood-an-overview-of-javascript-engine-heap-and-call-stack-1j5o)

### Videos

- 🎥 [Javascript: the Call Stack explained — Coding Blocks India](https://www.youtube.com/watch?v=w6QGEiQceOM)
- 🎥 [The JS Call Stack Explained In 9 Minutes — Colt Steele](https://www.youtube.com/watch?v=W8AeMrVtFLY)
- 🎥 [What is the Call Stack? — Eric Traub](https://www.youtube.com/watch?v=w7QWQlkLY_s)
- 🎥 [The Call Stack — Kevin Drumm](https://www.youtube.com/watch?v=Q2sFmqvpBe0)
- 🎥 [Understanding JavaScript Execution — Codesmith](https://www.youtube.com/watch?v=Z6a1cLyq7Ac&list=PLWrQZnG8l0E4kd1T_nyuVoxQUaYEWFgcD)
- 🎥 [The Ultimate Guide to Execution Contexts, Hoisting, Scopes, and Closures in JavaScript — Tyler McGinnis](https://www.youtube.com/watch?v=Nt-qa_LlUH0)
- 🎥 [What the heck is the event loop anyway? — Philip Roberts](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- 🎥 [La PILA DE EJECUCIÓN (Call Stack) de JavaScript — La Cocina del Código](https://www.youtube.com/watch?v=ygA5U7Wgsg8)
- 🎥 [How JavaScript Code is executed? ❤️& Call Stack — Akshay Saini](https://www.youtube.com/watch?v=iLWTnMzWtj4&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP)

**[⬆ Back to Top](#table-of-contents)**

---

## 2. Primitive Types

### Reference

- 📜 [JavaScript data types and data structures — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values)

### Articles

- 📜 [How numbers are encoded in JavaScript — Dr. Axel Rauschmayer](http://2ality.com/2012/04/number-encoding.html)
- 📜 [What You Need to Know About JavaScript Number Type — Max Wizard K](https://indepth.dev/posts/1139/here-is-what-you-need-to-know-about-javascripts-number-type)
- 📜 [What Every JavaScript Developer Should Know About Floating Point Numbers — Chewxy](https://blog.chewxy.com/2014/02/24/what-every-javascript-developer-should-know-about-floating-point-numbers/)
- 📜 [The Secret Life of JavaScript Primitives — Angus Croll](https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/)
- 📜 [Primitive Types — Flow](https://flow.org/en/docs/types/primitives/)
- 📜 [(Not) Everything in JavaScript is an Object — Daniel Li](https://dev.to/d4nyll/not-everything-in-javascript-is-an-object)
- 📜 [JavaScript data types and data structures — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values)
- 📜 [Diving Deeper in JavaScripts Objects — Arfat Salman](https://blog.bitsrc.io/diving-deeper-in-javascripts-objects-318b1e13dc12)
- 📜 [The differences between Object.freeze() vs Const in JavaScript — Bolaji Ayodeji](https://medium.com/@bolajiayodeji/the-differences-between-object-freeze-vs-const-in-javascript-4eacea534d7c)
- 📜 [Object to primitive conversion — JavaScript.info](https://javascript.info/object-toprimitive)

### Videos

- 🎥 [JavaScript Reference vs Primitive Types — Academind](https://www.youtube.com/watch?v=9ooYYRLdg_g)
- 🎥 [JavaScript Primitive Types — Simon Sez IT](https://www.youtube.com/watch?v=HsbWQsSCE5Y)
- 🎥 [Value Types and Reference Types in JavaScript — Programming with Mosh](https://www.youtube.com/watch?v=e-_mDyqm2oU)
- 🎥 [JavaScript Primitive Data Types — Avelx](https://www.youtube.com/watch?v=qw3j0A3DIzQ)
- 🎥 [Everything you never wanted to know about JavaScript numbers — Bartek Szopka](https://www.youtube.com/watch?v=MqHDDtVYJRI)
- 🎥 [What are variables in Javascript? — JS For Everyone](https://www.youtube.com/watch?v=B4Bbmei_thw)
- 🎥 [TIPOS DE DATOS PRIMITIVOS en JAVASCRIPT - La Cocina del Código](https://www.youtube.com/watch?v=cC65D2q5f8I)

**[⬆ Back to Top](#table-of-contents)**

---

## 3. Value Types and Reference Types

### Articles

- 📜 [Explaining Value vs. Reference in Javascript — Arnav Aggarwal](https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0)
- 📜 [Primitive Types & Reference Types in JavaScript — Bran van der Meer](https://gist.github.com/branneman/7fb06d8a74d7e6d4cbcf75c50fec599c)
- 📜 [Value Types, Reference Types and Scope in JavaScript — Ben Aston](https://medium.com/@benastontweet/lesson-1b-javascript-fundamentals-380f601ba851)
- 📜 [Back to roots: JavaScript Value vs Reference — Miro Koczka](https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18)
- 📜 [Grasp “By Value” and “By Reference” in JavaScript — Léna Faure](https://hackernoon.com/grasp-by-value-and-by-reference-in-javascript-7ed75efa1293)
- 📜 [JavaScript Reference and Copy Variables — Vítor Capretz](https://hackernoon.com/javascript-reference-and-copy-variables-b0103074fdf0)
- 📜 [JavaScript Primitive vs Reference Values](http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/)
- 📜 [JavaScript by Reference vs. by Value — nrabinowitz](https://stackoverflow.com/questions/6605640/javascript-by-reference-vs-by-value)
- 📜 [JavaScript Interview Prep: Primitive vs. Reference Types — Mike Cronin](https://dev.to/mostlyfocusedmike/javascript-interview-prep-primitive-vs-reference-types-3o4f)

### Videos

- 🎥 [Javascript Pass by Value vs Pass by Reference — techsith](https://www.youtube.com/watch?v=E-dAnFdq8k8)
- 🎥 [JavaScript Value vs Reference Types — Programming with Mosh](https://www.youtube.com/watch?v=fD0t_DKREbE)
- 🎥 [VALORES vs REFERENCIAS en JAVASCRIPT - La Cocina del Código](https://www.youtube.com/watch?v=AvkyOrWkuQc)

**[⬆ Back to Top](#table-of-contents)**

---

## 4. Implicit, Explicit, Nominal, Structuring and Duck Typing

### Articles

- 📜 [What you need to know about Javascript's Implicit Coercion — Promise Tochi](https://dev.to/promhize/what-you-need-to-know-about-javascripts-implicit-coercion-e23)
- 📜 [JavaScript Type Coercion Explained — Alexey Samoshkin](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839)
- 📜 [Javascript Coercion Explained — Ben Garrison](https://hackernoon.com/javascript-coercion-explained-545c895213d3)
- 📜 [What exactly is Type Coercion in Javascript? - Stack Overflow](https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript)

### Videos

- 🎥 [== ? === ??? ...#@^% - Shirmung Bielefeld](https://www.youtube.com/watch?v=qGyqzN0bjhc&t)
- 🎥 [Coercion in Javascript - Hitesh Choudhary](https://www.youtube.com/watch?v=b04Q_vyqEG8)
- 🎥 [JavaScript Questions: What is Coercion? - Steven Hancock](https://www.youtube.com/watch?v=z4-8wMSPJyI)
- 🎥 [Typing: Static vs Dynamic, Weak vs. Strong - Codexpanse](https://www.youtube.com/watch?v=C5fr0LZLMAs)
- 🎥 [EL SISTEMA de TIPOS DE JAVASCRIPT - La Cocina del Código](https://www.youtube.com/watch?v=0ei4nb49GKo)

### Books

- [You Don't Know JS, 1st Edition: Types & Grammar — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/tree/1st-ed)

**[⬆ Back to Top](#table-of-contents)**

---

## 5. == vs === vs typeof

### Articles

- 📜 [JavaScript Double Equals vs. Triple Equals — Brandon Morelli](https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a)
- 📜 [Should I use === or == equality comparison operator in JavaScript? — Panu Pitkamaki](https://bytearcher.com/articles/equality-comparison-operator-javascript/)
- 📜 [== vs === JavaScript: Double Equals and Coercion — AJ Meyghani](https://www.codementor.io/javascript/tutorial/double-equals-and-coercion-in-javascript)
- 📜 [Why Use the Triple-Equals Operator in JavaScript? — Louis Lazaris](https://www.impressivewebs.com/why-use-triple-equals-javascipt/)
- 📜 [What is the difference between == and === in JavaScript? — Craig Buckler](https://www.oreilly.com/learning/what-is-the-difference-between-and-in-javascript)
- 📜 [Why javascript's typeof always return "object"? — Stack Overflow](https://stackoverflow.com/questions/3787901/why-javascripts-typeof-always-return-object)
- 📜 [Checking Types in Javascript — Toby Ho](http://tobyho.com/2011/01/28/checking-types-in-javascript/)
- 📜 [How to better check data types in JavaScript — Webbjocke](https://webbjocke.com/javascript-check-data-types/)
- 📜 [Checking for the Absence of a Value in JavaScript — Tomer Aberbach](https://tomeraberba.ch/html/post/checking-for-the-absence-of-a-value-in-javascript.html)

### Videos

- 🎥 [JavaScript - The typeof operator — Java Brains](https://www.youtube.com/watch?v=ol_su88I3kw)
- 🎥 [Javascript typeof operator — DevDelight](https://www.youtube.com/watch?v=qPYhTPt_SbQ)

**[⬆ Back to Top](#table-of-contents)**

---

## 6. Function Scope, Block Scope and Lexical Scope

### Books

- [You Don't Know JS Yet, 2nd Edition: Scope & Closures — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/tree/2nd-ed/scope-closures)

### Articles

- 📜 [JavaScript Functions — Understanding The Basics — Brandon Morelli](https://codeburst.io/javascript-functions-understanding-the-basics-207dbf42ed99)
- 📜 [The battle between Function Scope and Block Scope — Marius Herring](http://www.deadcoderising.com/2017-04-11-es6-var-let-and-const-the-battle-between-function-scope-and-block-scope/)
- 📜 [Emulating Block Scope in JavaScript — Josh Clanton](http://adripofjavascript.com/blog/drips/emulating-block-scope-in-javascript.html)
- 📜 [The Difference Between Function and Block Scope in JavaScript — Joseph Cardillo](https://medium.com/@josephcardillo/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe)
- 📜 [Function Scopes and Block Scopes in JavaScript — Samer Buna](https://edgecoders.com/function-scopes-and-block-scopes-in-javascript-25bbd7f293d7)
- 📜 [Understanding Scope and Context in JavaScript — Ryan Morr](http://ryanmorr.com/understanding-scope-and-context-in-javascript/)
- 📜 [JavaScript Scope and Closures — Zell Liew](https://css-tricks.com/javascript-scope-closures/)
- 📜 [Understanding Scope in JavaScript — Wissam Abirached](https://developer.telerik.com/topics/web-development/understanding-scope-in-javascript/)
- 📜 [Speaking JavaScript - Variables: Scopes, Environments, and Closures — Dr. Axel Rauschmayer](http://speakingjs.com/es5/ch16.html)
- 📜 [Understanding Scope in JavaScript ― Hammad Ahmed](https://scotch.io/tutorials/understanding-scope-in-javascript)
- 📜 [When to use a function declaration vs. a function expression ― Amber Wilkie](https://medium.freecodecamp.org/when-to-use-a-function-declarations-vs-a-function-expression-70f15152a0a0)
- 📜 [A JavaScript Fundamentals Cheat Sheet: Scope, Context, and “this” ― Alexandra Fren](https://dev.to/alexandrafren/a-javascript-fundamentals-cheat-sheet-scope-context-and-this-28ai)
- 📜 [Functions / Function scope ― MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions#function_scope)

### Videos

- 🎥 [What Makes Javascript Weird ... and Awesome pt. 4 — LearnCode.academy](https://www.youtube.com/watch?v=SBwoFkRjZvE)
- 🎥 [Variable Scope in JavaScript — Kirupa Chinnathambi](https://www.youtube.com/watch?v=dhp57T3p760)
- 🎥 [JavaScript Block Scope and Function Scope — mmtuts](https://www.youtube.com/watch?v=aK_nuUAdr8E)
- 🎥 [What the Heck is Lexical Scope? — NWCalvank](https://www.youtube.com/watch?v=GhNA0r10MmA)
- 🎥 [Variable Scope — Steve Griffith](https://www.youtube.com/watch?v=FyWdrCZZavQ)

**[⬆ Back to Top](#table-of-contents)**

---

## 7. Expression vs Statement

### Articles

- 📜 [All you need to know about Javascript's Expressions, Statements and Expression Statements — Promise Tochi](https://dev.to/promhize/javascript-in-depth-all-you-need-to-know-about-expressions-statements-and-expression-statements-5k2)
- 📜 [Function Expressions vs Function Declarations — Paul Wilkins](https://www.sitepoint.com/function-expressions-vs-declarations/)
- 📜 [JavaScript Function — Declaration vs Expression — Ravi Roshan](https://medium.com/@raviroshan.talk/javascript-function-declaration-vs-expression-f5873b8c7b38)
- 📜 [Function Declarations vs. Function Expressions — Mandeep Singh](https://medium.com/@mandeep1012/function-declarations-vs-function-expressions-b43646042052)
- 📜 [Function Declarations vs. Function Expressions — Anguls Croll](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/)

### Videos

- 🎥 [Expressions vs. Statements in JavaScript — Hexlet](https://www.youtube.com/watch?v=WVyCrI1cHi8)
- 🎥 [JavaScript - Expression vs. Statement — WebTunings](https://www.youtube.com/watch?v=3jDpNGJkupA)

**[⬆ Back to Top](#table-of-contents)**

---

## 8. IIFE, Modules and Namespaces

### Articles

- 📜 [Mastering Immediately-Invoked Function Expressions ― Chandra Gundamaraju](https://medium.com/@vvkchandra/essential-javascript-mastering-immediately-invoked-function-expressions-67791338ddc6)
- 📜 [Do ES6 Modules make the case of IIFEs obsolete?](https://hashnode.com/post/do-es6-modules-make-the-case-of-iifes-obsolete-civ96wet80scqgc538un20es0)
- 📜 [A 10 minute primer to JavaScript modules, module formats, module loaders and module bundlers ― Jurgen Van de Moere](https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-and-module-bundlers/)
- 📜 [Modules ― Exploring JS](http://exploringjs.com/es6/ch_modules.html)
- 📜 [ES modules: A cartoon deep-dive — Lin Clark](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/)
- 📜 [Understanding ES6 Modules — Craig Buckler](https://www.sitepoint.com/understanding-es6-modules/)
- 📜 [An overview of ES6 Modules in JavaScript — Brent Graham](https://blog.cloud66.com/an-overview-of-es6-modules-in-javascript/)
- 📜 [ES6 Modules in Depth — Nicolás Bevacqua](https://ponyfoo.com/articles/es6-modules-in-depth)
- 📜 [ES6 modules, Node.js and the Michael Jackson Solution — Alberto Gimeno](https://medium.com/dailyjs/es6-modules-node-js-and-the-michael-jackson-solution-828dc244b8b)
- 📜 [JavaScript Modules: A Beginner’s Guide — Preethi Kasireddy](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)
- 📜 [Using JavaScript modules on the web — Addy Osmani & Mathias Bynens](https://developers.google.com/web/fundamentals/primers/modules)
- 📜 [IIFE: Immediately Invoked Function Expressions — Parwinder](https://dev.to/bhagatparwinder/iife-immediately-invoked-function-expressions-49c5)
- 📜 [Javascript Module Bundlers — Vanshu Hassija](https://sassy-butter-197.notion.site/Javascript-bundlers-016932b17b0744e983c2cc0db31e6f02)

### Videos

- 🎥 [Immediately Invoked Function Expression - Beau teaches JavaScript — freeCodeCamp](https://www.youtube.com/watch?v=3cbiZV4H22c)
- 🎥 [Understanding JavaScript IIFE — Sheo Narayan](https://www.youtube.com/watch?v=I5EntfMeIIQ)
- 🎥 [JavaScript Modules: ES6 Import and Export — Kyle Robinson](https://www.youtube.com/watch?v=_3oSWwapPKQ)
- 🎥 [ES6 - Modules — Ryan Christiani](https://www.youtube.com/watch?v=aQr2bV1BPyE)
- 🎥 [ES6 Modules in the Real World — Sam Thorogood](https://www.youtube.com/watch?v=fIP4pjAqCtQ)
- 🎥 [ES6 Modules — TempleCoding](https://www.youtube.com/watch?v=5P04OK6KlXA)
- 🎥 [JavaScript IIFE (Immediately Invoked Function Expressions) — Steve Griffith](https://www.youtube.com/watch?v=Xd7zgPFwVX8&)

**[⬆ Back to Top](#table-of-contents)**

---

## 9. Message Queue and Event Loop

### Articles

- 📜 [JavaScript Event Loop Explained — Anoop Raveendran](https://medium.com/front-end-hacking/javascript-event-loop-explained-4cd26af121d4)
- 📜 [The JavaScript Event Loop: Explained — Erin Sweson-Healey](https://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/)
- 📜 [Understanding JS: The Event Loop — Alexander Kondov](https://hackernoon.com/understanding-js-the-event-loop-959beae3ac40)
- 📜 [Understanding the JavaScript Event Loop — Ashish Gupta](https://www.zeolearn.com/magazine/understanding-the-javascript-event-loop)
- 📜 [The JavaScript Event Loop — Flavio Copes](https://flaviocopes.com/javascript-event-loop/)
- 📜 [How JavaScript works: Event loop — Alexander Zlatkov](https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5)
- 📜 [Tasks, microtasks, queues and schedules — Jake Archibald](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/)
- 📜 [Visualising the JavaScript Event Loop with a Pizza Restaurant analogy — Priyansh Jain](https://dev.to/presto412/visualising-the-javascript-event-loop-with-a-pizza-restaurant-analogy-47a8)
- 📜 [JavaScript Visualized: Event Loop — Lydia Hallie](https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif)

### Videos

- 🎥 [What the heck is the event loop anyway? | JSConf EU — Philip Roberts](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- 🎥 [JavaScript Event Loop — ComScience Simplified](https://www.youtube.com/watch?v=XzXIMZMN9k4)
- 🎥 [I'm stuck in an Event Loop — Philip Roberts](https://www.youtube.com/watch?v=6MXRNXXgP_0)
- 🎥 [In The Loop - Jake Archibald | JSConf.Asia 2018](https://www.youtube.com/watch?v=cCOL7MC4Pl0)
- 🎥 [Desmitificando el Event Loop (Spanish)](https://www.youtube.com/watch?v=Eqq2Rb7LzYE)

**[⬆ Back to Top](#table-of-contents)**

---

## 10. setTimeout, setInterval and requestAnimationFrame

### Articles

- 📜 [setTimeout and setInterval — JavaScript.Info](https://javascript.info/settimeout-setinterval)
- 📜 [Why not to use setInterval — Akanksha Sharma](https://dev.to/akanksha_9560/why-not-to-use-setinterval--2na9)
- 📜 [setTimeout VS setInterval — Develoger](https://develoger.com/settimeout-vs-setinterval-cff85142555b)
- 📜 [Using requestAnimationFrame — Chris Coyier](https://css-tricks.com/using-requestanimationframe/)
- 📜 [Understanding JavaScript's requestAnimationFrame() — JavaScript Kit](http://www.javascriptkit.com/javatutors/requestanimationframe.shtml)
- 📜 [Handling time intervals in JavaScript - Amit Merchant](https://www.amitmerchant.com/Handling-Time-Intervals-In-Javascript/)

### Videos

- 🎥 [Javascript: How setTimeout and setInterval works — Coding Blocks India](https://www.youtube.com/watch?v=6bPKyl8WYWI)
- 🎥 [setTimeout and setInterval in JavaScript — techsith](https://www.youtube.com/watch?v=TbCgGWe8LN8)
- 🎥 [JavaScript Timers — Steve Griffith](https://www.youtube.com/watch?v=0VVJSvlUgtg)
- 🎥 [JavaScript setTimeOut and setInterval Explained — Theodore Anderson](https://www.youtube.com/watch?v=mVKfrWCOB60)

**[⬆ Back to Top](#table-of-contents)**

---

## 11. JavaScript Engines

### Articles

- 📜 [JavaScript Engines — Jen Looper](http://www.softwaremag.com/javascript-engines/)
- 📜 [Understanding How the Chrome V8 Engine Translates JavaScript into Machine Code — DroidHead](https://medium.freecodecamp.org/understanding-the-core-of-nodejs-the-powerful-chrome-v8-engine-79e7eb8af964)
- 📜 [Understanding V8’s Bytecode — Franziska Hinkelmann](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775)
- 📜 [A Brief History of Google’s V8 Javascript Engine — Clair Smith](https://www.mediacurrent.com/blog/brief-history-googles-v8-javascript-engine/)
- 📜 [JavaScript essentials: why you should know how the engine works - Rainer Hahnekamp](https://medium.freecodecamp.org/javascript-essentials-why-you-should-know-how-the-engine-works-c2cc0d321553)
- 📜 [JavaScript engine fundamentals: Shapes and Inline Caches](https://mathiasbynens.be/notes/shapes-ics)
- 📜 [JavaScript engine fundamentals: optimizing prototypes](https://mathiasbynens.be/notes/prototypes)
- 📜 [How V8 optimizes array operations](https://v8.dev/blog/elements-kinds)

### Videos

- 🎥 [JavaScript Engines: The Good Parts™ — Mathias Bynens & Benedikt Meurer](https://www.youtube.com/watch?v=5nmpokoRaZI)
- 🎥 [JS Engine EXPOSED 🔥 Google's V8 Architecture 🚀 | Namaste JavaScript Ep. 16 - Akshay Saini](https://www.youtube.com/watch?v=2WJL19wDH68)

**[⬆ Back to Top](#table-of-contents)**

---

## 12. Bitwise Operators, Type Arrays and Array Buffers

### Articles

- 📜 [Programming with JS: Bitwise Operations — Alexander Kondov](https://hackernoon.com/programming-with-js-bitwise-operations-393eb0745dc4)
- 📜 [Using JavaScript’s Bitwise Operators in Real Life — ian m](https://codeburst.io/using-javascript-bitwise-operators-in-real-life-f551a731ff5)
- 📜 [JavaScript Bitwise Operators — w3resource](https://www.w3resource.com/javascript/operators/bitwise-operator.php)
- 📜 [Bitwise Operators in Javascript — Joe Cha](https://medium.com/bother7-blog/bitwise-operators-in-javascript-65c4c69be0d3)
- 📜 [A Comprehensive Primer on Binary Computation and Bitwise Operators in Javascript — Paul Brown](https://medium.com/techtrument/a-comprehensive-primer-on-binary-computation-and-bitwise-operators-in-javascript-81acf8341f04)
- 📜 [How can I understand Bitwise operation in JavaScript?](https://www.quora.com/How-can-I-understand-Bitwise-operation-in-JavaScript)

### Videos

- 🎥 [JavaScript Bitwise Operators — Programming with Mosh](https://www.youtube.com/watch?v=mesu75PTDC8)

**[⬆ Back to Top](#table-of-contents)**

---

## 13. DOM and Layout Trees

### Books

- 📜 [Eloquent JavaScript, 3rd Edition: Ch. 14 - The Document Object Model](https://eloquentjavascript.net/14_dom.html)

### Articles

- 📜 [How To Understand and Modify the DOM in JavaScript — Tania Rascia](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom)
- 📜 [What’s the Document Object Model, and why you should know how to use it — Leonardo Maldonado](https://medium.freecodecamp.org/whats-the-document-object-model-and-why-you-should-know-how-to-use-it-1a2d0bc5429d)
- 📜 [JavaScript DOM Tutorial with Example — Guru99](https://www.guru99.com/how-to-use-dom-and-events-in-javascript.html)
- 📜 [What is the DOM? — Chris Coyier](https://css-tricks.com/dom/)
- 📜 [Traversing the DOM with JavaScript — Zell Liew](https://zellwk.com/blog/dom-traversals/)
- 📜 [DOM Tree](https://javascript.info/dom-nodes)
- 📜 [How to traverse the DOM in Javascript — Vojislav Grujić](https://medium.com/javascript-in-plain-english/how-to-traverse-the-dom-in-javascript-d6555c335b4e)
- 📜 [Render Tree Construction — Ilya Grigorik](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction)
- 📜 [What exactly is the DOM?](https://bitsofco.de/what-exactly-is-the-dom/)

### Videos

- 🎥 [JavaScript DOM — The Net Ninja](https://www.youtube.com/watch?v=FIORjGvT0kk)
- 🎥 [JavaScript DOM Crash Course — Traversy Media](https://www.youtube.com/watch?v=0ik6X4DJKCc)

**[⬆ Back to Top](#table-of-contents)**

---

## 14. Factories and Classes

### Articles

- 📜 [How To Use Classes in JavaScript — Tania Rascia](https://www.digitalocean.com/community/tutorials/understanding-classes-in-javascript)
- 📜 [Javascript Classes — Under The Hood — Majid](https://medium.com/tech-tajawal/javascript-classes-under-the-hood-6b26d2667677)
- 📜 [ES6 Classes — Nathaniel Foster](https://www.javascriptjanuary.com/blog/es6-classes)
- 📜 [Better JavaScript with ES6, Pt. II: A Deep Dive into Classes ― Peleke Sengstacke](https://scotch.io/tutorials/better-javascript-with-es6-pt-ii-a-deep-dive-into-classes)
- 📜 [Understand the Factory Design Pattern in Plain JavaScript — Aditya Agarwal](https://medium.com/front-end-hacking/understand-the-factory-design-pattern-in-plain-javascript-20b348c832bd)
- 📜 [Factory Functions in JavaScript — Josh Miller](https://atendesigngroup.com/blog/factory-functions-javascript)
- 📜 [The Factory Pattern in JS ES6 — SnstsDev](https://medium.com/@SntsDev/the-factory-pattern-in-js-es6-78f0afad17e9)
- 📜 [Class vs Factory function: exploring the way forward — Cristi Salcescu](https://medium.freecodecamp.org/class-vs-factory-function-exploring-the-way-forward-73258b6a8d15)
- 📜 [How ES6 classes really work and how to build your own — Robert Grosse](https://medium.com/@robertgrosse/how-es6-classes-really-work-and-how-to-build-your-own-fd6085eb326a)
- 📜 [Understanding `super` in JavaScript](https://jordankasper.com/understanding-super-in-javascript)
- 📜 [An Easy Guide To Understanding Classes In JavaScript](https://dev.to/lawrence_eagles/an-easy-guide-to-understanding-classes-in-javascript-3bcm)

### Videos

- 🎥 [JavaScript Factory Functions — Programming with Mosh](https://www.youtube.com/watch?v=jpegXpQpb3o)
- 🎥 [Factory Functions in JavaScript — Fun Fun Function](https://www.youtube.com/watch?v=ImwrezYhw4w)
- 🎥 [Javascript Tutorial Function Factories — Crypto Chan](https://www.youtube.com/watch?v=R7-IwpH80UE)

**[⬆ Back to Top](#table-of-contents)**

---

## 15. this, call, apply and bind

### Reference

- 📜 [call() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call)
- 📜 [bind() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_objects/Function/bind)
- 📜 [apply() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply)

### Articles

- 📜 [Grokking call(), apply() and bind() methods in JavaScript — Aniket Kudale](https://levelup.gitconnected.com/grokking-call-apply-and-bind-methods-in-javascript-392351a4be8b)
- 📜 [How-to: call() , apply() and bind() in JavaScript — Niladri Sekhar Dutta](https://www.codementor.io/niladrisekhardutta/how-to-call-apply-and-bind-in-javascript-8i1jca6jp)
- 📜 [JavaScript’s Apply, Call, and Bind Methods are Essential for JavaScript Professionals — Richard Bovell](http://javascriptissexy.com/javascript-apply-call-and-bind-methods-are-essential-for-javascript-professionals/)
- 📜 [WTF is this - Understanding the this keyword, call, apply, and bind in JavaScript — Tyler McGinnis](https://tylermcginnis.com/this-keyword-call-apply-bind-javascript/)
- 📜 [Javascript: call(), apply() and bind() — Omer Goldberg](https://medium.com/@omergoldberg/javascript-call-apply-and-bind-e5c27301f7bb)
- 📜 [The difference between call / apply / bind — Ivan Sifrim](https://medium.com/@ivansifrim/the-differences-between-call-apply-bind-276724bb825b)
- 📜 [What the hack is call, apply, bind in JavaScript — Ritik](https://dev.to/ritik_dev_js/what-the-hack-is-call-apply-bind-in-javascript-11ce)
- 📜 [Mastering 'this' in JavaScript: Callbacks and bind(), apply(), call() — Michelle Gienow](https://thenewstack.io/mastering-javascript-callbacks-bind-apply-call/)
- 📜 [JavaScript’s apply, call, and bind explained by hosting a cookout — Kevin Kononenko](https://dev.to/kbk0125/javascripts-apply-call-and-bind-explained-by-hosting-a-cookout-32jo)
- 📜 [How AND When to use bind, call, and apply in Javascript — Eigen X](https://www.eigenx.com/blog/https/mediumcom/eigen-x/how-and-when-to-use-bind-call-and-apply-in-javascript-77b6f42898fb)
- 📜 [Let me explain to you what is `this`. (Javascript) — Jason Yu](https://dev.to/ycmjason/let-me-explain-to-you-what-is-this-javascript-44ja)
- 📜 [Understanding the “this” Keyword in JavaScript — Pavan](https://medium.com/quick-code/understanding-the-this-keyword-in-javascript-cb76d4c7c5e8)
- 📜 [How to understand the keyword this and context in JavaScript — Lukas Gisder-Dubé](https://medium.freecodecamp.org/how-to-understand-the-keyword-this-and-context-in-javascript-cd624c6b74b8)
- 📜 [What the heck is this in Javascript? — Hridayesh Sharma](https://dev.to/_hridaysharma/what-the-heck-is-this-in-javascript-37n1)
- 📜 [This and Bind In Javascript — Brian Barbour](https://dev.to/steelvoltage/this-and-bind-in-javascript-2pam)
- 📜 [3 Techniques for Maintaining Your Sanity Using "This" in JavaScript — Carl](https://dev.to/canderson93/3-techniques-for-maintaining-your-sanity-using-this-in-javascript-3idf)
- 📜 [Mastering the JavaScript "this" Keyword — Aakash Srivastav](https://dev.to/aakashsr/mastering-the-javascript-this-keyword-4pfa)
- 📜 [This binding in JavaScript – 4. New binding — Spyros Argalias](https://dev.to/sargalias/this-binding-in-javascript-4-new-binding-2p1n)
- 📜 [A quick intro to 'this' in JavaScript — Natalie Smith](https://dev.to/thatgalnatalie/a-quick-intro-to-this-in-javascript-2mhp)
- 📜 [Explaining JavaScript 'this' to my cat — Andrey K](https://dev.to/cat__logic/explaining-javascript-this-to-my-cat-1kig)
- 📜 [A conversation with the 'this' keyword in Javascript — Karen Efereyan](https://dev.to/developerkaren/a-conversation-with-the-this-keyword-in-javascript-3j6g)
- 📜 [What are call(), apply() and bind() in JavaScript — Amitav Mishra](https://jscurious.com/what-are-call-apply-and-bind-in-javascript/)
- 📜 [Understanding 'this' binding in JavaScript — Yasemin Cidem](https://yasemincidem.medium.com/understanding-this-binding-in-javascript-86687397c76d)

### Videos

- 🎥 [JavaScript call, apply and bind — techsith](https://www.youtube.com/watch?v=c0mLRpw-9rI)
- 🎥 [JavaScript Practical Applications of Call, Apply and Bind functions— techsith](https://www.youtube.com/watch?v=AYVYxezrMWA)
- 🎥 [JavaScript (call, bind, apply) — curious aatma](https://www.youtube.com/watch?v=Uy0NOXLBraE)
- 🎥 [Understanding Functions and 'this' In The World of ES2017 — Bryan Hughes](https://www.youtube.com/watch?v=AOSYY1_np_4)
- 🎥 [bind and this - Object Creation in JavaScript - FunFunFunction](https://www.youtube.com/watch?v=GhbhD1HR5vk)
- 🎥 [JS Function Methods call(), apply(), and bind() — Steve Griffith](https://www.youtube.com/watch?v=uBdH0iB1VDM)

**[⬆ Back to Top](#table-of-contents)**

---

## 16. new, Constructor, instanceof and Instances

### Articles

- 📜 [JavaScript For Beginners: the ‘new’ operator — Brandon Morelli](https://codeburst.io/javascript-for-beginners-the-new-operator-cee35beb669e)
- 📜 [Let’s demystify JavaScript’s ‘new’ keyword — Cynthia Lee](https://medium.freecodecamp.org/demystifying-javascripts-new-keyword-874df126184c)
- 📜 [Constructor, operator "new" — JavaScript.Info](https://javascript.info/constructor-new)
- 📜 [Understanding JavaScript Constructors — Faraz Kelhini](https://css-tricks.com/understanding-javascript-constructors/)
- 📜 [Use Constructor Functions — Openclassrooms](https://openclassrooms.com/en/courses/3523231-learn-to-code-with-javascript/4379006-use-constructor-functions)
- 📜 [Beyond `typeof` and `instanceof`: simplifying dynamic type checks — Dr. Axel Rauschmayer](http://2ality.com/2017/08/type-right.html)
- 📜 [What Is the Instanceof Operator in JavaScript — appendTo](https://appendto.com/2016/10/what-is-the-instanceof-operator-in-javascript/)
- 📜 [Function and Object, instances of each other — Kiro Risk](https://javascriptrefined.io/function-and-object-instances-of-each-other-1e1095d5faac)

**[⬆ Back to Top](#table-of-contents)**

---

## 17. Prototype Inheritance and Prototype Chain

### Reference

- 📜 [Inheritance and the prototype chain — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)

### Articles

- 📜 [Javascript : Prototype vs Class — Valentin PARSY](https://medium.com/@parsyval/javascript-prototype-vs-class-a7015d5473b)
- 📜 [JavaScript engine fundamentals: optimizing prototypes — Mathias Bynens](https://mathiasbynens.be/notes/prototypes)
- 📜 [JavaScript Prototype — NC Patro](https://codeburst.io/javascript-prototype-cb29d82b8809)
- 📜 [Prototype in Javascript — Sandeep Ranjan](https://www.codementor.io/sandeepranjan2007/prototype-in-javascipt-knbve0lqo)
- 📜 [Prototypes in JavaScript — Rupesh Mishra](https://hackernoon.com/prototypes-in-javascript-5bba2990e04b)
- 📜 [Prototype in JavaScript: it’s quirky, but here’s how it works — Pranav Jindal](https://medium.freecodecamp.org/prototype-in-js-busted-5547ec68872)
- 📜 [Understanding JavaScript: Prototype and Inheritance — Alexander Kondov](https://hackernoon.com/understanding-javascript-prototype-and-inheritance-d55a9a23bde2)
- 📜 [Understanding Classes (ES5) and Prototypal Inheritance in JavaScript — Hridayesh Sharma](https://dev.to/_hridaysharma/understanding-classes-es5-and-prototypal-inheritance-in-javascript-n8d)
- 📜 [prototype, **proto** and Prototypal inheritance in JavaScript — Varun Dey](https://dev.to/varundey/prototype-proto-and-prototypal-inheritance-in-javascript-2inl)
- 📜 [Prototypal Inheritance — JavaScript.Info](https://javascript.info/prototype-inheritance)
- 📜 [How To Work with Prototypes and Inheritance in JavaScript — Tania Rascia](https://www.digitalocean.com/community/tutorials/understanding-prototypes-and-inheritance-in-javascript)
- 📜 [Master JavaScript Prototypes & Inheritance — Arnav Aggarwal](https://codeburst.io/master-javascript-prototypes-inheritance-d0a9a5a75c4e)
- 📜 [JavaScript’s Prototypal Inheritance Explained Using CSS — Nash Vail](https://medium.freecodecamp.org/understanding-prototypal-inheritance-in-javascript-with-css-93b2fcda75e4)
- 📜 [Prototypal Inheritance in JavaScript — Jannis Redmann](https://gist.github.com/derhuerst/a585c4916b1c361cc6f0)
- 📜 [Demystifying ES6 Classes And Prototypal Inheritance ― Neo Ighodaro](https://scotch.io/tutorials/demystifying-es6-classes-and-prototypal-inheritance)
- 📜 [Intro To Prototypal Inheritance — Dharani Jayakanthan](https://dev.to/danny/intro-to-prototypal-inheritance---js-9di)
- 📜 [Let’s Build Prototypal Inheritance in JS — var-che](https://dev.to/varche/let-s-build-prototypal-inheritance-in-js-56mm)
- 📜 [Objects, Prototypes and Classes in JavaScript — Atta](https://dev.to/attacomsian/objects-prototypes-and-classes-in-javascript-3i9b)
- 📜 [The magical world of JavaScript prototypes — Belén](https://dev.to/ladybenko/the-magical-world-of-javascript-prototypes-1mhg)
- 📜 [Understanding Prototypal Inheritance In JavaScript — Lawrence Eagles](https://dev.to/lawrence_eagles/understanding-prototypal-inheritance-in-javascript-4f31#chp-4)
- 📜 [Objects and Prototypes in JavaScript — Irena Popova](https://dev.to/irenejpopova/objects-and-prototypes-in-javascript-2eie)

### Videos

- 🎥 [Javascript Prototype Inheritance — Avelx](https://www.youtube.com/watch?v=sOrtAjyk4lQ)
- 🎥 [JavaScript Prototype Inheritance Explained pt. I — techsith](https://www.youtube.com/watch?v=7oNWNlMrkpc)
- 🎥 [JavaScript Prototype Inheritance Explained pt. II — techsith](https://www.youtube.com/watch?v=uIlj6_z_wL8)
- 🎥 [JavaScript Prototype Inheritance Explained — Kyle Robinson](https://www.youtube.com/watch?v=qMO-LTOrJaE)
- 🎥 [Advanced Javascript - Prototypal Inheritance In 1 Minute](https://www.youtube.com/watch?v=G6l5CHl67HQ)
- 🎥 [An Overview Of Classical Javascript Classes and Prototypal Inheritance — Pentacode](https://www.youtube.com/watch?v=phwzuiJJPpQ)
- 🎥 [Object Oriented JavaScript - Prototype — The Net Ninja](https://www.youtube.com/watch?v=4jb4AYEyhRc)
- 🎥 [Prototype in JavaScript — kudvenkat](https://www.youtube.com/watch?v=2rkEbcptR64)
- 🎥 [JavaScript Using Prototypes — O'Reilly](https://www.youtube.com/watch?v=oCwCcNvaXAQ)
- 🎥 [A Beginner's Guide to Javascript's Prototype — Tyler Mcginnis](https://www.youtube.com/watch?v=XskMWBXNbp0)
- 🎥 [Prototypes in Javascript - p5.js Tutorial — The Coding Train](https://www.youtube.com/watch?v=hS_WqkyUah8)

### Books

- [You Don't Know JS, 1st Edition: this & Object Prototypes — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/tree/1st-ed)

**[⬆ Back to Top](#table-of-contents)**

---

## 18. Object.create and Object.assign

### Reference

- 📜 [Object.create() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create)
- 📜 [Object.assign() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)

### Articles

- 📜 [Object.create in JavaScript — Rupesh Mishra](https://medium.com/@happymishra66/object-create-in-javascript-fa8674df6ed2)
- 📜 [Object.create(): the New Way to Create Objects in JavaScript — Rob Gravelle](https://www.htmlgoodies.com/beyond/javascript/object.create-the-new-way-to-create-objects-in-javascript.html)
- 📜 [Basic Inheritance with Object.create — Joshua Clanton](http://adripofjavascript.com/blog/drips/basic-inheritance-with-object-create.html)
- 📜 [Object.create() In JavaScript — GeeksforGeeks](https://www.geeksforgeeks.org/object-create-javascript/)
- 📜 [Understanding the difference between Object.create() and the new operator — Jonathan Voxland](https://medium.com/@jonathanvox01/understanding-the-difference-between-object-create-and-the-new-operator-b2a2f4749358)
- 📜 [JavaScript Object Creation: Patterns and Best Practices — Jeff Mott](https://www.sitepoint.com/javascript-object-creation-patterns-best-practises/)
- 📜 [Dealing With Objects in JavaScript With Object.assign, Object.keys and hasOwnProperty](https://alligator.io/js/dealing-with-objects/)
- 📜 [Copying Objects in JavaScript ― Orinami Olatunji](https://scotch.io/bar-talk/copying-objects-in-javascript)
- 📜 [JavaScript: Object.assign() — Thiago S. Adriano](https://codeburst.io/javascript-object-assign-bc9696dcbb6e)
- 📜 [How to deep clone a JavaScript Object — Flavio Copes](https://flaviocopes.com/how-to-clone-javascript-object/)
- 📜 [Object.create(): When and Why to Use — VZing](https://dev.to/vzing/object-create-when-and-why-to-use-20m9)

### Videos

- 🎥 [Object.assign() explained — Aaron Writes Code](https://www.youtube.com/watch?v=aw7NfYhR5rc)
- 🎥 [Object.assign() Method — techsith](https://www.youtube.com/watch?v=9Ky4X6inpi4)

**[⬆ Back to Top](#table-of-contents)**