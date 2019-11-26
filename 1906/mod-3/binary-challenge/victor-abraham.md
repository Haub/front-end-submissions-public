### Evaluator: Robbie
### Students: Victor
### Comments:

* Cool card cards! I think the red is pretty bold and maybe taking away from the card graphics - you want these to stand out since they are like artwork and identify the card to users
* Nice loading spinner
* Some filters not loading cards, Set is not working
* Would be cool to combine filters (type and rarity)
* Some compilation warnings happening in the terminal for `npm start`
* Need to do something if the `response.ok` is false in apicalls

* 31 tests passing - some proptype failures

* Mixing up containers and components - the distinguishing factor is if it is connected to the store or not
* The card info route is good - would like to see a dynamic route used here (this might make your generate card URL logic easier in the long run)
* Interesting to give the `FilterBar` the `apiCalls` responsibility - talk about that choice

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

* 2 - Nearly all unit tests are in place. React components are well tested with a diverse set of tests including but not limited to snapshot tests, event simulation tests, and tests on class methods.  All routes have been tested as well including dynamic routes.  There are tests in place for actions, reducers, mapStateToProps, and mapDispatchToProps.  No attempt to test async functionality was made.
* 3 - All Redux functionality is tested (actions, reducers, mapStateToProps, mapDispatchToProps), all components are unit tested, and a valid attempt was made to test any async functionality.

### Routing

* 3 - Application uses React Router to display appropriate components based on URL.  UX is clear and set up well so that user has access to previous routes.
