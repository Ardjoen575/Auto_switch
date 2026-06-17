# 📝 To-Do List Application

A modern, responsive to-do list application with **local storage functionality** for persistent task management.

## ✨ Features

### Core Functionality
- ✅ **Add Tasks** - Easily add new tasks to your list
- ✅ **Mark Complete** - Check off tasks as you complete them
- ✅ **Delete Tasks** - Remove individual tasks or clear all
- ✅ **Filter Tasks** - View All, Active, or Completed tasks
- ✅ **Local Storage** - All tasks are automatically saved to your browser
- ✅ **Task Statistics** - See total, completed, and remaining task counts
- ✅ **Priority Badges** - Tasks display priority levels (High/Medium/Low)

### User Experience
- 🎨 Modern, gradient-based UI design
- 📱 Fully responsive design (mobile, tablet, desktop)
- ⌨️ Keyboard support (Enter key to add tasks)
- 🎭 Smooth animations and transitions
- 💾 Persistent storage - no data loss on page refresh
- 📊 Real-time statistics updates

## 🚀 Getting Started

### Option 1: Open in Browser
1. Clone or download this repository
2. Open `index.html` directly in your web browser
3. Start adding tasks!

### Option 2: Live Server
For best experience, use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (http-server)
npx http-server
```

Then open `http://localhost:8000/todo-app` in your browser.

## 📁 File Structure

```
todo-app/
├── index.html        # HTML structure
├── styles.css        # Styling and responsive design
├── script.js         # Application logic
└── README.md         # Documentation
```

## 🎯 How to Use

### Adding a Task
1. Type your task in the input field
2. Click "Add Task" or press Enter
3. Your task appears in the list

### Managing Tasks
- **Check off a task** - Click the checkbox to mark as complete
- **Delete a task** - Click the "Delete" button
- **Clear all completed** - Click "Clear Completed"
- **Delete everything** - Click "Delete All"

### Filtering Tasks
- Click **All** to see all tasks
- Click **Active** to see incomplete tasks
- Click **Completed** to see finished tasks

## 💾 Local Storage Details

All tasks are automatically saved to your browser's **localStorage** under the key `todoList`. This means:
- ✅ Tasks persist after closing the browser
- ✅ Tasks persist after shutting down your computer
- ✅ No server required
- ✅ Complete privacy - data stays on your device

### Storage Limits
- Most browsers allow 5-10MB of local storage
- This is more than enough for thousands of tasks

## 🎨 Customization

### Change Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #4f46e5;      /* Main color */
    --secondary-color: #10b981;    /* Success color */
    --danger-color: #ef4444;       /* Delete color */
}
```

### Change Fonts
Update the font-family in `styles.css`:

```css
body {
    font-family: 'Your Font', sans-serif;
}
```

## 🔧 Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Flexbox layout, gradients, animations
- **Vanilla JavaScript** - No frameworks or dependencies
- **Web APIs** - localStorage API

### Browser Support
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## 🐛 Troubleshooting

### Tasks not saving?
- Check if localStorage is enabled in your browser
- Try clearing browser cache
- Ensure cookies/storage isn't blocked

### Tasks disappeared?
- They may have been cleared by clearing browser data
- Check browser privacy/clearing settings

## 📊 Data Structure

Each task is stored as a JSON object:

```javascript
{
    id: 1234567890,              // Unique identifier
    text: "Task description",     // Task text
    completed: false,             // Completion status
    priority: "medium",           // Priority level
    createdAt: "12/20/2024, 3:30 PM"  // Creation timestamp
}
```

## 🎓 Learning Resources

This app demonstrates:
- DOM manipulation with vanilla JavaScript
- ES6 Classes and Object-Oriented Programming
- localStorage API for data persistence
- Event handling and listeners
- CSS Grid and Flexbox
- Responsive design principles
- State management basics

## 📄 License

Free to use and modify for personal or commercial projects.

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

## 🌟 Future Enhancements

Potential features for future versions:
- 🔔 Task reminders/notifications
- 📅 Due dates for tasks
- 🏷️ Task categories/tags
- 🌙 Dark mode
- ☁️ Cloud sync option
- 📈 Advanced statistics and charts
- 🔍 Search functionality
- 📱 Mobile app version

---

**Made with ❤️ for better productivity**