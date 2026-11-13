
<div align="center">

  <h1>📦 Inventor – Inventory Management System Web API</h1>

  <p>
    A RESTful Inventory Management System built with
    <strong>C# and ASP.NET Core Web API</strong>.
  </p>

  <p>
    Designed to manage products, categories, suppliers,
    inventory records, customers, and orders.
  </p>

</div>

<hr />

<h2>📌 About The Project</h2>

<p>
  <strong>Inventor</strong> is a backend Inventory Management System
  developed using C#, ASP.NET Core Web API, Entity Framework Core,
  LINQ, and SQL Server.
</p>

<p>
  The project provides RESTful APIs and CRUD operations for managing
  inventory-related business data. It follows a layered and reusable
  architecture to separate data access from business logic,
  improve maintainability, and support efficient data management.
</p>

<h2>🚀 Key Features</h2>

<ul>
  <li>
    <strong>Product Management:</strong>
    Create, retrieve, update, and delete products.
  </li>
  <li>
    <strong>Category Management:</strong>
    Manage product categories and their relationships.
  </li>
  <li>
    <strong>Supplier Management:</strong>
    Manage supplier information and related products.
  </li>
  <li>
    <strong>Inventory Management:</strong>
    Manage inventory records and related business data.
  </li>
  <li>
    <strong>Customer Management:</strong>
    Manage customer information.
  </li>
  <li>
    <strong>Order Management:</strong>
    Handle order-related data and relationships.
  </li>
  <li>
    <strong>RESTful APIs:</strong>
    Provide structured HTTP endpoints for application operations.
  </li>
  <li>
    <strong>Data Validation:</strong>
    Validate incoming requests using Data Annotations and
    Custom Action Filters.
  </li>
</ul>

<h2>🛠️ Technologies & Tools</h2>

<ul>
  <li>C#</li>
  <li>ASP.NET Core Web API</li>
  <li>Entity Framework Core</li>
  <li>LINQ (Language Integrated Query)</li>
  <li>SQL Server</li>
  <li>Entity Framework Core Code-First</li>
  <li>Data Annotations</li>
  <li>Custom Action Filters</li>
  <li>Data Transfer Objects (DTOs)</li>
</ul>

<h2>🏗️ Design Patterns & Architecture</h2>

<ul>
  <li>
    <strong>Generic Repository Pattern:</strong>
    Provides reusable data access operations and reduces
    code duplication.
  </li>
  <li>
    <strong>Specification Pattern:</strong>
    Encapsulates query criteria and helps organize complex
    data retrieval logic.
  </li>
  <li>
    <strong>Layered Architecture:</strong>
    Separates data access responsibilities from business logic
    to improve maintainability and code organization.
  </li>
  <li>
    <strong>DTO Pattern:</strong>
    Transfers data between application layers and API endpoints
    without exposing database entities directly.
  </li>
</ul>

<h2>🗄️ Database Design</h2>

<p>
  The project uses <strong>SQL Server</strong> with
  <strong>Entity Framework Core Code-First</strong> to design
  and manage relational database models.
</p>

<p>
  The database includes entities and relationships between:
</p>

<ul>
  <li>Products</li>
  <li>Product Categories</li>
  <li>Suppliers</li>
  <li>Inventory Records</li>
  <li>Customers</li>
  <li>Orders</li>
</ul>

<h2>✅ Validation & Data Processing</h2>

<p>
  To ensure consistent and reliable API request processing,
  the project uses:
</p>

<ul>
  <li><strong>DTOs:</strong> To structure request and response data.</li>
  <li><strong>Data Annotations:</strong> To define validation rules.</li>
  <li><strong>Custom Action Filters:</strong> To handle request validation
      and consistent processing across API endpoints.</li>
</ul>

<h2>⚙️ Getting Started</h2>

<h3>Prerequisites</h3>

<ul>
  <li>.NET SDK</li>
  <li>SQL Server</li>
  <li>Visual Studio</li>
  <li>Git</li>
</ul>

<h3>Installation</h3>

<ol>
  <li>
    Clone the repository:
    <pre><code>git clone YOUR_REPOSITORY_URL</code></pre>
  </li>
  <li>
    Navigate to the project directory:
    <pre><code>cd Inventor</code></pre>
  </li>
  <li>
    Restore project dependencies:
    <pre><code>dotnet restore</code></pre>
  </li>
  <li>
    Configure your SQL Server connection string
    in the application configuration.
  </li>
  <li>
    Apply the Entity Framework Core migrations:
    <pre><code>dotnet ef database update</code></pre>
  </li>
  <li>
    Run the application from Visual Studio or using:
    <pre><code>dotnet run</code></pre>
  </li>
</ol>

<h2>🎯 Project Goals</h2>

<ul>
  <li>Build a maintainable and reusable backend architecture.</li>
  <li>Apply Repository and Specification design patterns.</li>
  <li>Improve separation of concerns between application layers.</li>
  <li>Build RESTful APIs following backend development practices.</li>
  <li>Design and manage relational databases using EF Core.</li>
</ul>

<hr />

<h2>👨‍💻 Author</h2>

<p>
  <strong>Your Name</strong>
</p>

<hr />

<div align="center">
  <p>
    Built with ❤️ using ASP.NET Core Web API
  </p>
</div>
