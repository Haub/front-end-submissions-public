### Evaluator: Robbie
### Students: Eduardo
### Comments:

* Some compilation warnings in the terminal when running `npm start`
* The loading screen is cool - very fitting for the app
* Nice to have an instructions page - could you alter the main page to give the user an idea of the flow they should take instead of having to write it out? There is some of that with the sorting hat being at the top, but I think you can make it clearer
* Can't see if something is selected in the sorting hat form, which is pretty confusing
* The theme change once the house is selected is really cool!
* I got "Foolish Wand Waving" on the quiz...

*** Not seeing the list of characters on the Characters page, same with spells**

* 58 tests passing, a few skipped or failing - questions about these?

* In the `App` `closeModal` method, there is some DOM selection happening using `document.querySelector`...you should not need to use `document` (almost ever) in React, find a way to put this logic in the component (maybe inlining the style) - let React control the DOM - we don't want to control the DOM using query selectors
* Good routing overall - curious about the use of `<Redirect to='/' />` in `App`
* What is the need for the `setTimeout` in the `Game` component?

## Rubric 

### Specification Adherence

* 2 - The application is in a usable state, but is missing part of one or more of the features outlined above. There are one or more major bugs and the evaluator has multiple recommendations for design changes.
* 3 - The application completes all iterations above without error. Evaluator has minimal recommendations for design changes.

### Project Professionalism

* 3 - The codebase has less than 5 linter errors and README has been updated with all group members. Project utilized wireframes from the outset and updated them as changes were made. A project management tool was continuously used from the beginning of the project.  All git commits are atomic, made first to branches, and use descriptive and consise commit messages. 

### React Architecture

* 3 - React architecture is clean and organized.  Logic is kept out of return statements.  There are some issues with the asynchronous js where the frontend is not matching with the backend.  There are multiple functions (including fetch calls) that are doing similar pieces of functionality that could continue to be refactored. Data fetched from API is not cleaned before being set to state.

### Redux Architecture

* 3 - Appropriate components are wrapped in connected Redux container components. The Redux store contains all necessary application data. All state changes are handled through Redux actions and reducers.

### Testing

* 3 - All Redux functionality is tested (actions, reducers, mapStateToProps, mapDispatchToProps), all components are unit tested, and a valid attempt was made to test any async functionality.

### Routing

* 3 - Application uses React Router to display appropriate components based on URL.  UX is clear and set up well so that user has access to previous routes.
