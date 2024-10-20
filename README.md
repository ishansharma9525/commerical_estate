Your README file is well-structured and informative! Here’s a corrected and polished version with some improvements for clarity and consistency:

---

# Estate Hub

Estate Hub is a MERN stack real estate application. In this app, users can create accounts, view listings, filter or search for listings, and add them to their favorites. Additionally, users can create listings to sell or rent their properties.



## :bulb: Features

- Responsive UI
- Dark and Light Theme
- Infinite Scroll
- JWT Authentication
- Filter Listings
- Search by Location or Title
- Create and Edit Listings
- Notifications and Favorites

## :hammer_and_wrench: Built With

- [TypeScript](https://www.typescriptlang.org/) - Main Language
- [React](https://reactjs.org/) - UI Library
- [TailwindCSS](https://tailwindcss.com/) - CSS Framework
- [Zustand](https://zustand-demo.pmnd.rs/) - State Management
- [GraphQL](https://graphql.org/) - Query Language
- [Node.js](https://nodejs.org/en) - Backend
- [Express.js](https://expressjs.com/) - Node.js Framework
- [MongoDB](https://www.mongodb.com/) - NoSQL Database
- [Mongoose](https://mongoosejs.com/) - Database ODM
- [React Icons](https://react-icons.github.io/react-icons/) - Icon Library
- [Bcrypt](https://www.npmjs.com/package/bcryptjs) - Password Encryption
- [Cloudinary](https://www.cloudinary.com/) - Image Storage



## :triangular_flag_on_post: Getting Started

To get started, clone the repository and install the dependencies for both the server and client:

```shell
git clone https://github.com/ishansharma9525/MERN-Stack-Real-Estate-App.git

cd client
npm install

cd ../server
npm install
```

### Environment Variables

After installing the dependencies, you must assign the following environment variables:

For the client:

```shell
VITE_CLOUD_NAME - Cloudinary cloud name
VITE_UPLOAD_PRESET - Cloudinary upload preset
```

For the server:

```shell
MONGODB_URI
JWT_ACCESS_SECRET
JWT_REFRESH_SECRET
```

### Running the Development Server

To run the development server for both the client and server, use the following command:

```shell
npm run dev
```

---

Feel free to adjust any sections according to your preferences or project specifics!
