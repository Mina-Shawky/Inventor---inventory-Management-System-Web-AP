<div align="center">

  <h1>📦 Inventor – Inventory Management System Web API</h1>

  <p>
    A RESTful Inventory Management System built with
    <strong>C# and ASP.NET Core Web API</strong>.
  </p>

  <p>
    Managing products, categories, suppliers, inventory,
    customers, and orders through a structured backend architecture.
  </p>

  <p>
    <a href="https://github.com/Mina-Shawky/Inventor---inventory-Management-System-Web-AP">
      View Project on GitHub
    </a>
  </p>

</div>

<hr />

<h2>📌 About The Project</h2>

<p>
  Inventor is an Inventory Management System backend
  developed using C#, ASP.NET Core Web API,
  Entity Framework Core, LINQ, and SQL Server.
</p>

<p>
  The application provides RESTful APIs and CRUD operations
  for managing inventory-related business data.
  It follows a layered architecture to separate data access
  from business logic, improve maintainability,
  and promote code reusability.
</p>

<h2>🚀 Key Features</h2>

<ul>
  <li>Product Management</li>
  <li>Product Category Management</li>
  <li>Supplier Management</li>
  <li>Inventory Records Management</li>
  <li>Customer Management</li>
  <li>Order Management</li>
  <li>RESTful API Endpoints</li>
  <li>CRUD Operations</li>
  <li>Request Validation</li>
  <li>Reusable Data Access Operations</li>
</ul>

<h2>🛠️ Technologies & Tools</h2>

<ul>
  <li>C#</li>
  <li>ASP.NET Core Web API</li>
  <li>Entity Framework Core</li>
  <li>LINQ</li>
  <li>SQL Server</li>
  <li>Entity Framework Core Code-First</li>
  <li>Data Transfer Objects (DTOs)</li>
  <li>Data Annotations</li>
  <li>Custom Action Filters</li>
</ul>

<h2>🏗️ Design Patterns & Architecture</h2>

<h3>Generic Repository Pattern</h3>

<p>
  Implemented reusable data access operations
  to reduce code duplication and separate database
  operations from business logic.
</p>

<h3>Specification Pattern</h3>

<p>
  Used to encapsulate query criteria and organize
  complex filtering and data retrieval operations.
</p>

<h3>Layered Architecture</h3>

<p>
  Organized application responsibilities into separate
  layers to improve maintainability, scalability,
  and separation of concerns.
</p>

<h3>DTO Pattern</h3>

<p>
  Used DTOs to transfer data between application layers
  and API endpoints without exposing database entities directly.
</p>

<h2>🗄️ Database Design</h2>

<p>
  The project uses SQL Server and Entity Framework Core
  Code-First to create and manage relational database models.
</p>

<p>Core entities include:</p>

<ul>
  <li>Products</li>
  <li>Product Categories</li>
  <li>Suppliers</li>
  <li>Inventory Records</li>
  <li>Customers</li>
  <li>Orders</li>
</ul>

<h2>✅ Validation & Data Processing</h2>

<ul>
  <li>
    <strong>DTOs:</strong>
    For structured request and response models.
  </li>
  <li>
    <strong>Data Annotations:</strong>
    For defining validation rules.
  </li>
  <li>
    <strong>Custom Action Filters:</strong>
    For consistent request validation and processing
    across API endpoints.
  </li>
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
    <pre><code>git clone https://github.com/Mina-Shawky/Inventor---inventory-Management-System-Web-AP.git</code></pre>
  </li>

  <li>
    Navigate to the project directory:
    <pre><code>cd Inventor---inventory-Management-System-Web-AP</code></pre>
  </li>

  <li>
    Navigate to the API project:
    <pre><code>cd InventorySystemAPI</code></pre>
  </li>

  <li>
    Restore dependencies:
    <pre><code>dotnet restore</code></pre>
  </li>

  <li>
    Configure your SQL Server connection string
    in the application configuration.
  </li>

  <li>
    Apply Entity Framework Core migrations:
    <pre><code>dotnet ef database update</code></pre>
  </li>

  <li>
    Run the application:
    <pre><code>dotnet run</code></pre>
  </li>
</ol>

<h2>🎯 Project Goals</h2>

<ul>
  <li>Build a maintainable and reusable backend system.</li>
  <li>Apply Repository and Specification Design Patterns.</li>
  <li>Develop RESTful APIs using ASP.NET Core.</li>
  <li>Design relational databases using EF Core Code-First.</li>
  <li>Improve separation of concerns and code reusability.</li>
</ul>

<hr />

<h2>👨‍💻 Author</h2>

<p>
  <strong>Mina Shawky</strong>
</p>

<p>
  GitHub:
  <a href="https://github.com/Mina-Shawky">
    @Mina-Shawky
  </a>
</p>

<hr />

<div align="center">

  <p>
    Built with ❤️ using C# and ASP.NET Core Web API
  </p>

  <p>
    ⭐ Feel free to explore the repository!
  </p>

</div>
