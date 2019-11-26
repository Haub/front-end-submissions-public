### Evaluator: Robbie
### Students: Elyse
### Comments:

* Overall theme is great - simple and consistent throughout the app
* Would be nice to have some additional filters for products on each category page so I can decide from the list of products

* 64 passed

* For `App` `componentDidMount`, I think I would move these fetches to the page where the data is needed. The opening page is kind of slow because we are waiting for the data to load, but we don't actually see/interact with that data on the home page
* Using async await in `App` `componentDidMount` will make your data fetching slower in the end - async await behaves synchronously in the `try` block, whereas using `Promise.all()` could allow these fetches to occur in parallel
* Naming conventions for action creators are all great
* `exact` not needed on all routes in `App` - careful with overusing it as it can be confusing
* Curious if you need the fragment in `App` render with the Switch?
* Good route naming conventions
* Empty `localStorage` file?
* For the `Product`, having the `require('../Images/default_image.jpg')` in the `return` might be making your code do more work than it needs to as opposed to requiring at the top of the file once and then referring to a variable

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
* 4 - All async functionality is tested.   Asynchronous tests cover happy paths as well as multiple sad paths.  All pieces of functionality have been tested and are passing and run efficiently (using mount only when appropriate). Evaluator has no recommendations for testing.

### Routing

* 3 - Application uses React Router to display appropriate components based on URL.  UX is clear and set up well so that user has access to previous routes.
