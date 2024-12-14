# Fast-React-Pizza-Co

Fast React Pizza Co. is a Redux project where users can order pizzas without the need for authentication.

You can view the project live [here](https://fast-order-react-pizza.netlify.app/).

---

## Table of Contents

1. [Project Requirements from the Business](#project-requirements-from-the-business)
2. [Getting Started](#getting-started)
3. [References](#references)

---

## Project Requirements from the Business

This is a very simple pizza ordering application with the following requirements:

- Users can order one or more pizzas from a menu.
- No user accounts or login required: users input their name before using the app.
- The pizza menu can change dynamically and should be loaded from an API.
- Users can add multiple pizzas to their cart before ordering.
- Ordering requires only the user’s name, phone number, and address.
- GPS location should be provided if possible to make the delivery easier.
- Users can mark their order as "priority" for an additional 20% of the cart price.
- Orders are made by sending a POST request with the order data (user data + selected pizzas) to the API.
- Payments are made on delivery, so no payment processing is necessary in the app.
- Each order will receive a unique ID, which will be displayed so users can look up their order based on the ID.
- Users can mark their order as "priority" even after the order has been placed.

---

## Technologies

- **React**: For building the user interface.
- **Tailwind CSS**: For styling the app.
- **React Router**: For navigating between pages.
- **Redux**: For state management across the app.

---

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/Fast-React-Pizza.git
   ```
