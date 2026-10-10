# ReHome - Frontend

Frontend web application for the ReHome hyper-local reuse platform. Built with React and Vite to connect neighbors for reusing household items.

## Tech Stack
- **Framework:** React 19
- **Build Tool:** Vite 8
- **UI Components:** Ant Design (`antd`) & `@ant-design/icons`
- **Routing:** React Router v7
- **HTTP Client:** Axios
- **Testing:** Vitest & React Testing Library

## Getting Started

### 1. Installation
```bash
npm install
```

### 2. Environment Configuration
Create a `.env` file in the project root (see `.env.example`):
```env
VITE_API_URL=http://localhost:5000/api
```

### 3. Start Development Server
```bash
npm run dev
# App will run at http://localhost:5173
```

### 4. Build for Production
```bash
npm run build
```

## Features Included
- Home page with category browsing and search
- Server-side search with active category and condition filters
- Item details view with claim pickup helper and save item toggle
- Authenticated item posting modal with multiple image uploads
- My listings dashboard for tracking, re-listing, and deleting items
- Saved items page
- User profile page
- Responsive layout for mobile, tablet, and desktop screens
