### Evaluator: Robbie
### Students: Eric
### Comments:

* I don't think it's necessary to give examples for first and last names in the form input, but you do have the room for it
* Searched for Michael Jordan, and a card came up with a zero to the right of the card, what's going on here?
*** Viewing stats for `http://localhost:3000/player/2931` (Michael Jordan) causes the app to crash...**
* After viewing stats, no easy way to get back home without using back button
* Not seeing anything for "Compare Players" - pretty unclear how that works that you need to "Search" for two players
* Cool visualization for player stats - would be nice to have different colors for different players - not sure if line charts are totally applicable in this case since it's not continuous data
* Is there a way to view different stats?

* 30 tests passing - some proptype failures (check how you are mocking components in the tests)

* Good job leaving the `<NavBar />` outside of the routes since this is shown on every page
* How did you like using the `react-chartjs-2` library?
* Why use the `for` loop in the `Chart` component?

## Rubric 

### Specification Adherence

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
