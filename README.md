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
          Used for page navigation. It allows navigation between pages without reloading the browser.
          Routing has been implemented for the following pages:

         - Onboarding Page
               1. Navigate to Sign In via the Sign In button.
               2. Navigate to Home via the Learn More button.
               3. Navigate to Sign Up via the Start Your Order button.

         - Home Page
               1. Navigate to the Explore page via the Discover What's New button.

         - My Order Page
               1. Navigate to the Order Summary page via the View Order Summary button.
               2. The Add More link navigates to the Explore page.

         - Order Summary Page
               1. Navigate to the Delivery page via the Delivery button.
               2. Navigate to the Payment page via the Pickup button.

         - Authentication Pages
               1. Sign In → Sign Up via the Create New Account link.
               2. Sign Up → Sign In via the Sign In link.
               3. Back to Home button on both pages navigates to the Home page.

          - Cart Functionality
               1. The Add to Cart button on both the Home and Explore pages adds items to the cart.
               2. The cart icon also adds items and displays them on the My Order page.
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

