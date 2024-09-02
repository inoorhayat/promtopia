# Promtopia

Promtopia is a full-stack web application built with Next.js, MongoDB, and NextAuth for authentication. The application allows users to create, share, and explore AI-generated prompts.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Demo

A live demo of the project can be found [here](https://promtopia.vercel.app).

## Features

- User authentication with Google via NextAuth.
- Create, edit, and delete prompts.
- Explore prompts created by other users.
- Search functionality to find prompts by keywords.
- User profiles with a list of their created prompts.

## Tech Stack

- **Frontend:** Next.js, TailwindCSS
- **Backend:** Node.js, MongoDB
- **Authentication:** NextAuth (Google Provider)
- **Database:** MongoDB (with Mongoose)

## Installation

Follow these steps to get the project up and running on your local machine.

### Prerequisites

- Node.js (v14.x or later)
- MongoDB (local instance or MongoDB Atlas)
- A Google account for OAuth (Google Client ID and Secret)

### Clone the Repository

```bash
git clone https://github.com/inoorhayat/promtopia.git
cd promtopia

