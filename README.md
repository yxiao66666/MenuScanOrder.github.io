# MenuScanOrder

## Overview
MenuScanOrder is a SaaS web application designed to streamline the process of ordering and order management for businesses in the hospitality industry. By digitizing menus and implementing QR code-based ordering, this system reduces labor hours, improves efficiency, and enhances the customer experience.

The application is built using the **CodeIgniter MVC framework**, ensuring a structured and maintainable codebase. **MySQL** is used for database management, with a focus on data security and integrity. While initially developed as a web-based platform, future iterations may include a native mobile application.

## Key Features
### 1. Digital Menu Creation
- Business owners can create and manage digital menus with categorized items and pricing.
- Customers can view menus independently without staff intervention.

### 2. QR Code Generation
- Unique QR codes are generated for each table in a business.
- Customers can scan the QR codes to access the menu on their mobile devices.

### 3. Seamless Ordering
- Customers can place orders directly through the platform.
- Reduces staff workload and improves service efficiency.

### 4. Order Management
- Staff can monitor and manage orders in real-time.
- Ensures smooth processing and timely delivery of orders.

## Technology Stack
- **Backend:** PHP (CodeIgniter MVC Framework)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** MySQL
- **QR Code Library:** EasyQRCodeJS

## Installation
### Prerequisites
Ensure you have the following installed on your system:
- PHP 7.4+
- MySQL 5.7+
- Apache/Nginx web server
- Composer

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yxiao66666/menuscanorder.git
   cd menuscanorder
   ```
2. Install dependencies:
   ```bash
   composer install
   ```
3. Set up the database:
   - Import the provided SQL file into MySQL.
   - Configure database settings in `application/config/database.php`.
4. Run the application:
   ```bash
   php -S localhost:8000
   ```
5. Access the application at `http://localhost:8000`.

## Project Timeline
This project follows a structured development timeline:
1. **Planning**: Research and feasibility study.
2. **Design**: UI/UX design and database structure.
3. **Development**: Backend, frontend, and database implementation.
4. **Testing**: User acceptance testing and bug fixes.
5. **Deployment**: Production release and maintenance.

## Future Enhancements
- Mobile app development (React Native)
- Integration with payment gateways
- Multi-language support

## License
This project is licensed under the MIT License.

## Contributors
- [yxiao66666](https://www.linkedin.com/in/yang~xiao/) 
