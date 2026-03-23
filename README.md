WorldWise – Travel Tracking App

A geographic travel tracking application that allows users to log, visualize, and manage the places they’ve visited on an interactive map.
This project focuses on combining map-based UI, state management, and dynamic data handling to create a real-world, data-driven user experience.


Features:
* Interactive map to explore locations
* Add and manage visited cities
* Store notes/details for each location
* Dynamic UI updates based on user interactions
* Navigation between map and app views
* Responsive design for multiple screen sizes


Tech Stack:
* Frontend: React
* State Management: Context API / useReducer
* Routing: React Router
* Maps: Leaflet
* Styling: CSS Modules
* Tooling: Vite
* Deployment: Netlify


Architecture & Key Concepts:
* Global State Management
Managed application-wide data (cities, selected location) using Context API to avoid prop drilling.

* Reducer Pattern
Used useReducer for predictable state transitions and better scalability.

* Map Integration
Synced UI state with map interactions (clicking, selecting, rendering markers).

* Component-Driven Design
Built reusable UI components to separate concerns and improve maintainability.

* Routing & Navigation
Structured multi-page navigation with protected and dynamic routes.

* Asynchronous Data Handling
Managed loading states and side effects for a smooth user experience.
