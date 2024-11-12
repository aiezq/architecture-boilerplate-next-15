# Next.js Architecture Boilerplate

This repository serves as a boilerplate and explains the project structure for a Next.js application using a feature-based architecture. It's designed to help developers quickly start new projects with a scalable and maintainable structure.

## Project Structure

The project follows a feature-based architecture:

```
src/
├── app/
├── entities/
├── features/
├── shared/
├── views/
└── widgets/
```

- `app/`: Core application components
- `entities/`: Business logic and data models
- `features/`: Specific functionalities
- `shared/`: Reusable components and utilities
- `views/`: Page layouts and compositions
- `widgets/`: Complex UI components

## Getting Started

1. Clone this repository
2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```
   npm run dev
   ```

4. Open http://localhost:3000 in your browser

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Feature-Sliced Design](https://feature-sliced.design/)
