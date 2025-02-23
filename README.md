# Form Validation with Zod in TypeScript & React

This is a React-based form validation project using **Zod**, **TypeScript**, and **React Hook Form**. It ensures robust input validation, including email verification via an API endpoint.

## Features
- **Zod Schema Validation** for form inputs
- **TypeScript** for type safety
- **React Hook Form** for efficient form handling
- **Email validation** via an API endpoint

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

### 2. Install Dependencies
```sh
npm install  # or yarn install
```

### 3. Set API Endpoint
Update the file `userForms4.tsx` with your API endpoint for email validation:
```ts
const API_ENDPOINT = "https://your-api-url.com/validate-email";
```

### 4. Start the Development Server
```sh
npm run dev  # or yarn dev
```

## Usage
- Fill out the form fields.
- Form will validate fields using Zod.
- Email field validation will be checked against your API.
- If all validations pass, the form can be submitted successfully.

## Tech Stack
- **React** (Frontend framework)
- **TypeScript** (Static typing)
- **Zod** (Schema validation)
- **React Hook Form** (Form handling)

## Folder Structure
```
/project-root
  ├── src/
  │   ├── components/
  │   │   ├── Form.tsx
  │   │   ├── userForms4.tsx  # API validation logic
  │   ├── App.tsx
  │   ├── main.tsx
  ├── package.json
  ├── README.md
```

## Contributing
Feel free to submit issues and pull requests!



