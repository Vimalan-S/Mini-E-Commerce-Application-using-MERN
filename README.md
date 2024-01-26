# ECommerce-Management-System---RESTful-API-with-Node.js-and-MongoDB

# Control Flow
# Server Initialization:
server.js creates an HTTP server.
Express application is integrated into the server.

# Express Application Setup:
app.js initializes the Express application.
Middleware (logging, body parsing, CORS) is configured.
MongoDB connection is established.
Routes are defined for user, product, and order actions.

# Routing:
Requests are directed to the appropriate route handlers based on the URL path.
Middleware functions are executed before reaching route handlers for tasks like authentication.

# User Actions:
Routes in routes/user.js handle user-related actions.
Corresponding functions in controllers/user.js interact with the User model for database operations.

# Product Actions:
Routes in routes/products.js handle product-related actions.
Corresponding functions in controllers/products.js interact with the Product model for database operations.

# Order Actions:
Routes in routes/orders.js handle order-related actions.
Corresponding functions in controllers/orders.js interact with the Order model for database operations.

# Middleware Execution:
check-auth.js middleware is executed to verify user authentication.
Other middleware functions in routes/products.js handle file uploads using multer.

# Model Operations:
User, Product, and Order models are responsible for CRUD operations on the MongoDB database.
