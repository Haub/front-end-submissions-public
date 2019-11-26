### Evaluator: Robbie
### Students: Edwin
### Comments:

* The loading animation is cool, but seeing it on a lot of cards is very distracting - maybe something more subtle for the image placeholder and a single loacing progress bar...
* Cool audio preview for shows! Seeing a small bug where once one is selected and played you cannot select a new one
* Favorites is working well! In this case, not sure an on/off style switch is what a user would expect, this is like turing on/off a feature, not switching to another view

* 63 tests!

* Good job putting `<Nav />` not in a route component since it's rendering on every page
* `componentDidMount` in `ArtworkModal` is a good place to refactor a bit
* In `SearchForm`, why have `const data = await getData(term, type);` outside the try/catch?

## Rubric 

### Specification Adherence

* 4 - The application completes all iterations above and implements one or more of the extensions.  The evaluator has no recommendations for design changes.

### Project Professionalism

* 3 - The codebase has less than 5 linter errors and README has been updated with all group members. Project utilized wireframes from the outset and updated them as changes were made. A project management tool was continuously used from the beginning of the project.  All git commits are atomic, made first to branches, and use descriptive and consise commit messages. 

### React Architecture

* 3 - React architecture is clean and organized.  Logic is kept out of return statements.  There are some issues with the asynchronous js where the frontend is not matching with the backend.  There are multiple functions (including fetch calls) that are doing similar pieces of functionality that could continue to be refactored. Data fetched from API is not cleaned before being set to state.

### Redux Architecture

* 3 - Appropriate components are wrapped in connected Redux container components. The Redux store contains all necessary application data. All state changes are handled through Redux actions and reducers.

### Testing

* 3 - All Redux functionality is tested (actions, reducers, mapStateToProps, mapDispatchToProps), all components are unit tested, and a valid attempt was made to test any async functionality.
* 4 - All async functionality is tested.   Asynchronous tests cover happy paths as well as multiple sad paths.  All pieces of functionality have been tested and are passing and run efficiently (using mount only when appropriate). Evaluator has no recommendations for testing.

### Routing

* 3 - Application uses React Router to display appropriate components based on URL.  UX is clear and set up well so that user has access to previous routes.
* 4 - React Router components have been refactored for developer empathy and code quality is clean.  Application accounts for undefined routes. UX is excellent and set up well to have links to all routes on all pages.