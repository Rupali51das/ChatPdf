
# ChatPdf
**PDF Query Assistant**  
A full-stack application enabling users to query and upload PDF files, leveraging a Retrieval-Augmented Generation (RAG) system with OpenAI’s API. Built with a React frontend, FastAPI backend, and MongoDB for query history storage, it provides seamless interaction and intelligent responses based on PDF content.

## Features
---
1. **Upload PDF**: Users can upload a PDF file through an intuitive interface to enable the system to process its content.

2. **Input Query**: Users can type in their questions related to the uploaded PDF directly in the query box on the frontend.

3. **Receive Responses**: The application retrieves relevant information from the PDF using the RAG system and OpenAI’s API, providing accurate and contextual answers.

4. **Query History**: Users can view past queries and responses stored in MongoDB for reference, ensuring continuity and easy access to previously searched information.

----

## Functionalities

### Homepage
![as1](https://github.com/user-attachments/assets/15048e3e-0207-4967-92a3-4c17b67fd532)

### Uploading a file
![as2](https://github.com/user-attachments/assets/5c046282-766a-46bf-8428-230792af1699)

### Getting Result
![as3](https://github.com/user-attachments/assets/d876fbd6-44e0-4b0a-b2a2-59335803351b)

### Getting History

### Image Table

| ![as6](https://github.com/user-attachments/assets/24861687-7b9d-44d1-82f8-9854c56e5f9f) | ![as5](https://github.com/user-attachments/assets/29477cf0-ad3e-4214-aa04-d4f550ddfbde) | ![as4](https://github.com/user-attachments/assets/ba631ce4-8bda-4035-8f7a-45b5be5332ee) |
|------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|

----

## Prerequisites

Make sure you have the following installed:

- **Node.js** (v16+ recommended)
- **npm** or **yarn**

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Rjjha/ChatPdf-Frontend.git
   cd ChatPdf-Frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

---

## Development

Start the development server:

```bash
npm run dev
# or
yarn dev
```

The app will be live at [http://localhost:5173](http://localhost:5173).

---

## Build

To create a production-ready build:

```bash
npm run build
# or
yarn build
```

The built files will be available in the `dist/` folder.

---

## Scripts

- **`npm run dev`**: Start the development server.
- **`npm run build`**: Build the project for production.
- **`npm run preview`**: Preview the production build locally.
- **`npm run lint`**: Lint the TypeScript and React code.

---

## Tailwind Configuration

Tailwind CSS is configured in `tailwind.config.js`. Modify this file to customize your design system.

---

## Project Structure

```
├── public/          # Static assets
├── src/
│   ├── assets/      # Images and static files
│   ├── components/  # Reusable React components
│   ├── pages/       # Page-level components
│   ├── styles/      # Global and component styles
│   ├── App.tsx      # Root component
│   └── main.tsx     # Application entry point
├── index.html       # Main HTML file
├── package.json     # Project metadata and scripts
├── postcss.config.js # Tailwind CSS config integration
├── tailwind.config.js # Tailwind CSS configuration
├── tsconfig.json    # TypeScript configuration
└── vite.config.ts   # Vite configuration
```

---

## Contribution

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature-name'`.
4. Push the branch: `git push origin feature-name`.
5. Open a Pull Request.

---

## Acknowledgements

- [Vite](https://vitejs.dev/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)

---
