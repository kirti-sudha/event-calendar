<<<<<<< HEAD
# Custom Event Calendar

A modern, feature-rich calendar application built with React, TypeScript, Vite, Tailwind CSS, and shadcn-ui.

## Features
- Add, edit, and delete events
- Support for recurring events (daily, weekly, monthly)
- View events in a monthly grid or list
- Drag-and-drop event rescheduling
- Color-coded events and categories
- Responsive and mobile-friendly UI

## Recurring Events
- Create events that repeat daily, weekly, or monthly
- Recurring events are visible in all future months according to their pattern
- (Advanced) Support for deleting or updating individual instances of recurring events (with code modifications)

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm (v9+ recommended)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/iamKirtix/custom-event-calendar1.git
   ```
2. Navigate to the project directory:
   ```sh
   cd custom-event-calendar1/custom-event-calendar1
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

### Running the App
Start the development server:
```sh
npm run dev
```
The app will be available at [http://localhost:8080](http://localhost:8080) (or the port shown in your terminal).

### Building for Production
```sh
npm run build
```

### Linting
```sh
npm run lint
```

## Project Structure
- `src/` — Main source code (components, hooks, types)
- `public/` — Static assets (e.g., favicon, images)
- `index.html` — Main HTML file

## Technologies Used
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)

## Customization
- You can easily extend the calendar to support more recurrence rules, custom views, or integrations.
- To change the favicon, replace `public/image.png` and update the `<link rel="icon">` in `index.html`.

## License
MIT

---

For questions or contributions, please open an issue or pull request on [GitHub](https://github.com/iamKirtix/custom-event-calendar1).
=======
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

>>>>>>> c1886ad39c514292c39b1fbe9eef11ca220c6c25
