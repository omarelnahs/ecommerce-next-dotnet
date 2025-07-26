# 🛒 E-commerce Platform – Next.js + .NET Core

A modern full-stack e-commerce web application built using:

- 🧩 **Frontend**: Next.js + TypeScript + TailwindCSS
- 🔧 **Backend**: ASP.NET Core Web API + Entity Framework Core (Code First)
- 💾 **Database**: SQL Server
- 🔐 **Auth**: JWT-based authentication

---

## 📁 Project Structure

```bash
ecommerce-next-dotnet/
├── backend/                # ASP.NET Core Web API
│   ├── Ecommerce.API/      # API project
│   ├── Ecommerce.Core/     # Domain models and DTOs
│   └── Ecommerce.Data/     # EF Core, DbContext, Migrations
│
├── frontend/               # Next.js + TS
│   ├── pages/              # Routes
│   ├── components/         # Reusable UI
│   └── services/           # API client logic
