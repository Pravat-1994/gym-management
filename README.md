# FitZone Gym Management System

A full-featured gym management web application built with HTML, CSS, and JavaScript. This application provides a comprehensive solution for gym members to manage their memberships, track workouts, book classes, and interact with trainers.

## Features

### 🏠 Home Page
- Modern hero section with call-to-action buttons
- Feature highlights showcasing gym amenities
- Service overview with visual icons
- Responsive navigation menu

### 💳 Membership Management
- Three membership tiers: Basic, Premium, and Elite
- Online membership registration
- Member dashboard with membership details
- Membership status tracking
- LocalStorage-based data persistence

### 💪 Workout Tracking
- Pre-built workout plans (Strength, Cardio, HIIT, Flexibility)
- Custom exercise logging
- Daily workout tracker
- Weekly progress statistics
- Exercise history management

### 📅 Class Schedule & Booking
- Weekly class schedule view
- Interactive calendar interface
- Class booking system
- Instructor information
- Booking management (view and cancel bookings)

### 👥 Trainers
- Trainer profiles with specializations
- Certification information
- Book personal training sessions
- Contact trainers directly

### 📞 Contact & Support
- Contact form with multiple inquiry types
- Gym location and hours
- Social media links
- Direct contact information

## Technology Stack

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with animations and responsive design
- **JavaScript (Vanilla)** - Interactive functionality and data management
- **Font Awesome** - Icons and visual elements
- **LocalStorage API** - Client-side data persistence

## File Structure

```
gym-management/
├── index.html              # Home page
├── membership.html         # Membership plans and registration
├── workouts.html           # Workout plans and tracking
├── schedule.html           # Class schedule and booking
├── trainers.html           # Trainer profiles
├── contact.html            # Contact form and information
├── css/
│   ├── style.css          # Main stylesheet
│   └── responsive.css     # Responsive design styles
├── js/
│   ├── main.js            # Common functionality
│   ├── membership.js      # Membership management
│   ├── workouts.js        # Workout tracking
│   └── schedule.js       # Class scheduling and booking
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. For development, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

### Usage

1. **Browse the Home Page**: Explore gym features and services
2. **Sign Up for Membership**: Choose a plan and complete registration
3. **Track Workouts**: Add exercises or select from pre-built plans
4. **Book Classes**: View schedule and book fitness classes
5. **Meet Trainers**: Browse trainer profiles and book sessions
6. **Contact Support**: Use the contact form for inquiries

## Features in Detail

### Membership System
- Three membership tiers with different features
- Form validation and error handling
- Persistent storage using LocalStorage
- Member dashboard with quick actions

### Workout Tracker
- Filter workouts by type (Strength, Cardio, HIIT, Flexibility)
- Add custom exercises with sets, reps, and duration
- Track daily workouts
- View weekly progress statistics
- Remove completed workouts

### Class Booking
- Weekly calendar view
- Navigate between weeks
- Book classes with member information
- View all bookings in one place
- Cancel upcoming bookings

### Data Persistence
All user data is stored locally using the browser's LocalStorage API:
- Membership information
- Workout logs
- Class bookings

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Responsive Design

The application is fully responsive and optimized for:
- Desktop computers (1200px+)
- Tablets (768px - 1199px)
- Mobile devices (320px - 767px)

## Future Enhancements

Potential features for future development:
- Backend integration for data persistence
- User authentication system
- Payment processing for memberships
- Email notifications
- Mobile app version
- Social features and community
- Nutrition tracking
- Progress photos and measurements

## Contributing

This is a demonstration project. Feel free to fork and modify for your own use.

## License

This project is open source and available for educational purposes.

## Contact

For questions or support, please use the contact form in the application or reach out through the provided contact information.

---

**Note**: This is a frontend-only application. All data is stored locally in the browser. For production use, integrate with a backend server and database.
