👉 Live demo URL https://birtukan178.github.io/Chuks-kitchen-app-final/


👉 Project Overview

     ✓ Chuks Kitchen is a modern frontend web application for food ordering.
     ✓ The platform allows users to:
         - Browse popular dishes
         - Search for meals
         - Explore chef’s specials
         - Add items to cart
         - Navigate between pages (Home, Explore, My Orders,Account,login/signin,create account,order summary,delivery,payment)
     ✓ The goal of this project is to create a responsive, user-friendly frontend interface with a focus on user experience and smooth navigation.

👉 Tech Stack Used

     ✓ React.js
         - Built using React (Functional Components)
         - Used React Hooks (useState)
         - Used useNavigate from React Router for navigation
         - Component-based architecture for reusability
     ✓ React Router
         - Used for page navigation (It allows navigation without page reloads.), Implemented routing between:
             1. Onboarding page to signin via signin button, to home page via learn more button and to signup page via start your order button.
             2. Home to explore via discover what's new button.
             3. My order to order summary page via view order summary button.
             4. Add more link on my order page also navigate to explore page .
             5. Order summary page to Delivery page via delivery button and to payment page via pickup button.
             6. signin page to signup page via create new account link.
             7. signup page to signin page via signin link.
             8. back to home button both on signin and signup page also navigate to home page.
             9. Explore and home page add to cart button and icon also add cart items on my order page.
     ✓ CSS
         - Custom CSS for styling
         - Responsive design for mobile and desktop
         - Flexbox and Grid for layout structure
         - Smooth transitions and hover effects
     ✓ React Icons
         - Used for UI icons like search and arrows

👉 Features Implemented

     ✓ Responsive design (mobile & desktop)
     ✓ Search foods on home page
     ✓ filter cards/foods based on their category on explore page
     ✓ Add to cart logic assist to render orders on my order page
     ✓ Scroll-to-top button
     
👉 Design interpretation

     ✓ The Figma design was translated into a responsive React frontend using reusable components, CSS flex and grid for layout, and React Router for navigation. 
     ✓ Some assumptions were made for spacing and hover states. A “Back to Home” button was added on the Sign In and Sign Up pages to improve user experience. On the My Order page, a “View Order Summary” button and a total amount summary were added. Additionally, an optional search feature was included on the Explore page to help users find food items more easily.
     
👉 Limitations & Improvements

     ✓ The “View More” link does not yet have functional logic.
     ✓ A Contact page was not provided in the Figma design.
     ✓ The desktop layout for the Sign Up page was not included, so assumptions were made based on the Sign Up design.
     ✓ The cart summary is not yet linked to a real payment system to transfer the total amount and others not included designs.
     ✓ After deployment, the app behave slightly different in the browser compared to when opened locally.
     
So,I plan to improve the app later by adding missing functionality and implementing pages not included in my code.

