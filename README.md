# GDocsClone

GDocsClone is a web-based application that emulates the core functionalities of Google Docs. Built using ASP.NET Core MVC, it offers a seamless user experience for document creation, editing, and management.

## Features

* **User Authentication**: Secure login and registration system.
* **Document Management**: Create, edit, and delete documents.
* **Rich Text Editor**: Format text with various styles and options.
* **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

* **Backend**: ASP.NET Core MVC
* **Frontend**: HTML, CSS, JavaScript
* **Database**: SQL Server (LocalDB)
* **Authentication**: ASP.NET Core Identity

## Setup Instructions

### Prerequisites

Ensure you have the following installed:

* [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)
* [SQL Server Express or LocalDB](https://docs.microsoft.com/en-us/sql/ssdt/how-to-install-and-use-sql-server-data-tools)
* [Visual Studio 2022 or later](https://visualstudio.microsoft.com/)

### Installation Steps

1. Clone the repository:

```bash
git clone https://github.com/Devansh-Rawat-gamedev/GDocsClone.git
cd GDocsClone
```

2. Restore the dependencies:

```bash
dotnet restore
```

3. Apply the database migrations:

```bash
dotnet ef database update
```

4. Run the application:

```bash
dotnet run
```

5. Open your browser and navigate to `https://localhost:5001` to access the application.

## Project Structure

* **TextEditor**: Contains the main application logic, views, and controllers.
* **TextEditor.sln**: The solution file for the project.
* **.gitignore**: Specifies which files and directories to ignore in version control.
* **.gitattributes**: Defines attributes for pathnames in the repository.

## Testing

To run tests, use the following command:

```bash
dotnet test
```
