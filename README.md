# Portfolio Monorepo

This monorepo contains multiple projects showcasing my skills as a full-stack developer. The repository is managed using Lerna to streamline the development process across multiple projects.

## Projects

1. **E-Commerce Platform**

   - Tech Stack: React, Node.js, Express.js, MongoDB
   - Description: A full-fledged e-commerce platform with user management, product browsing, shopping cart functionality, and more.

2. **Blog Platform**

   - Tech Stack: Vue.js, Flask, PostgreSQL
   - Description: A blogging platform where users can register, write, edit, and delete posts, as well as comment on posts.

3. **Real-time Chat Application**

   - Tech Stack: Angular, Django, WebSockets, SQLite
   - Description: A chat application with real-time messaging, chat room management, and user registration.

4. **Chrome Extension - Bookmark Manager**

   - Tech Stack: JavaScript, HTML, CSS, Chrome Extension API
   - Description: A Chrome extension to manage bookmarks with custom tags and categories.

5. **Personal Portfolio Website**

   - Tech Stack: Gatsby.js, GraphQL, Netlify
   - Description: A website to showcase my projects, skills, and work experience.

6. **Weather Application**
   - Tech Stack: Svelte, Express.js, Redis
   - Description: An application to search and view weather information for cities globally.

## Getting Started

1. **Clone the repository:**

   ```
   git clone [repository-url]
   cd portfolio-monorepo
   ```

2. **Install global dependencies:**

   ```
   npm install -g lerna
   ```

3. **Bootstrap the projects (install dependencies):**

   ```
   lerna bootstrap
   ```

4. **Navigate to any project:**

   ```
   cd packages/[project-name]
   ```

5. **Run the project-specific commands (e.g., start, build).**

## Using Lerna

1. **Add a dependency to all projects:**

   ```
   lerna add [dependency-name]
   ```

2. **Add a dependency to a specific project:**

   ```
   lerna add [dependency-name] --scope=[project-name]
   ```

3. **Run scripts across projects (e.g., start):**
   ```
   lerna run start
   ```

## Contribution

Feel free to contribute, raise issues, or suggest improvements. All contributions are welcome!
