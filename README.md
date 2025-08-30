# CollabX Project Overview

This project covers the end-to-end process of building a Jira clone. It implements various features including workspaces, projects/epics, tasks, Kanban boards, calendars, invitation systems, role-based access control, image uploads, analytics, and authentication.

## Key Features

- **Workspaces:** Manage team-specific work areas.
- **Projects/Epics:** Manage projects and epics.
- **Tasks:** Manage tasks.
- **Kanban Board View:** Kanban board view.
- **Data Table View:** Data table view.
- **Calendar View:** Calendar view.
- **Invitation System:** Team member invitation functionality.
- **Workspace and Project Settings:** Manage workspace and project settings.
- **Image Uploads:** Avatar and attachment image uploads.
- **Appwrite SDK Integration:** Appwrite SDK integration.
- **Next.js 14 Framework:** Utilizes the Next.js 14 framework.
- **Shadcn UI & TailwindCSS Styling:** Shadcn UI and TailwindCSS styling.
- **Advanced Search and Filtering:** Advanced search and filtering.
- **Analytics Dashboard:** Analytics dashboard.
- **User Roles and Permissions:** User role and permission management.
- **Authentication (OAuth and Email):** OAuth and email authentication.
- **Responsive Design (Mobile-Friendly):** Responsive design (mobile-friendly).
- **API using Hono.js:** API powered by Hono.js.

## Technology Stack

- Next.js 14
- React
- TailwindCSS
- Hono.js
- Appwrite
- Shadcn UI
- TanStack Query
- Zod
- React Icons
- React Hook Form
- React Big Calendar

## Project Structure

1. **Project Setup:** 
   - Component library addition (shadcn/ui) and project structure setup.
   - Component customization and lint error resolution.
2. **Authentication:**
   - Construction of login and signup screens.
   - Hono API setup and authentication API implementation.
   - Appwrite setup and database construction.
3. **Middleware and Layouts:**
   - Session middleware construction and route protection.
   - Dashboard layout and workspace form construction.
4. **Features Development:**
   - Image upload handling and workspace switching.
   - Workspace member management and invitation system.
   - Responsive modal and standalone layout construction.
   - Workspace settings and server query refactoring.
   - Delete and invitation reset functionalities.
   - Workspace projects and project settings.
   - Task API construction and task form development.
   - Data filter and data table construction.
   - Kanban update API addition and calendar integration.
   - Task page construction and server component refactoring.
   - Project and workspace analytics functionality.
5. **Finalization:**
   - Build error resolution.
   - OAuth login implementation.
   - Vercel deployment and bug fixes.

## Project Implementation Method

1. **Environment Setup:**  
   Install necessary tools and libraries.
2. **Basic Structure Construction:**  
   Set up project structure and basic components.
3. **Core Functionality Implementation:**  
   Implement core functionalities such as workspaces, projects, and tasks.
4. **UI/UX Improvement:**  
   Enhance styling and overall user experience.
5. **Testing and Deployment:**  
   Thorough testing followed by deployment on Vercel.

---

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev