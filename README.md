# Isadora Nascimento

## Private Chef

The Chef Spirov website is a concept project created to demonstrate the design, structure, and functionality of a professional service website. The website is user-friendly designed to connect Chef Spirov with private clients, events and corporate business. 

The purpose is to present how a private chef could showcase skills, menu, and booking options through a clean, responsive, and visually appealing online presence. While the site content is inspired by real-world service scenario, is not connected to an actual business and is intended for portfolio and esucational purpose only.

This project focuses on:

- Presenting a strong value proposition.
- Organizing clear navigation for various client types.
- Demonstrating responsive design and custom styling.
- Guiding the user smoothly from interest to a booking inquiry.

## Business Goals

- Showcase chef skills, sample menus, and event experience.
- Attract multiple client types: private clients, event hosts and corporate clients.
- Get clients to book private chef services.
- Build credibility though photos, professional presentation and testimonials.

## User Goals

- Easily find a chef for a specific event or need.
- View pricing, availability, and menus.
- Get a quick response or book online.
- Feel confident that the chef is reliable, high-quality, and professional.

## Strategy

The goal of the private chef website is to create a professional, visually engaging, and user-friendly online platform that builds trust and drives bookings. The strategy focuses on presenting the chef’s brand, skills, and experience in a way that resonates with various client types, from private individuals to corporate clients and venue managers, while making the booking process seamless and intuitive.

## Scope

### Must Have 

- Homepage with a compelling value proposition and "Book Now" CTA
- Menu page with interactive sample menus and pricing packages
- Booking/inquiry form with calendar and service selection
- About page with chef bio, experience, and credentials
- Contact page with phone, email, and possibly WhatsApp integration

## Nice to Have 

- Client testimonials section
- Availability calendar or booking automation

## Structure

The user will visit the site because they are looking for a private chef for an event or personal service. The structure should guide them through:

1.	Value proposition – Clear statement of what the service offers (on homepage).
2.	Service offerings – Detailed menus with pricing.
3.	Chef credibility – Chef experience, bio and photos.
4.	Booking process – Simple and accessible booking enquiry and form submission.
5.	Contact and support – Social media, Email address and contact number.

Information Architecture:

- Homepage: Overview, booking CTA, intro to chef.
- About: Chef bio and service philosophy.
- Menu: Sample menus, dishes with pricing.
- Booking: Booking enquiry, form submission and contact info.
- Contact: Phone, Email and social meddia.

## Skeleton

Priority Content:

- High Priority (Top-level navigation + hero section):

1. Booking CTA
2. Menus
4. Contact options

- Medium Priority (secondary sections or deeper pages):

1. Chef’s bio

- Lower Priority (footer):

1. Blog, social links, privacy policy

Navigation:

1. Sticky top navigation bar with: Home | About | Menus | Book Now | Contact
2. Scrollable homepage with anchor links to each section.
3. Prominent “Book Now” buttons throughout.

## Surface

-	Color Palette: Neutral base (light ivory) + rich accent (sky blue).
-	Typography: Elegant serif for headings (Lora), clean sans-serif for body (Inter Tight).
-	Imagery: High-resolution food and chef photos.

-	Design Elements: 

1. Smooth animations (hover effects, fading transitions).
2. Subtle textures or overlays for elegance.
3. Icons for service features.


## User Stories

1.	Private Client (Host)

Description: Individuals or families hosting a private dinner or party at home or a rented space.

Needs: 

- Hire a private chef for a dinner, celebration, or event
- View available sample menus or customize one
- Understand pricing and booking process

User Stories:

- As a private client, I want to view sample menus so I can choose a menu that fits my event.
- As a private client, I want to check pricing and availability so I can book a chef confidently
- As a private client, I want to customize a menu, so the food matches my preferences and dietary needs


2.	Corporate Client 

Description: A business, gallery, or brand organizing an event (e.g., exhibition, product launch) and needs catering.

Needs:

- Find a professional chef to cater a formal/informal event
- Ensure branding alignment and presentation
- Request a quote or proposal

User Stories:

- As a gallery owner, I want to see the menus, so I know the chef can deliver high-end service
- As a corporate client, I want to get a quote for my event so I can plan the budget accordingly
- As a business, I want catering that aligns with my brand image to impress my guests

3.	Venue Manager 

Description: A venue that hosts weddings, parties, or corporate events and seeks a chef partner to provide in-house catering.

Needs:

- Review set menu options and pricing 
- Confirm capacity (number of guests)
- Build a long-term partnership

User Stories:

- As a venue manager, I want to view standard menus and pricing so I can offer them to my clients
- As a venue, I want to understand the chef’s service scope so I can determine if it fits our events
- As a venue, I want to partner with a reliable chef to offer catering packages to our clients

## Features

Responsive Navigation Bar – Fixed at the top of the page and fully responsive. Clicking a menu item smoothly scrolls to the corresponding section, while "Book Now" opens a dedicated booking page with an enquiry form. After submission, users are redirected to a success page confirming their booking request.

- Home Page: Image of Chef Spirov preparing a dish, paired with a short, engaging service message and a prominent CTA button inviting visitors to explore the menu. Image carousel showcasing the chef’s signature dishes.
- About Chef: High-quality portrait of the chef cooking, with an accompanying biography describing his expertise, training, and unique style.
- Menu: Interactive headers with hover effects for each menu category. Each section includes a dish image followed by a breakdown of the starter, main course, and dessert. A footer section displaying pricing details.
- Contact Section: Located in the footer with the chef’s contact details and social media links, making it easy for clients to connect.
- Booking (Book Now): Dedicated booking enquiry page featuring a form with fields for visitor details, and a message field where clients can specify order preferences or ask questions. A submit button sends the enquiry and redirects users to a success page confirming that their request has been received.

## Tecnologies Used

- HTML & CSS: Core programming languages used to structure and style the website.
- Bootstrap 5: Framework used to streamline layout development and ensure full responsiveness across devices.
- Font Awesome: Provides icons for improved visual design and user interaction.
- Google Fonts: Used to enhance typography with elegant and professional font choices.
- jQuery: Supports JavaScript functionality to ensure smooth interactions, including the automatic collapsing of the Bootstrap mobile navbar when navigating to in-page links.
- Images: All external images were generated using AI, except for the chef’s portrait, which is a real photograph.

## Testing

### Manual Testing

Testing of the home page. 

The image have loaded correctly and the buttom "explore menu" goes directly to the correct menu section. The carousel images have loaded correctly and the interactive carousel works. The menu section looks as expected and the hover effect works.

The responsive grid works in tablet and mobile screens 

### Automated testing with Lighthouse

### HTML and CSS validation

The code has been validate using the W3C tools:

[W3C Markup Validation - HTML] https://validator.w3.org/ 
[W3C CSS Validation] https://jigsaw.w3.org/css-validator/

## Deployment

This project is hosted on GitHub Pages, a free service that publishes websites directly from a GitHub repository.

Steps to deploy:

1. Open the repository for this project on GitHub.
2. Click the Settings tab at the top of the page.
3. From the left-hand menu, under Code and automation, select Pages.
    In the Build and deployment section:
    Source → Deploy from a branch
    Branch → main
    Folder → / (root)
4. Click Save.
5. Return to the Code tab and wait a few minutes while GitHub builds and publishes the site.
6. Once the process is complete, go to the Environments section on the right-hand side of the repository page.
7. Click github-pages, then select View deployment to open the live site.