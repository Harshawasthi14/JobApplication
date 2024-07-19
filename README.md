# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Create an .env file in server.js and add these parameters in it.
MONGO_URI=your_mongodb_uri, 
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name, 
CLOUDINARY_API_KEY=your_cloudinary_api_key, 
CLOUDINARY_API_SECRET=your_cloudinary_api_secret, 
PORT=your_port, 
JWT_SECRET=your_jwt_secret,


# run the development server
npm run dev

