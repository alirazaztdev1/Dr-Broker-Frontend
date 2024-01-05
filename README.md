# Dr-Broker-Frontend

Dr-Broker-Frontend is a frontend application that provides a user-friendly interface for doctors and patients to interact with the Dr-Broker-Backend server. It is designed to seamlessly integrate with the backend and provide a comprehensive healthcare management system for doctors and patients.

## Features

### Doctor Dashboard
- View and manage patient appointments
- Access patient medical records and treatment history
- Update doctor profile information
- Prescribe medications and treatments

### Patient Dashboard
- Book appointments with doctors
- View and manage upcoming and past appointments
- Access personal medical records and treatment history
- Update patient profile information

### Appointment Management
- Schedule appointments with preferred doctors
- Receive notifications and reminders for upcoming appointments
- Cancel or reschedule appointments as needed
- View appointment history and details

### Treatment Management
- View and track patient's medical history and treatment plans
- Monitor progress and update treatment information
- Record and manage prescribed medications and dosages
- Receive reminders for medication schedules

### Medicine Management
- View prescribed medications and dosage information
- Receive reminders for medication schedules and refills
- Manage medication inventory and request refills
- Integration with pharmacy systems for medication delivery

## Technologies Used

- React: A JavaScript library for building user interfaces
- Redux: A predictable state container for managing application state
- Tailwind CSS: A utility-first CSS framework for easy and responsive styling
- Axios: A promise-based HTTP client for making API requests
- React Router: A routing library for managing navigation in a React application
- Formik: A form library for building robust and flexible forms
- Yup: A library for schema validation
- Calendar integration: Integration with calendar APIs for appointment scheduling
- Pharmacy system integration: Integration with pharmacy systems for medication delivery

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- Dr-Broker-Backend server running

### Installation

1. Clone the repository:

   ````shell
   git clone  https://github.com/alirazaztdev1/Dr-Broker-Frontend
   ```

2. Install dependencies:

   ````shell
   cd dr-broker-frontend
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the root directory and add the following environment variables:

   ````plaintext
   REACT_APP_API_BASE_URL=http://localhost:3000
   ```

   Replace `http://localhost:3000` with the base URL of your Dr-Broker-Backend server.

4. Run the application:

   ````shell
   npm start
   ```

   The application will be accessible at [http://localhost:3000](http://localhost:3000).

## Usage

Once the application is up and running, you can access the doctor or patient dashboard based on your role. Use the provided UI to manage appointments, treatments, and medications according to your needs.

The frontend application communicates with the Dr-Broker-Backend server through API requests, so make sure the backend server is running and accessible.

## Contributing

Contributions to Dr-Broker-Frontend are welcome! If you find any issues or want to add new features, feel free to submit a pull request. Please follow the existing code style and conventions.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use it for your own projects.

## Acknowledgements

- [React](https://reactjs.org)
- [Redux](https://redux.js.org)
- [Tailwind CSS](https://tailwindcss.com)
- [Axios](https://axios-http.com)
- [React Router](https://reactrouter.com)
- [Formik](https://formik.org)
- [Yup](https://github.com/jquense/yup)
- Calendar APIs (e.g., Google Calendar, Microsoft Outlook)
- Pharmacy system APIs (e.g., CVS, Walgreens)
- Any other libraries or resources used in your implementation

## Contact

If you have any questions or suggestions regarding Dr-Broker-Frontend, please feel free to reach out to us:

- Email: [contact@drbroker.com](mailto:contact@drbroker.com)
- Website: [https://drbroker.com](https://drbroker.com)
- GitHub: [https://github.com/alirazaztdev1](https://github.com/alirazaztdev1)
- 
