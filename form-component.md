# Form component

## Story
I used to work in a company where almost part of the web component is standardized. If you want a textbox, you will be using the framework text box. If I just want to tweak the text box a bit, I will need go through the system team for permission. Now in another company where I got a opportunity to start a website from scratch. I found myself standizing the form components. Why you ask?

### Benefits of components
+ reduce code repetition
+ easy to maintain *(only if you pair with unit/integration test, else any changes in the component will be a high risk change)*
+ separation of concern

## Component
I was taught for React there are 2 types of component: *container* and *dummy* component. Dummy means a component that holds no/minimun logic (eg: header/side bar). Container integrates all the dummy component, in-charge on how a page works in general. I apply this concept in Angular component as well, so far so good.

## Reactive Model Form vs Template Driven Form
There are 2 ways to create forms: reactive model or template driven. At first I prefer template driven form because it uses less code and you can code almost everything in the html alone. However when it comes to customizing the forms or sharing validation script, template driven form become less flexible. I also find that template driven form does not give consistent result in the unit test and integration test. It could just pass or fail depend on mood. That drive me mad and I re-code all my work from template driven form to reactive model form and never looked back since. There is only one scenario that template driven model is useful, I will write about it later.




