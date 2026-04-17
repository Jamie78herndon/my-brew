# Project Structure and Architecture

## Project Structure

```plaintext
my-brew/
├── README.md
├── src/
│   ├── components/
│   ├── hooks/
│   └── utils/
├── tests/
├── public/
└── package.json
```

## Architecture Overview

This project follows a modular architecture, consisting of:
- **Components**: Reusable UI parts. 
- **Hooks**: Custom logic for managing state.
- **Utils**: Helper functions for various functionalities.

### Data Flow

Data within the application flows from the main components to child components, utilizing React's context for state management when necessary.