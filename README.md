# Digital Creative Frontend Test

We want you to develop a search box component with the following requirements:

- The completed page should accurately represent the design templates which can be found here: [figma-link](https://www.figma.com/file/mcHQ3hMUG0fmgWVh6QPUlv/Frontend-test-What-technologies-we-are-using-at-DC?node-id=71%3A377)
- The data should be retrieved from the following api: [`GET -> https://frontend-test-api.digitalcreative.cn/?query=flutter`](https://frontend-test-api.digitalcreative.cn/?query=flutter)
- The correct search box state should be shown accordingly with these rules:
    - [**Initial State:**](./assets/examples/initial-state.png) No search has been performed yet. 
    - [**Search Results:**](./assets/examples/search-results-state.png) Display a list of all matching results. 
    - [**No Results:**](./assets/examples/no-results-state.png) When the api response return no results.

# Rules

- The application has to be developed using `Vue`.
- Split your code into logical reusable components. We want to see how you isolate your components.
- You have to create at least 3 components, which are the search box, the tag and the result item in the list.
- For styling, you can use whatever you want. We use SASS at DC, but feel free to use what you're more comfortable with.
- Add a `README.md` file with the decisions you took, any information you want to share with us (possible improvements, for example), and the installation instructions.

# What we will be looking for

- A nice architecture. Code is read more than it is written, so the easier it gets to follow your code, folder structure, etc... the better.
- Your UI composition. We'll check how you connect the different components of the application between them and how the data/state flows.
- Nice and clean code.

# Bonus points

- CSS Transitions
- Typescript
- Pixel perfect UI implementaion
- Modern build toolsm
- ...
