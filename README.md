# TMK PARKING APP (React)

![TMK Parking App Logo](app_logo.png)

TMK Parking App is a web application built using React that aims to simplify parking management for both parking lot owners and customers. The app provides an easy-to-use interface for users to find available parking spots, book them in advance, and manage their parking reservations.

## Features

- Booking System: Customers can search for available parking spots, book them for specific dates and times, and make payments.
- User Dashboard: Each user has a personalized dashboard that displays their bookings, reservations, and account information.
- Ratings and Reviews: Customers can leave ratings and reviews for parking spots they have used, helping others make informed decisions.
- Admin Panel: An admin panel allows administrators to manage users, parking spots, and reservations effectively.
- Notifications: Users receive notifications for booking confirmations, cancellations, and other important updates.

## Getting Started

These instructions will help you set up the TMK Parking App on your local machine for development and testing purposes.

### Prerequisites

- Node.js (version 20.0.4)
- npm (version 9.5.1)

### Installation

1. Clone the repository: `git clone https://github.com/Trevor-Kayeyia-Madara/t-m-k-parking-react.git`
2. Change to the app's directory: `cd tmk-parking-app-react`
3. Install the dependencies: `npm install`
4. Start the development server: `npm start`
5. In package.json file at start, add the following: `set PORT=4000 && react-scripts-start`

The app should now be running locally at `http://localhost:4000`.

### Configuration

Before running the app, ensure that you have set up the required environment variables. Check the `.env.example` file for the list of variables needed and create a `.env` file in the root directory with the appropriate values.

## Contributing

We welcome contributions to improve the TMK Parking App. If you find any issues or have suggestions, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m "Add your commit message here"`.
4. Push the changes to your forked repository: `git push origin feature/your-feature-name`.
5. Open a pull request on the main repository and describe your changes in detail.

We will review your contribution and merge it if it meets our guidelines and aligns with the project's objectives.

Thank you for contributing to the TMK Parking App!

## Acknowledgments

We would like to extend our gratitude to the following individuals and projects for their contributions and inspiration:

- Hat tip to anyone whose code was used as a reference or inspiration.
- Special thanks to the TMK Parking App development team for their hard work and dedication in creating this application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please contact the development team at <tmk-parking-app@example.com>.

Happy parking with TMK Parking App!

### Testing

To run the automated tests, execute the following command:

```bash
npm test
