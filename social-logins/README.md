
# Social Logins

This project provides social login functionality for Google, Facebook, and Twitter using Next.js. It's designed to be a straightforward implementation that can be easily integrated into any Next.js application.

## Features

- **Google Login**: Allow users to sign in with their Google accounts.
- **Facebook Login**: Enable Facebook login for users.
- **Twitter Login**: Authenticate users via their Twitter accounts.
- **Next.js Integration**: Seamless integration with Next.js, making it easy to include social logins in your existing or new projects.

## Getting Started

### Prerequisites

- **Node.js**: Make sure you have Node.js installed. You can download it [here](https://nodejs.org/).
- **Next.js**: This project uses Next.js. If you don't have it installed, you can install it globally by running:
  ```bash
  npm install -g next
  ```

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/social-logins.git
   ```

2. Navigate to the project directory:

   ```bash
   cd social-logins
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

### Configuration

To enable social logins, you'll need to configure OAuth credentials for Google, Facebook, and Twitter.

1. **Google OAuth**: 
   - Go to the [Google Developer Console](https://console.developers.google.com/).
   - Create a new project and set up OAuth 2.0 credentials.
   - Add your credentials to `.env.local` as follows:

   ```env
   GOOGLE_CLIENT_ID=your-google-client-id
   GOOGLE_CLIENT_SECRET=your-google-client-secret
   ```

2. **Facebook OAuth**: 
   - Go to the [Facebook Developers](https://developers.facebook.com/).
   - Create a new app and configure OAuth.
   - Add your credentials to `.env.local`:

   ```env
   FACEBOOK_APP_ID=your-facebook-app-id
   FACEBOOK_APP_SECRET=your-facebook-app-secret
   ```

3. **Twitter OAuth**: 
   - Visit the [Twitter Developer Portal](https://developer.twitter.com/).
   - Create a new project and set up OAuth credentials.
   - Add your credentials to `.env.local`:

   ```env
   TWITTER_CONSUMER_KEY=your-twitter-consumer-key
   TWITTER_CONSUMER_SECRET=your-twitter-consumer-secret
   ```

### Running the Project

To start the development server, run:

```bash
npm run dev
```

Your application will be available at `http://localhost:3000`.

### Deployment

To deploy your application, you can use platforms like Vercel, which has excellent support for Next.js projects. Simply connect your GitHub repository and follow the deployment instructions on Vercel's dashboard.

### Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

