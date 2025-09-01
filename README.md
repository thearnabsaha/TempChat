# TempChat

TempChat is a modern, full-stack chat application designed to provide seamless communication with a clean and intuitive user interface. This project is divided into two main parts: the backend and the frontend.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [APIs and Libraries](#apis-and-libraries)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Contributing](#contributing)
- [License](#license)

## Features
- Real-time messaging
- Modern UI/UX design
- Scalable backend architecture
- Responsive design for mobile and desktop
- **Memory Retention**: The application retains chat memories for 30 minutes, after which the memory is refreshed.

## Tech Stack
### Backend
- **Language**: TypeScript
- **Framework**: Node.js
- **Libraries**: Express, Zod, LangChain, Groq, Tavily
- **Environment Variables**: Managed using `.env` files

### Frontend
- **Framework**: Next.js
- **Styling**: Tailwind CSS, shadcn/ui
- **State Management**: React Hook Form
- **Package Manager**: pnpm

## Folder Structure
```
TempChat/
├── backend/                # Backend codebase
│   ├── src/               # Source files
│   ├── package.json       # Backend dependencies
│   ├── tsconfig.json      # TypeScript configuration
│   └── .env               # Environment variables
├── frontend/               # Frontend codebase
│   ├── app/               # Next.js app directory
│   ├── components/        # Reusable components
│   ├── lib/               # Utility functions
│   ├── public/            # Static assets
│   ├── package.json       # Frontend dependencies
│   ├── tsconfig.json      # TypeScript configuration
│   └── .next/             # Build output
```

## APIs and Libraries
### Backend
- **LangChain**: Provides tools for building applications with language models. Used for natural language processing and AI-driven features.
- **Groq**: A query language for JSON-like data. Used for querying structured data efficiently.
- **Tavily**: A library for managing conversational AI workflows.
- **LangGraph**: A graph-based library for managing relationships between language models and data.
- **Express**: A web framework for building RESTful APIs.
- **Zod**: A TypeScript-first schema validation library.

### Frontend
- **shadcn/ui**: A collection of accessible and customizable UI components built with Tailwind CSS.
- **React Hook Form**: A library for managing form state and validation.
- **Radix UI**: Provides accessible and composable React components.
- **Tailwind CSS**: A utility-first CSS framework for styling.
- **Lucide Icons**: A library of customizable icons for React.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Node.js (>= 18.x)
- pnpm (>= 8.x)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/thearnabsaha/TempChat.git
   cd TempChat
   ```

2. Install dependencies for both backend and frontend:
   ```bash
   # Install backend dependencies
   cd backend
   pnpm install

   # Install frontend dependencies
   cd ../frontend
   pnpm install
   ```

### Running the Application
1. Start the backend server:
   ```bash
   cd backend
   pnpm run dev
   ```

2. Start the frontend development server:
   ```bash
   cd ../frontend
   pnpm run dev
   ```

3. Open your browser and navigate to `http://localhost:3000` to view the application.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
