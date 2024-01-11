
# EasyBreezyBlogs - Comprehensive Blog Application

Welcome to EasyBreezyBlogs, a feature-rich blog application with a robust REST API using Laravel Sanctum for authentication.


## Demo

See the complete view of this project: [Visit Here](https://easybreezyblogs.dreamersdesire.xyz)


## API Reference (Blog Post)

#### Get all posts

```
  GET /api/post/all
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `authorized_token` | `string` | **Required**. Your PERSONAL_ACCESS_TOKEN |

#### Get single post

```
  GET /api/post/view
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `authorized_token`      | `string` | **Required**. Your PERSONAL_ACCESS_TOKEN |
| `pid`      | `string` | **Required**. UUID of the fetched post |



## Author

- [@jahid404](https://www.github.com/jahid404)


## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://raw.githubusercontent.com/jahid404/EasyBreezyBlogs/main/LICENSE)



## Installation and Usage

### Installation
- Clone the repository into EasyBreezyBlogs folder.
```bash
  git clone https://github.com/jahid404/EasyBreezyBlogs.git EasyBreezyBlogs
```

- Install Composer dependencies.
```composer
composer install
```

- Install npm dependencies.
```composer
npm install
```

- Create a copy of your .env file.
```bash
cp .env.example .env
```

- Generate an app encryption key.
```php
php artisan key:generate
```

- Create an empty database for our application with named *'easybreezyblogs'*

In the .env file fill in the DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, and DB_PASSWORD options to match the credentials of the database you just created. This will allow us to run migrations and seed the database in the next step.

- Migrate the database
```php
php artisan migrate
```

- Run the project
```php
php artisan serve
```

That's all done!

## Credentials
- **Admin:**
  - Email: admin@easybreezyblogs.com
  - Password: password
- **User:**
  - Email: user@easybreezyblogs.com
  - Password: password


## Features

### Admin

- **Authentication:**
  - Admins can securely log in to their accounts using their unique credentials.

- **User Management:**
  - Admins have the authority to manage user accounts, including creating, editing, and deleting user profiles.

- **Post Management:**
  - Admins can manage all blog posts on the platform, allowing them to create, edit, and delete posts regardless of the author.

- **Create, Edit, Delete Own Posts:**
  - Admins also possess the capability to create, edit, and delete their own blog posts.

- **View All Posts:**
  - Admins can view all blog posts on the platform, providing a comprehensive overview of the content.

- **Laravel Sanctum API Access:**
  - Admins have access to the Laravel Sanctum API with extended capabilities for managing users and posts.

- **Dashboard Insights:**
  - Admins are equipped with a dashboard that provides insights into user activities, post analytics, and overall platform usage.

- **Role-Based Permissions:**
  - The admin role is equipped with role-based permissions, ensuring a secure and controlled environment.

- **Audit Trail:**
  - Changes made by admins, such as user modifications or post management, are logged in an audit trail for accountability and traceability.

- **Security Measures:**
  - Special security measures are in place for admin accounts to protect sensitive information and maintain the integrity of the platform.


## Features

### User

- **Authentication:**
  - Users can securely log in to their accounts using their unique credentials.

- **Registration:**
  - New users can register for an account with a unique username and email.

- **Create, Edit, Delete Own Posts:**
  - Authenticated users have the ability to create, edit, and delete their own blog posts.

- **View All Posts:**
  - Users can view all blog posts on the platform, including those created by other users.

- **Laravel Sanctum API Access:**
  - Authenticated users have access to the Laravel Sanctum API for secure authentication.

- **Dashboard:**
  - Users have access to a personalized dashboard displaying their posts, activities, and relevant information.

- **Profile Management:**
  - Users can manage their profile information, including updating their username, password, and other details. *(NOTE: This option is currently Unavailable)*

- **Responsive Design:**
  - The application features a responsive design, ensuring a seamless experience across different devices.

- **Commenting System:**
  - Users can engage with other users by commenting on posts, fostering a sense of community. *(NOTE: This option is currently Unavailable)*


## 🤓 About Me
I'm a web developer with a focus on Laravel. My expertise lies in developing robust web applications, and I've actively contributed to various PHP-Laravel projects in the past. With a passion for problem-solving and a keen interest in crafting elegant solutions, I enjoy the challenges that web development brings.

If you're interested in connecting, discussing web development, or exploring potential collaborations, feel free to reach out. I'm open to new opportunities and always excited about creating innovative projects.

Let's build something amazing together!


## Support

If you have any feedback, please reach out to me at jsjahidmini@gmail.com


## Screenshots
**Frontend**

![App Screenshot](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhj8bEsgcaumgYaRaE3z1xr6FYRPcvtwEsg3fKqiF6tB6WkOXLiA1K8SIMAO5n8IljmjKgSM2zYj4Jz8rOjDgouXVm1nOUpKwWbORW9XnNB6rlqIJSx8l1YL45GQ8MaYd5tvbT5za9EnATc4sjzwOEjZOi4gfd_ERjfwHywweIFHVPSQVNICpBheT7WkN4/s720)

![App Screenshot](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiRxKmbTs7Q9VZ6yO78G2yNhyvlRpYo7BDllZUlUDOVDWCEtLTnlUU9mTg15G_pkeY5Ju-buXVgSTp3WmQBu99Ld0qXBDYJIMH6IS0UlZ-U8dTc_n-NpnUpvToDFb1qf1TWUJBznpx9Z3b-xfTvOMBiIqCGkMz2845VygGPJUjhGXzVeyu9cH5XO0RFYFI/s720)

![App Screenshot](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhDp7b_1kJI-ALmJ4WlHUvXXoHeNZvS9IjgSLXL4bLAPziDNnfKJSJtiXarcDM3RLZBNPFdNaPL4itHTRu2P_8MNZSX0GQbnjZXn-uQgjbjgKq39i2D3Opmw-jeI4w9EMlH3UCwj6LzzXygjMdfDbKPp582GARPs6z_Bi7P-1npG1ceAsBbZJwmBNL-1MI/s720)


**Backend**

![App Screenshot](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjXMe_IDobV4h2kH2YpIY1-gKtyfi28_Uw3rQZ1rBQkcsAcdaooUVcemzfrwwVuruN7s-dqSandAZqT0E0WbNdGCbBjAMaJlZ_tfYKjyLz3juyFTpudHBmjrwAc-Fupm1PGz1Ogqv8zCXInZVwftocNU1KIvSgeKVc2HLLAp9pHR4WDYJXvyaeRX3O_5eM/s720)

![App Screenshot](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhPQCrfN4kBeAi4C-UtdBTw1UQK_A_AL2dV_2oH8PSpR217ddBZJLLDXzKyCC09WbsNukZU-fOnB5RJtYQbcggW97b5WtAI3WT3nNsmtsfjn-3hrpGLc1LCnhjEdCr5igZI5UlCq6USBxi16f88IYMNFgWli3stU4V82Nxps4kPQ2n6l7fEI6AaFTA0cCo/s720)
