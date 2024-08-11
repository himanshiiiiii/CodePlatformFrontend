# Clone the repository:
git clone https://github.com/himanshiiiiii/CodePlatformFrontend.git

# Install packages
npm install

# Run the application 
npm run start

# Environment Configuration
The application uses environment files to manage API paths and other configurations:

environment.ts: Used during development. Set the API_PATH to your development server.
environment.prod.ts: Used during production. Set the API_PATH to your production server.

# Backend code is deployed on
API_PATH: 'https://codeplatform-backend-1.onrender.com',

# src/app: Contains all the Angular components, services, and modules.
components: UI components like Navbar, Editor, etc.

# src/environments: Contains all the environments related vairable.
environments: Configuration files for different environments (development and production)

# src/assets: Contains all the static assets used.
