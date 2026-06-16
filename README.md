# To-Do List Application

A simple, elegant, and functional to-do list application with local storage functionality. Built with vanilla JavaScript, HTML, and CSS.

## Features

✅ **Add Tasks** - Easily add new tasks to your to-do list
✅ **Mark Complete** - Check off tasks as you complete them
✅ **Delete Tasks** - Remove individual tasks or clear all completed tasks
✅ **Filter Tasks** - View all, active, or completed tasks
✅ **Local Storage** - All tasks are automatically saved to your browser's local storage
✅ **Responsive Design** - Works perfectly on desktop and mobile devices
✅ **Task Counter** - See how many active tasks you have

## How to Use

1. Open `index.html` in your web browser
2. Type a task in the input field
3. Press Enter or click the "Add" button to add the task
4. Check the checkbox to mark a task as complete
5. Click "Delete" to remove a specific task
6. Use the filter buttons to view all, active, or completed tasks
7. Click "Clear Completed" to remove all finished tasks

## Technical Details

### Architecture
- **HTML Structure** - Clean semantic markup with a single container for the app
- **CSS Styling** - Modern gradient design with smooth transitions and animations
- **JavaScript** - Object-oriented approach using a `TodoApp` class for better maintainability

### Local Storage
- All tasks are automatically saved to browser's local storage under the key `todoAppData`
- Tasks persist even after closing and reopening the browser
- Data is stored as JSON for easy serialization and deserialization

### Key Methods
- `addTodo()` - Creates a new task with unique ID and timestamp
- `deleteTodo(id)` - Removes a specific task
- `toggleTodo(id)` - Marks a task as complete/incomplete
- `clearCompleted()` - Removes all completed tasks with confirmation
- `saveTodos()` - Persists tasks to local storage
- `loadTodos()` - Retrieves tasks from local storage on app initialization
- `render()` - Updates the DOM with current task list

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- Local Storage API
- CSS Flexbox and Grid

## Customization

You can easily customize:
- Colors in `styles.css` (change gradient colors, button colors, etc.)
- Storage key in `script.js` (line: `this.storageKey = 'todoAppData'`)
- Input placeholder text in `index.html`

## Future Enhancements

Possible improvements:
- Add due dates and priorities
- Task categories/tags
- Dark mode toggle
- Export/import tasks
- Recurring tasks
- Cloud synchronization

## License

Open source - feel free to use and modify!
