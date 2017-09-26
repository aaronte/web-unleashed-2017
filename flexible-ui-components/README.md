<h1 align="center">Flexible UI Components for a Multi-Framework World</h1>

Speaker: [Kevin Ball](https://twitter.com/kbal11)

Website: https://zendev.com

Implementing UI is easier its ever been

Environments have
* Different DOM manipulation paradigms
* Different atural markup structure
* Different managing states

Zurb Foundation 7 Design Goals
- Design Language Agnostic
- JS Framework Agnostic
- Flexible UI Components

Flexible UI Components
* Components designed to be adapted to any JS framework


Principles of Flexible UI Components
* Components should be State Driven
* Coupling Should be Event Driven
* Should be "DOM Flexible"

State Driven - Imperative Manipulation is like telling your kids what to do
* Go to your room
* Pick out one shirt
* Pick out one pair of shoe

* Native JavaScript
* JQuery
* Polymer/Web Components

```js
element.setStyle({});
element.setClass({});
```

State Driven manipulation is like me taking my car to the shop
* Make this car awesome

```js
component.setState({ selected: true });
```

state => imperative is easy

imperative => state is hard

Everything as State
- APplication State
- UI State
- User entered content
- Aria labels

Coupling Should be Event Driven
* Loose Coupling > Tight Coupling

Multiple Models of State
- Redux: event === dispatch
- RxJS: Component => Observables

**Components Should Be "Dom Flexible"**

What does it mean?
- Explicit over Implicit
- Classes and Attributes over Elements
    - Finer control
    - Allow More Variation
    - More Verbose

Lets Review
- Components Should Be State Driven
- Coupling SHould be Event Driven
- Components Should be "DOM Flexible"

Old Model of Component Libraries
- Components should Make Us Build Easier

New Model of Component Libraries
- Put User Experience First
- Enable Shared Language Between Design & Development
- Enable Consistency Across All Brand Faces


How Do We Get There?
- Recognize UI/UX as a primary concern
- Advocate against JS framework elitism
- UI frameworks need more JS experts involved
- JS frameworks need more designers involved

https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/
