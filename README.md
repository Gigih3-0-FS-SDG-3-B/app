# Carepal
## Description
__Carepal,__ __*Empowering Elders, Enabling Care*__ 👵👴

As Indonesia's population ages rapidly, CarePal steps in as a revolutionary solution to address the challenges faced by families in providing quality care for their elderly loved ones. This GitHub repository houses the codebase for CarePal, an innovative app designed to streamline the search, hiring, and operational processes of caregivers.

## Features

🔍 Search with Ease:

CarePal simplifies the daunting task of finding qualified and experienced caregivers. The app provides a user-friendly platform for families to discover caregivers suited to their specific needs.

🤝 Hassle-Free Hiring:

Say goodbye to the complexities of hiring caregivers. CarePal facilitates a seamless hiring process, ensuring families can connect with reliable caregivers daily or for long-term commitments.

🌐 Bridging Information Gaps:

Tackling the lack of information and transparency in elderly care services, CarePal empowers families with the knowledge they need. Easily compare rates, services, and caregiver qualifications at your fingertips.

## Local Development Setup
1. Clone this github project
    ``` 
    $ git clone --recursive https://github.com/Gigih3-0-FS-SDG-3-B/carepal.git
    ```
2. Insert .env files into both carepal-fe & carepal-be folders

3. Setup Prisma (ORM) Config

    Duplicate `.example.schema.prisma` and rename to `.schema.prisma`
4. Make sure we're at the root workspace directory
5. Make sure you have Docker running at the current machine and `docker-compose` installed.
    ```
    $ docker-compose build
    ```
    Afterwards,
    ```
    $ docker-compose up
    ```

## Tech Stack & Specification

__Node Version:__ `20.8.0`

### Frontend
- React JS running on port 3000
- Chakra UI
- React Bootstrap
- Tailwind CSS
- React Datepicker

### Backend
- NodeJS
- Prisma
- Swagger UI

### Database
- MySQL

### Authentication
- JWT


## API Documentation

Swagger UI Self Hosted URL:
```
localhost:5000/api/docs
```
Or available at [Postman Public Documention](
https://documenter.getpostman.com/view/25063333/2s9YXo2L5S)
