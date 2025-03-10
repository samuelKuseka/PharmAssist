# PharmAssist
A sales and inventory management system for local drug stores / warehouses.

## Repository Structure

```plaintext
pharmassist/
├── backend                # ASP.NET Core backend
│   ├── PharmAssist.API    # Main API project
│   ├── appsettings.json   # Configuration file
│   ├── Program.cs         # Entry point
│   └── Startup.cs         # Middleware & services
├── frontend               # Next.js frontend
│   ├── components         # Reusable UI components
│   ├── pages              # Next.js pages (routes)
│   ├── public             # Static assets (images, icons)
│   ├── next.config.js     # Next.js configuration
│   ├── package.json       # Dependencies & scripts
│   ├── tsconfig.json      # TypeScript configuration
│   └── .env               # Environment variables
├── .gitignore             # Ignore unnecessary files
├── docker-compose.yml     # Docker setup for backend & frontend
├── LICENSE                # Project license
└── README.md              # Main project documentation
```

## Getting Started

Follow these steps to set up and run the PharmAssist project on your local machine.

### Backend Setup

1. **Clone the Repository** (if you haven't already):
   ```bash
   git clone https://github.com/your-username/pharmassist.git
   cd pharmassist/backend
   ```
2. **Restore Dependencies**:
   ```bash
   dotnet restore
   ```
3. **Run the API**:
   ```bash
   dotnet run
   ```

### Frontend Setup

1. **Navigate to the Frontend Folder**:
   ```bash
   cd ../frontend
   ```
2. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Start the Development Server**:
   ```bash
   npm run dev
   ```

### Running with Docker

1. **Ensure Docker is installed and running.**
2. **Build and Run Containers**:
   ```bash
   docker-compose up --build
   ```

