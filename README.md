# Riot-Blog :newspaper:

A personal blog site built with JavaScript, EJS, and CSS, powered by Express.js on the backend.

## Tech Stack :computer:

**Backend:**

- Node.js
- Express.js (^4.16.3)
- EJS (^2.6.1) (Templating Engine)
- Body-Parser (^1.18.3) (Middleware for parsing request bodies)
- Lodash (^4.17.21) (Utility library)

**Frontend:**

- JavaScript
- CSS
- HTML (implied by EJS usage)


## Installation :wrench:

1. **Clone the repository:**

```bash
git clone https://github.com/YOUR_USERNAME/Riot-Blog.git 
cd Riot-Blog
```

2. **Install dependencies:**

```bash
npm install
```

## Dependencies :link:

Key dependencies are listed in `package.json`.  Important ones include:

- **Express.js:**  Provides the web framework for handling routing and requests.
- **EJS:**  Enables dynamic HTML content generation through templating.
- **Body-parser:** Parses incoming request bodies (e.g., form data) into usable JavaScript objects.



## Usage :rocket:

1. **Start the development server:**

```bash
npm start
```

2. **Access the blog:** Open your web browser and navigate to `http://localhost:3000` (or the port specified by your Express.js setup).

**Example Routes (Assumed):**

- `/`: Homepage, displaying recent blog posts.
- `/posts/:id`: Individual blog post view.
- `/about`: About page.
- `/contact`: Contact page.


## Features :sparkles:

- **Dynamic content generation:** Uses EJS for dynamic templating.
- **"Read More" Functionality:**  Allows users to expand blog post previews to view the full content (based on commit message "final version updated 'read more' function").
- **Routing:** Handles various routes for different pages (assumed based on common blog structure).
- **Data Handling:** Likely utilizes a data storage mechanism (not specified, could be files, database, etc.) for managing blog posts.


## Contributing :handshake:

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Make your changes and commit them with clear, descriptive messages.
4. Push your branch to your forked repository.
5. Submit a pull request to the main repository.


## License :scroll:

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.



---

_Created: 2025-02-01_

_Last Updated: 2025-02-03_
