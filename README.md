# Todo-List-with-filtering-functionality

# Todo List with Filtering Functionality

## Observations and Learnings

1. State Management: This project reinforced my understanding of state management in React. I learned how to manage multiple state variables (`todos`, `newTodo`, and `filter`) and update them based on user interactions.

2. Conditional Rendering: The filtering functionality demonstrated the power of conditional rendering in React. Based on the selected filter (`all`, `active`, or `completed`), the component renders the appropriate subset of todos.

3. Immutable State Updates: To update the `todos` array, I learned the importance of creating a new array instead of modifying the existing one directly. This ensures that React can efficiently detect changes and re-render the component accordingly.

4. Array Methods: I utilized various array methods, such as `map`, `filter`, and `splice`, to manipulate the `todos` array and render the todo list dynamically.

5. Event Handling: The project involved handling events like `onClick` and `onChange` to capture user interactions and update the state accordingly.

6. Component Structure: I organized the component into smaller, reusable functions (`addTodo`, `toggleTodo`, `removeTodo`, `filterTodos`, and `renderTodos`) to improve code readability and maintainability.

7. Styling Components: I applied basic styling to the todo list using inline styles and CSS classes, enhancing the visual presentation of the application.

Overall, this project provided me with hands-on experience in managing complex state in React, implementing conditional rendering, updating state immutably, working with arrays, handling events, structuring components, and styling components. It deepened my understanding of building dynamic and interactive user interfaces with React.