### Evaluator: Robbie
### Students: Jeannie
### Comments:

* The "Correct Answers" was pretty confusing at first - thought it was showing me the correct answers I got, but there were too many flags sometimes
* Really like the simple UI
* Would be awesome to know _which_ flags I got incorrect so I can review them more
* Some compilation warnings in terminal when app is started
* Confused by the default region when you do not select a region and play the game

* 42 passed, 3 skipped - any questions about these tests?

* In `App`, `<div className="region-img-p">` and code in `handleRegion` could be refactored to make this iterable, so you don't have to everything by hand
* Some refactoring opportunities in some methods, namely `filterCountries` in `ChooseRegion` component
* `handleGuess` in `GameContainer` could use some refactoring due to repeated logic in if/else
* Could some things in `GameContainer` belong in redux, or was there a reason to keep it in local state?

## Rubric 

### Specification Adherence

* 3 - The application completes all iterations above without error. Evaluator has minimal recommendations for design changes.

### Project Professionalism

* 3 - The codebase has less than 5 linter errors and README has been updated with all group members. Project utilized wireframes from the outset and updated them as changes were made. A project management tool was continuously used from the beginning of the project.  All git commits are atomic, made first to branches, and use descriptive and consise commit messages. 

### React Architecture

* 3 - React architecture is clean and organized.  Logic is kept out of return statements.  There are some issues with the asynchronous js where the frontend is not matching with the backend.  There are multiple functions (including fetch calls) that are doing similar pieces of functionality that could continue to be refactored. Data fetched from API is not cleaned before being set to state.

### Redux Architecture

* 2 - At least one component is not connected with Redux appropriately. Application state is mutated by more than just Redux. The Redux store is missing application data that it should be handling.
* 3 - Appropriate components are wrapped in connected Redux container components. The Redux store contains all necessary application data. All state changes are handled through Redux actions and reducers.
  store. Data in the store remains flat (not nested).

### Testing

* 3 - All Redux functionality is tested (actions, reducers, mapStateToProps, mapDispatchToProps), all components are unit tested, and a valid attempt was made to test any async functionality.

### Routing

* 3 - Application uses React Router to display appropriate components based on URL.  UX is clear and set up well so that user has access to previous routes.
