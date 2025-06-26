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
