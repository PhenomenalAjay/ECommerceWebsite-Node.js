

### Click "[Live Demo](https://e-commerce-websites-3l2v.onrender.com)" to view my Website .

---

### Overview
This is an e-commerce website built using HTML, Tailwind CSS for styling, and Express.js as the backend framework. The website features multiple pages including Home, Collection, Wishlist, and others.

### Features
- Responsive design using Tailwind CSS
- Dynamic product display on the Home page fetched from an external API
- Navigation bar with links to Home, Collection, and Wishlist pages
- Side navigation for mobile view
- Footer with social media icons
- Basic routing handled by Express.js

### Folder Structure
```
/ (root)
|-- app.js                 # Main Express application setup
|-- package.json           # Project dependencies and scripts
|-- routes/                # Express route handlers
|   |-- admin.js           # Admin related routes (serves home page)
|   |-- auth.js            # Authentication routes (signup, login)
|   |-- shop.js            # Shop related routes (collection, wishlist)
|-- views/                 # HTML view templates
|   |-- 404.html           # 404 error page
|   |-- collection.html    # Product collection page
|   |-- home.html          # Home page
|   |-- wishlist.html      # Wishlist page
|-- utils/                 # Utility modules
|   |-- path.js            # Utility for handling file paths
|-- assets/                # Static assets like videos
|-- images/                # Static images served by Express
|-- README.md              # Project documentation
```

### Routes Overview
- `/` (Admin route) serves the Home page
- `/collection` serves the product collection page
- `/wishlist` serves the wishlist page
- `/signup` and `/login` handle user authentication via POST requests

### Login Setup (Using Axios)
This project can be extended to include user authentication using Axios for API requests. For example, you can use Axios in the frontend or backend to send login credentials to an authentication API endpoint.
|-- README.md              # Project documentation



### How to Extend
- Add a login form in the frontend to collect username and password
- Use Axios to send login requests to your backend or external authentication service
- Implement session management or token storage for authenticated users
- Protect routes that require authentication

### Running the Project
1. Clone the repository
2. Run `npm install` to install dependencies
3. Start the server with `node app.js`
4. Open your browser and navigate to `http://localhost:3000`

### Dependencies
- Express.js
- Tailwind CSS (via CDN)
- Font Awesome (via CDN)
- Axios (for API requests, can be added as needed)
- bcrypt (for password hashing)

### License
This project is open source and free to use.

