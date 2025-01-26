# CSC293 Project: Online Store

## Project Details
- **Matric No:** 236356
- **Name:** Omotosho Bukola Dorcas

## Project Description
This project involves creating an online store using various technologies including external JavaScript, Laravel, and both internal and external CSS. The goal is to develop a fully functional e-commerce platform as part of the CSC293 course requirements.

## Technologies Used
- **Laravel:** A PHP framework used for the backend development.
- **External JavaScript:** For adding dynamic functionalities to the website.
- **Internal and External CSS:** For styling the web pages.

## Features
- User authentication and authorization
- Product listing and categorization
- Shopping cart functionality
- Order processing and management
- Responsive design

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Bukola0205/236356_Bubufits.git
    ```
2. Navigate to the project directory:
    ```bash
    cd 236356_Bubufits
    ```
3. Install dependencies:
    ```bash
    composer install
    ```
4. Set up the environment file:
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```
5. Run the migrations:
    ```bash
    php artisan migrate
    ```

## Usage
Start the development server:
```bash
php artisan serve
```
Open your browser and navigate to `http://localhost:8000` to view the application.

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.