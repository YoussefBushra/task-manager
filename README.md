
# Full-Stack Task Manager (Laravel + Next.js + PostgreSQL)

This repository contains a full-stack web application structured as a monorepo, with the backend (Laravel) and frontend (Next.js) managed as submodules. The database used is PostgreSQL.


## Installation

```bash
  git clone --recurse-submodules https://github.com/YoussefBushra/task-manager.git
  cd task-manager
```
    
## Backend Setup

```bash
  cd backend
  composer install
```
Now, copy your **.env.example** and configure your database (I am using postgreSQL)

```bash
  cp .env.example .env
  php artisan key:generate
```
```bash
  php artisan migrate
  php artisan db:seed
  php artisan serve
```


## Frontend Setup

```bash
  cd frontend
  npm install
```
Now, copy your **.env.example** and configure your backend local URL

```bash
  cp .env.example .env.local
  npm run dev
```




## Screenshots
<img width="1463" alt="Screenshot 2025-05-09 at 1 43 27 PM" src="https://github.com/user-attachments/assets/c9f82f59-b3a2-40e3-bc44-a8a883fe2676" />

<img width="920" alt="Screenshot 2025-05-09 at 1 45 21 PM" src="https://github.com/user-attachments/assets/284e36e1-cf26-4e9c-b819-9bb58dfb4bb5" />

<img width="771" alt="Screenshot 2025-05-09 at 1 46 14 PM" src="https://github.com/user-attachments/assets/0817129d-f935-4840-8125-eee4850b8f07" />

<img width="779" alt="Screenshot 2025-05-09 at 1 46 26 PM" src="https://github.com/user-attachments/assets/99e0fcb8-ed4c-45d7-a15e-91959366d146" />


## FAQ

#### What are the used frontend tools?

Nextjs (App Router), TailwindCSS, ShadCn Components

#### What are the used backend tools?

Laravel & PostgreSQL
