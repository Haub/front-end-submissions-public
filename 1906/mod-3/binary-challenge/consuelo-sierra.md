### Evaluator: Robbie
### Students: Consuelo
### Comments:

***App crashes when incorrect spell name is put into the search bar**
* Some compilation warnings in terminal when app is started
* The All Spells button is nice for getting back to seeing all spells
* On the Favorites page, the spell favorite ocon has an unfavorited state, which is confusing when clicked
* Would really like to see some way to filter the spells because I have no idea what the spell names are (maybe filter by spell/charm/what it can do)

* 49 passed - a few skipped - what questions do you have about these?

* You do not need "exact" on all Routes in the `App` component - play around with removing exact to figure out when you need it
* Look into refactoring your `bindActionCreators` functions so that you just pass in the action function reference instead of defining a whole new function again
* Naming for actions is good, but a couple of them need rewording to be a verb, have some action
* Why nest the `<h2 className='fav-link'>Favourite Spells</h2>` in the `<NavLink to='/favourites'>` for `Navbar`?

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

* 2 - Nearly all unit tests are in place. React components are well tested with a diverse set of tests including but not limited to snapshot tests, event simulation tests, and tests on class methods.  All routes have been tested as well including dynamic routes.  There are tests in place for actions, reducers, mapStateToProps, and mapDispatchToProps.  No attempt to test async functionality was made.
* 3 - All Redux functionality is tested (actions, reducers, mapStateToProps, mapDispatchToProps), all components are unit tested, and a valid attempt was made to test any async functionality.

### Routing

* 3 - Application uses React Router to display appropriate components based on URL.  UX is clear and set up well so that user has access to previous routes.
