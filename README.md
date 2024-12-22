# Paws On Tour - TXST Campus Guide

A dynamic campus tour guide application built with Vue.js and interactive mapping features. This single-page application (SPA) showcases 18 key locations across Texas State University's campus, featuring an interactive map, image carousels, and detailed location information.

## Features
- Interactive campus map with walking route
- Dynamic search and filtering system
- Grid and list view toggle
- Location-based sorting options
- Image carousels for multiple location photos
- High contrast mode toggle
- Mobile-responsive design
- Smooth navigation animations
- Turn-by-turn walking directions

## Built With
- Vue.js 2
- Vue Router
- Leaflet.js
- Bootstrap 5.3
- CSS3 Custom Properties
- Google Fonts (Montserrat, Roboto, etc.)

## Project Structure
The application includes several main components:
- Interactive navbar with theme toggle
- Search and sort functionality
- Location grid/list views
- Detailed location pages
- Interactive map with numbered markers
- Navigation system between locations

## Design System
Core styles can be customized through CSS variables:
```css
:root {
  --primary: #501214;
  --secondary: #6a5638;
  --accent: #d2b650;
  --background: #f8f9fa;
  --text: #2d3748;
  --light: #f4f1ed;
}
```

## Responsive Design
The website is fully responsive across:
- Mobile: < 768px (simplified navigation)
- Tablet: 768px and up
- Desktop: Full features and animations

## Setup
1. Clone the repository
   ```bash
   git clone https://github.com/thesamc/PawsOnTour.git
   ```
2. Open index.html in your browser

No build process required - this is a static website.

## Future Updates
Planning to add:
- Real-time bus tracking
- User location tracking
- Additional campus locations
- Virtual tour functionality
- Photo gallery expansion
- User reviews and tips

## Contact
- GitHub: [@thesamc](https://github.com/thesamc)
- LinkedIn: [Samuel Chutter](https://www.linkedin.com/in/samuel-chutter/)
- Email: samcwebdev@gmail.com

## License
This project is open source and available under the MIT License.
