Project Planning and Initial Approach

The project began with identifying the core objective: building an AI-powered web application capable of detecting pneumonia from chest X-ray images while maintaining a scalable and structured full-stack architecture.
I divided the project into the following phases:
Research and dataset understanding
Model development and evaluation
Backend integration using Django
Database schema design
Dashboard and analytics implementation
Testing and optimization
Instead of building everything at once, I followed an incremental approach — first validating the deep learning model independently, then integrating it into the web application layer.
This separation helped reduce complexity and made debugging easier.

Why Django?
Django was chosen for several reasons:
Built-in authentication system
ORM for simplified database management
Secure file handling for image uploads
Scalability and modular app structure
Rapid development capability
Since the application required both authentication and structured data management, Django provided a stable and secure backend framework with minimal setup complexity.
Its built-in security features (CSRF protection, secure session handling) were especially important because the application handles medical data.

Why Convolutional Neural Networks (CNN)?
CNNs are the standard architecture for image classification tasks.
They are particularly effective for:
Extracting spatial features
Identifying patterns in medical imaging
Reducing dimensionality while preserving important image structures
For this project, I experimented with:
A basic CNN architecture
A deeper CNN with dropout for regularization
ResNet-inspired architecture for deeper feature learning
MobileNet-inspired lightweight architecture for efficiency
This comparative approach helped evaluate performance trade-offs between accuracy and computational efficiency.

