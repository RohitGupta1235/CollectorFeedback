### Feedback-Collector-App

Welcome to Feedback-Collector-App, a full-stack application built to streamline the process of sending mass email surveys and gathering responses. 

#### Key Features

- **Google OAuth 2.0 Integration:** Securely log in using your Google account with Passport's authentication.
  
- **Stripe API for Payments:** Utilize credits for survey distribution; each $5 payment equals 5 credits, where one credit is required per survey sent.
  
- **Efficient Survey Management:** Manage and send surveys seamlessly, optimizing user engagement and feedback collection.

#### Technology Stack

**Client-Side (Front-end):**
- **React 16** for building responsive user interfaces.
- **Redux** for managing application state.
- **Reactstrap** for easy-to-use Bootstrap 4 components.
- **Axios** for handling asynchronous HTTP requests.
- **Redux Form** and **Redux Thunk** for form management and handling asynchronous actions.

**Server-Side (Back-end):**
- **Node.js** with **Express** for building robust server-side applications.
- **MongoDB with Mongoose** for database management and interaction.
- **Passport** with **Google OAuth 2.0** for secure user authentication.
- **Stripe** for handling payment transactions securely.
- **SendGrid** for reliable email delivery of surveys.
- **Lodash** for utility functions and simplifying complex operations.

#### Installation

To get started with Feedback-Collector-App, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd Feedback-Collector-App
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up API Keys:**
   - Ensure you have API keys for Stripe, Google OAuth 2.0, and SendGrid.
   - Add these keys to `config/dev.js` (make sure not to push them to a public repository).

4. **Run the Application:**
   ```bash
   cd server
   npm run dev
   ```


#### Screenshot
![1ssGit](https://github.com/RohitGupta1235/CollectorFeedback/assets/94480941/55cc63a8-777a-40e2-a32a-73e5811186ed)



 
