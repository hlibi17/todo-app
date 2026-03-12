# Enhanced Todo App 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## ✨ Features

This is a **fully-featured, modern Todo application** built with vanilla HTML, CSS (Tailwind), and JavaScript. No frameworks or build tools required!

### Core Functionality
- ✅ **Task Management**: Add, edit, delete, mark complete
- ✅ **Categories**: Personal, Work, Health, Shopping (color-coded)
- ✅ **Priorities**: High, Medium, Low
- ✅ **Due Dates & Reminders**: Browser notifications for overdue/upcoming tasks
- ✅ **Team Collaboration**: Assign tasks to team members
- ✅ **Search & Filters**: Filter by status, category; sort by priority/date
- ✅ **Progress Tracking**: Visual progress bar & stats dashboard

### UI/UX
- 🌙 **Dark/Light Mode** (auto-detects system preference)
- 📱 **Fully Responsive** (mobile-first design)
- 🎨 **Modern Glassmorphism** design with animations
- 📊 **Sidebar Dashboard**: Stats, categories, team, upcoming reminders
- 💬 **Task Comments** in edit modal
- 📤 **Export/Import** JSON data
- 🔔 **Toast Notifications**

### Data & Performance
- 💾 **LocalStorage Persistence** (data saved in browser)
- ⚡ **Instant Search** & real-time updates
- 🎭 **Smooth Animations** & transitions

## 🖼️ Screenshots

### Light Mode - Desktop
![Desktop Light](https://via.placeholder.com/1200x800/ffffff/4a5568?text=Enhanced+Todo+App+-+Light+Mode)

### Dark Mode - Mobile
![Mobile Dark](https://via.placeholder.com/400x800/1a202c/4a5568?text=Enhanced+Todo+App+-+Dark+Mode)

### Team View & Dashboard
![Team Dashboard](https://via.placeholder.com/1200x800/2d3748/4a5568?text=Team+Dashboard)

*(Replace with actual screenshots after deployment)*

## 🚀 Quick Start

1. **Download/Clone** the repo
2. **Open** `index.html` in any modern browser
3. **Start using** immediately!

```
git clone https://github.com/hlibi17/todo-app.git
cd todo-app
open index.html  # or double-click the file
```

**No installation required!** Uses CDN for Tailwind CSS & Font Awesome.

## 📋 Usage

### Adding Tasks
1. Type task description
2. Select **Category**, **Priority**, **Due Date**, **Reminder Time**
3. Assign to team member (auto-adds new members)
4. Click **+** or press Enter

### Team Management
- Switch to **Team** view in top tabs
- Add team members with optional roles
- Assign tasks via assignee field

### Data Backup
- **Export**: Download JSON file from footer
- **Import**: Click import icon & select JSON file

### Keyboard Shortcuts
- `Enter`: Add task (in input field)
- `Esc`: Close modals

## 🛠️ Customization

Edit `index.html`:

```html
<!-- Change categories -->
<select id="category-select">
    <option value="personal">Personal</option>
    <!-- Add your own -->
</select>

<!-- Modify colors (Tailwind classes) -->
<div class="bg-indigo-600">...</div>

<!-- Add new features in <script> section -->
```

## 🌐 Browser Support

- Chrome 80+, Firefox 75+, Safari 13.1+, Edge 80+
- Works offline (after first load)
- Progressive Web App ready

## 📱 PWA Installation
1. Open in browser
2. Click install icon in address bar
3. Use as native app!

## 🔒 Privacy & Security
- **All data stored locally** in browser LocalStorage
- **No tracking or external requests**
- **No backend required**
- Data only accessible to you

## 📈 Stats Dashboard
- Total tasks & progress
- Category breakdowns
- Team workload
- Upcoming reminders

## 🚧 Roadmap
- [x] Categories & Filters
- [x] Reminders/Notifications
- [x] Team Collaboration
- [x] Dark Mode
- [x] Export/Import
- [ ] Cloud sync (Firebase)
- [ ] Recurring tasks
- [ ] Task subtasks

## 🤝 Contributing
1. Fork the repo
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License
MIT License - see [LICENSE](LICENSE) file.

## 👨‍💻 Author
**hlibi17** - [GitHub](https://github.com/hlibi17)

## 🙏 Acknowledgments
- [Tailwind CSS](https://tailwindcss.com) - Beautiful utility-first CSS
- [Font Awesome](https://fontawesome.com) - Amazing icons
- Inter font from Google Fonts

---

⭐ **Star this repo if you found it useful!** ⭐

**Deploy instantly**: Just upload `index.html` to GitHub Pages, Netlify, Vercel, or any static host!

