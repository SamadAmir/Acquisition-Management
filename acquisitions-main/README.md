<h1>Acquisition Management System</h1>
A comprehensive business acquisition and deal management platform built with modern DevOps practices, featuring containerized deployment, automated testing, and enterprise-grade security.
<h2>🚀 Features </h2>
Core Functionality

<ul>
<li>Business Listings Management: Create, update, delete, and browse business listings efficiently</li>
<li>Deal Management: Create deals on listings, accept or reject offers, and track deal status</li>
<li>User Management: Complete CRUD operations for user accounts with role-based access control</li>
<li>Authentication & Authorization: JWT-based authentication supporting signup, signin, and signout workflows</li>
</ul>
DevOps & Infrastructure

Docker Containerization: Full containerization with separate development and production environments
Health Monitoring: System health endpoints for monitoring application status
Structured Logging: Winston-based logging throughout the application for debugging and monitoring
Automated Testing: Comprehensive test suite with Jest and SuperTest for unit and integration testing
Hot Reload: Development server with automatic restart on file changes

Security & Validation

Advanced Security: Integrated Arcjet for bot protection, rate limiting, and attack prevention
Input Validation: Zod schemas for runtime type safety and data validation
Role-Based Access Control: Admin and user roles with permission middleware
Secure Authentication: JWT tokens with proper session management

Code Quality

TypeScript-First: Full TypeScript implementation with strict type checking
Clean Architecture: Absolute imports with # prefix aliases for organized code structure
Code Standards: ESLint and Prettier for consistent code formatting and linting
Database Management: Type-safe queries and automated schema migrations with Drizzle ORM

🛠️ Tech Stack
Backend

Runtime: Node.js
Framework: Express.js
Database: Neon PostgreSQL (Serverless)
ORM: Drizzle ORM
Authentication: JSON Web Tokens (JWT)

Security & Validation

Security Layer: Arcjet (bot protection, rate limiting, email validation)
Schema Validation: Zod (TypeScript-first validation)
Input Sanitization: Express middleware with Zod integration

DevOps & Infrastructure

Containerization: Docker with multi-stage builds
Orchestration: Kubernetes ready
Database: Neon Postgres with autoscaling and branching
Monitoring: Winston structured logging
Testing: Jest with SuperTest for API testing

Development Tools

Terminal: Warp (modern Rust-based terminal)
Package Manager: npm/yarn
Type Checking: TypeScript with strict mode
Code Quality: ESLint + Prettier
