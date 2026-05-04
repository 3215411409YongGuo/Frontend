# Book Management System — Frontend

Vue.js frontend for the Book Management System (COMP3000 Final Year Project).

## Tech Stack

- **Framework:** Vue.js 2
- **UI Library:** Element UI
- **State Management:** Vuex
- **Routing:** Vue Router
- **HTTP Client:** Axios
- **Testing:** Jest, Vue Test Utils

## Project Structure

```
├── src/
│   ├── api/          # API modules (bookinfo, booktype, borrow, user)
│   ├── components/   # Reusable components (Breadcrumb, Hamburger, SvgIcon)
│   ├── directive/    # Custom directives (v-permission)
│   ├── layout/       # Main layout with AI assistant widget
│   ├── router/       # Route definitions and navigation guards
│   ├── store/        # Vuex store (user, permission modules)
│   ├── utils/        # Utility functions (request, validate, index)
│   └── views/        # Page components (bookinfo, booktype, borrow, user)
├── tests/unit/       # Jest unit tests
├── mock/             # Mock data
└── public/           # Static assets
```

## Getting Started

### Prerequisites

- Node.js 14+
- npm

### Installation

```bash
npm install
```

### Development

```bash
npm run serve
```

### Production Build

```bash
npm run build
```

### Run Unit Tests

```bash
npm run test:unit
```

## Key Features

- Book search with dynamic filtering (title, author, category)
- Role-based UI using custom v-permission directive
- Token-based authentication with Vuex and localStorage persistence
- AI assistant chat widget with SSE streaming responses
- Paginated data tables with CRUD operations

## Backend Repository

[https://github.com/3215411409YongGuo/Backend](https://github.com/3215411409YongGuo/Backend)

## Main Repository

[https://github.com/3215411409YongGuo/Comp3000](https://github.com/3215411409YongGuo/Comp3000)

## License

This project is released under the Creative Commons Zero (CC0) licence for educational purposes.
