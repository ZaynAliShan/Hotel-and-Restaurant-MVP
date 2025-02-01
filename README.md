# Hotel and Restaurant Management System MVP

A comprehensive full-stack web application for managing hotels and restaurants, built with React and modern web technologies. This MVP provides complete solutions for hotel bookings, restaurant ordering, and administrative management.

## 🌟 Features

### 🏨 Hotel Management
- **Room Booking System**: Browse and book hotel rooms with detailed descriptions
- **Room Management Dashboard**: Manage room availability, types, and status
- **Hotel Services**: Display and manage hotel amenities and services
- **Gallery**: Showcase hotel facilities with image galleries
- **Check-in/Check-out Management**: Handle guest check-ins and check-outs
- **Payment Tracking**: Monitor room payments and pending transactions

### 🍽️ Restaurant Management
- **Restaurant Home Page**: Browse restaurants and view menus
- **Order Landing Page**: Discover restaurants with map integration
- **Menu Display**: Interactive menu browsing with product details
- **Shopping Cart**: Add items to cart and manage orders
- **Order Management**: Track and manage restaurant orders
- **Customer Management**: Handle customer profiles and analytics

### 👥 Admin Dashboards
- **Main Admin Dashboard**: Comprehensive system overview and management
- **Hotel Manager Dashboard**: Hotel-specific management tools
- **Restaurant Admin Dashboard**: Restaurant operations and analytics
- **User Management**: Manage accounts and permissions
- **Payment Management**: Handle payments and transactions
- **Analytics**: View detailed analytics and reports

### 🔐 Authentication & Security
- Firebase Authentication integration
- Secure user login and registration
- Role-based access control
- Protected routes and sessions

## 🛠️ Tech Stack

### Frontend
- **React 18.2.0** - Modern UI library
- **React Router DOM 6.22.3** - Client-side routing
- **Tailwind CSS 3.4.1** - Utility-first CSS framework
- **Ant Design 5.15.2** - Enterprise UI component library
- **React Icons 5.0.1** - Icon library
- **React Yandex Maps 4.6.0** - Map integration

### Backend & Services
- **Firebase 10.8.1** - Authentication and backend services
- **JSON Server 1.0.0** - Mock REST API for development
- **Axios 1.6.7** - HTTP client

### Development Tools
- **Create React App** - Build toolchain
- **Prettier 3.2.5** - Code formatter
- **ESLint** - Code linting

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v14 or higher)
- **npm** or **yarn** package manager
- **Git** for version control

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ZaynAliShan/Hotel-and-Restaurant-MVP.git
   cd Hotel-and-Restaurant-MVP
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Get your Firebase configuration credentials
   - Update `src/pages/auth/firebaseConfig.js` with your Firebase config:
     ```javascript
     const firebaseConfig = {
       apiKey: "YOUR_API_KEY",
       authDomain: "YOUR_AUTH_DOMAIN",
       projectId: "YOUR_PROJECT_ID",
       storageBucket: "YOUR_STORAGE_BUCKET",
       messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
       appId: "YOUR_APP_ID",
       measurementId: "YOUR_MEASUREMENT_ID"
     };
     ```

4. **Start JSON Server** (for mock API)
   ```bash
   npx json-server --watch public/api/db.json --port 3001
   ```

5. **Start the development server**
   ```bash
   npm start
   ```

6. **Open your browser**
   - Navigate to [http://localhost:3000](http://localhost:3000)
   - The app will automatically reload when you make changes

## 📁 Project Structure

```
Hotel-and-Restaurant-MVP/
├── public/
│   ├── api/
│   │   └── db.json          # JSON Server database
│   └── index.html
├── src/
│   ├── assets/              # Images, CSS, and static assets
│   │   ├── css/
│   │   ├── images/
│   │   └── landing-img/
│   ├── components/          # Reusable React components
│   │   └── layout/         # Layout components (header, footer, navbar)
│   ├── pages/              # Page components
│   │   ├── auth/           # Authentication pages
│   │   ├── app/            # Main application pages
│   │   │   ├── admin/      # Admin dashboard pages
│   │   │   ├── homeRestaurant/
│   │   │   ├── orderLandingPage/
│   │   │   ├── profile/
│   │   │   └── restourant/
│   │   ├── main-admin-page/
│   │   ├── main-hotel-dashboard/
│   │   └── main-hotel-page/
│   ├── routes/             # Route configuration
│   ├── util/               # Utility functions
│   ├── index.js            # Application entry point
│   └── index.css           # Global styles
├── package.json
├── tailwind.config.js
└── README.md
```

## 🎯 Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run eject`
**Note: This is a one-way operation. Once you `eject`, you can't go back!**

Ejects from Create React App, giving you full control over the build configuration.

## 🔗 Key Routes

- `/` - Main landing page
- `/loginSignUp` - User login
- `/signUp` - User registration
- `/MainDashboardIndex` - Main admin dashboard
- `/MainDashboard` - Hotel manager dashboard
- `/homerestourant` - Restaurant home page
- `/orderlist` - Order management
- `/itemlist` - Item management
- `/customer` - Customer management

## 🎨 Design Resources

The project design is based on the Figma design:
- [Figma Design](https://www.figma.com/file/dOWXll72Gww8GR88QvXG5B/Online-Hospitality-Facility-Finder-System-Design-(Community)?type=design&node-id=84-3096&mode=design&t=kE13BdU6pTYSKosy-0)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Zayn Ali Shan**
- GitHub: [@ZaynAliShan](https://github.com/ZaynAliShan)
- Email: zainalishann@gmail.com

## 🙏 Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- UI components from [Ant Design](https://ant.design/)
- Styling with [Tailwind CSS](https://tailwindcss.com/)
- Authentication powered by [Firebase](https://firebase.google.com/)

## 📞 Support

For support, email zainalishann@gmail.com or open an issue in the repository.

---

⭐ If you found this project helpful, please consider giving it a star!
