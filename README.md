# City Ride Booking System - Frontend

A modern, responsive, and real-time ride-booking application frontend built with **React** and **Vite**. This application provides distinct interfaces for **Users** (passengers) and **Captains** (drivers), featuring real-time location tracking, ride matching, and seamless state management.

## 🚀 Features

### for Users
- **Secure Authentication**: Signup, Login, and Logout functionality.
- **Ride Booking**: diverse vehicle selection, fare estimation, and easy ride requests.
- **Real-Time Tracking**: view driver location and ride status in real-time.
- **Ride History/Status**: Track current ride progress (`Riding` screen).

### for Captains (Drivers)
- **Captain Dashboard**: Manage availability and view ride requests.
- **Ride Management**: Accept/Decline rides and navigation assistance.
- **Earnings & Stats**: (Future scope/Mocked) View daily earnings and trip details.

### Shared Features
- **Responsive Design**: Optimized for mobile and desktop views using **TailwindCSS**.
- **Smooth Animations**: Enhanced UI interactions powered by **GSAP**.
- **Interactive Maps**: Integrated Google Maps for location selection and tracking.

## 🛠️ Tech Stack

- **Framework**: [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Styling**: [TailwindCSS](https://tailwindcss.com/)
- **Routing**: [React Router DOM](https://reactrouter.com/)
- **State Management**: React Context API
- **Maps**: [@react-google-maps/api](https://www.npmjs.com/package/@react-google-maps/api)
- **Animations**: [GSAP](https://gsap.com/)
- **HTTP Client**: [Axios](https://axios-http.com/)
- **Real-time Communication**: [Socket.io-client](https://socket.io/)
- **Icons**: [Remix Icon](https://remixicon.com/)

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ride-booking-frontend.git
   cd ride-booking-frontend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   Create a `.env` file in the root directory and add the following keys:
   ```env
   VITE_BASE_URL=http://localhost:4000
   VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   ```

4. **Run Development Server**
   ```bash
   npm run dev
   ```
   The app will typically run at `http://localhost:5173`.

## 📂 Project Structure

```
src/
├── components/        # Reusable UI components (Buttons, Inputs, Modals)
├── context/           # Context providers for User, Captain, and Socket
├── pages/             # Main application pages
│   ├── Start.jsx      # Landing/Welcome screen
│   ├── Home.jsx       # User dashboard
│   ├── CaptainHome.jsx # Driver dashboard
│   ├── UserLogin.jsx  # Authentication pages
│   ├── Riding.jsx     # Active ride screen
│   └── ...
├── assets/            # Static assets (images, fonts)
└── App.jsx            # Main app component & Route definitions
```

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.
