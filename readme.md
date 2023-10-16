car-rental-app/
├── cmd/
│ └── server/
│ ├── main.go # Application entry point
│
├── internal/
│ ├── api/
│ │ ├── routes.go # API route definitions
│ │ ├── middleware/
│ │ │ ├── auth.go # Authentication middleware
│ │ │ ├── logging.go # Logging middleware
│ │ │ └── ...
│ │
│ ├── config/
│ │ ├── config.go # Application configuration
│ │
│ ├── db/
│ │ ├── postgres/
│ │ │ ├── postgres.go # PostgreSQL database setup
│ │ │ ├── migrations/ # Database migration files
│ │ │ └── ...
│ │
│ ├── handlers/
│ │ ├── car.go # Car-related API handlers
│ │ ├── user.go # User-related API handlers
│ │ └── ...
│ │
│ ├── models/
│ │ ├── car.go # Car data model
│ │ ├── user.go # User data model
│ │ └── ...
│ │
│ ├── services/
│ │ ├── car_service.go # Business logic for cars
│ │ ├── user_service.go # Business logic for users
│ │ └── ...
│ │
│ └── utils/
│ ├── helpers.go # Utility functions
│ ├── validation.go # Input validation functions
│ └── ...
│
├── static/ # Static assets (if needed)
│ ├── css/
│ ├── js/
│ ├── images/
│ └── ...
│
├── templates/ # HTML templates (if using server-side rendering)
│ ├── index.html
│ ├── ...
│
├── tests/
│ ├── integration/ # Integration tests
│ └── unit/ # Unit tests
│
├── .env # Environment variable configuration
├── go.mod # Go module file
├── go.sum # Go module sum file
└── README.md # Project documentation
