<h1 align="center">Predictable Web Apps with Angular and Redux</h1>

Speaker: [Giorgio Natili](https://twitter.com/giorgionatili)

**Using AngularJS within Angular**
- Module built with different Angular versions should work in the same app
- The routing system should be aware of which routes it should take care of
- Existing components should work

Five Things You **Should** Do
- Design the application state before starting to code
- Build independent and self-contained odules using fractal stores
- Implement action creators to don't repeat yourself
- Use filters and selectors to listen to changes of specific slices
- Remove as much as possible the logic from the components

Five Things You **Shouldn't** Do
- Store in the application state redundant information (loading states)
- Pollute and make the DSL ambiguous with not needed actions
- Use Redux as an event bus system
- Apply optomistic changes when interacting with external API
- Create complex reducers instead of splitting the state