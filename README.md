# Passport-google-oauth20
1.  **Set Up Google Developer Console:**
    
    -   Create a new project in the Google Developer Console.
    -   Enable the Google+ API for your project.
    -   Configure the OAuth consent screen with necessary details.
2.  **Create OAuth Credentials:**
    
    -   Generate OAuth client credentials (Client ID and Client Secret) in the Google Developer Console.
    -   Define the authorized redirect URI where Google will send the user after successful authentication.
3.  **Initialize Your Node.js Project:**
    
    -   Create a new Node.js project or use an existing one.
    -   Install the necessary packages: `express`, `passport`, `passport-google-oauth20`, etc.
4.  **Configure Passport with Google OAuth Strategy:**
    
    -   Set up Passport.js and configure the Google OAuth strategy using the client credentials and redirect URI.
    -   Define a callback function to handle the user profile data after successful authentication.
5.  **Initialize Passport and Set Up Routes:**
    
    -   Initialize Passport in your application.
    -   Set up routes for initiating the Google OAuth authentication process (`/auth/google`) and handling the callback (`/auth/google/callback`).
6.  **Protect Routes:**
    
    -   Implement middleware to protect routes that require authentication.
    -   For example, create a middleware function (`ensureAuthenticated`) to check if the user is authenticated before allowing access to certain routes.
7.  **User Sessions and Database Integration:**
    
    -   Implement user session management to keep track of authenticated users.
    -   Optionally, integrate a database to store user information for persistent authentication across sessions.
8.  **Start Your Server:**
    
    -   Start your Node.js server to listen for incoming requests.
    -   Visit the authentication route (e.g., `/auth/google`) to initiate the Google OAuth process.
9.  **Handle Authentication Callback:**
    
    -   After successful authentication, handle the callback (`/auth/google/callback`) to process the user profile data and perform any necessary actions.
10.  **Secure Your Application:**
    
    -   Implement security best practices, such as using HTTPS, securing sensitive information, and validating user input.

## SETUP
Run the following commands to setup the tool :
```
git clone https://github.com/AshajanetR/passport-google-oauth20.git
```
```
npm install --y
```
```
node app6.js
```
