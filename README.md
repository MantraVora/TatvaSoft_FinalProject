
# Virtual Community Support

## Introduction

The Virtual Community Support project is a web application designed for efficient user management within a virtual community. It uses an Angular frontend and an ASP.NET Core backend with a PostgreSQL database. Administrators can easily add, view, and remove users, making community support streamlined and effective.

## Tech Stack

- **Frontend:**
  - **Angular**: A TypeScript-based open-source web application framework used for building dynamic and responsive user interfaces.
- **Backend:**
  - **ASP.NET Core**: A cross-platform, high-performance framework for building modern, cloud-based, and internet-connected applications.
- **Database:**
  - **PostgreSQL**: An open-source relational database management system known for its robustness, extensibility, and SQL compliance.
- **Development Tools:**
  - **VS Code**: A lightweight but powerful source code editor used for Angular development.
  - **Visual Studio**: An integrated development environment (IDE) from Microsoft used for .NET Core development.
  - **pgAdmin**: A management tool for PostgreSQL, providing a graphical interface for database management and query execution.

## Features

- Add new users
- View user list
- Delete users
- Responsive and user-friendly UI

## Setup and Installation

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Angular CLI](https://cli.angular.io/)
- [Visual Studio](https://visualstudio.microsoft.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [pgAdmin](https://www.pgadmin.org/)

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/virtual-community-support.git
   cd virtual-community-support/backend
   ```

2. Open the project in Visual Studio.

3. Install required packages:
   ```powershell
   Install-Package Npgsql.EntityFrameworkCore.PostgreSQL
   ```

4. Update `appsettings.json` with your PostgreSQL connection string:
   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Host=localhost;Database=virtual_community_support;Username=postgres;Password=yourpassword"
   }
   ```

5. Run the following commands in the Package Manager Console to create the database and apply migrations:
   ```powershell
   Add-Migration InitialCreate
   Update-Database
   ```

6. Build and run the project.

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd virtual-community-support/frontend
   ```

2. Install Angular CLI if not already installed:
   ```bash
   npm install -g @angular/cli
   ```

3. Install project dependencies:
   ```bash
   npm install
   ```

4. Run the Angular development server:
   ```bash
   ng serve
   ```

5. Open your browser and navigate to `http://localhost:4200`.

## Usage

- **Add User:** Fill out the form with user details and click "Add".
- **View Users:** The user list is displayed in a table.
- **Delete User:** Click the "Delete" button next to a user to remove them.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Contact

For questions or issues, please contact mantradvora652@gmail.com

