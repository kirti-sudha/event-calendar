# 📅 Custom Event Calendar

An interactive and dynamic **Event Calendar** application built using ReactJS. This calendar allows users to manage their schedules efficiently by adding, editing, deleting, and viewing events. It also supports advanced features like recurring events, drag-and-drop rescheduling, and local persistence.

---

## 🚀 Features

### ✅ Monthly View
- Traditional calendar view
- Highlight for the current day
- Navigation between months

### ✅ Event Management
- Add events with:
  - Title
  - Date & Time picker
  - Description
  - Recurrence options (Daily, Weekly, Monthly, Custom)
  - Color/category (optional)
- Edit existing events
- Delete events

### ✅ Recurring Events
- Daily, Weekly, Monthly, and Custom recurrence logic
- Proper expansion and display across the calendar view

### ✅ Drag-and-Drop Rescheduling
- Easily reschedule events by dragging them to a different day
- Automatically handles updates to dates and potential conflicts

### ✅ Conflict Management
- Detects and warns about overlapping events
- Prevents accidental scheduling of clashing events

### ✅ Event Filtering & Search (Optional)
- Search events by title or description
- Filter events by category or date (if implemented)

### ✅ Event Persistence
- Uses **LocalStorage** or **IndexedDB** to persist events across sessions

### ✅ Responsive Design (Optional)
- Mobile-friendly layout with potential weekly/daily views

---

## 💻 Tech Stack

- **Frontend:** ReactJS, TailwindCSS (or CSS/SCSS)
- **Calendar UI:** `react-big-calendar` or custom layout
- **Date Handling:** `date-fns` or `moment.js`
- **Drag-and-Drop:** `react-dnd` or `react-beautiful-dnd`
- **State Management:** React Context, useReducer, or Redux (depending on complexity)
- **Persistence:** LocalStorage / IndexedDB / Supabase (optional)

---

## 🧠 How It Works

1. Users can click on a calendar date to add an event.
2. A modal form collects event details including recurrence.
3. Events are rendered on the monthly view.
4. Recurring events are expanded and rendered accordingly.
5. Users can drag and drop events to reschedule them.
6. Changes are saved in the local database to persist across refreshes.

---

## 📦 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/event-calendar.git
cd event-calendar

