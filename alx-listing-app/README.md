# ALX Listing App

## Project Description

The **ALX Listing App** is a project aimed at creating a foundation for an Airbnb clone. This milestone focuses on scaffolding a Next.js app with TypeScript, TailwindCSS, and ESLint configurations to ensure a clean, scalable, and maintainable codebase. The project will lay the groundwork for building a property listing page, complete with reusable components and a well-organized folder structure.

---

## Project Structure

The project follows a modular and maintainable structure. Below is an overview of the key directories and files:

### **1. `components/`**

Contains reusable UI components used across the project.

- **`common/`**:
  - **`Card.tsx`**: A reusable Card component to display property information.
  - **`Button.tsx`**: A reusable Button component for actions like "Book Now", "Details", etc.

### **2. `interfaces/`**

Defines TypeScript interfaces used throughout the project for type safety.

- **`index.ts`**: Includes interfaces like `CardProps` and `ButtonProps`.

### **3. `constants/`**

Stores reusable constants such as API URLs, configuration settings, or UI text.

- **`index.ts`**: Contains reusable constants for the app.

### **4. `public/assets/`**

Contains static assets such as images and SVGs.

- Stores image files and other assets used throughout the project.

### **5. `styles/`**

Contains global styles and TailwindCSS configurations.

- **`globals.css`**: Imports Tailwind’s default styles.

### **6. `pages/`**

Contains pages for routing in the application.

- **`index.tsx`**: The entry point of the app and the first page displayed to users.

---

## Installation Instructions

Follow the steps below to set up and run the project locally:

### **1. Install Dependencies**
First, clone the repository to your local machine. Then, navigate to the project directory and install the dependencies:
```bash
git clone <repository-url>
cd alx-listing-app
npm install
