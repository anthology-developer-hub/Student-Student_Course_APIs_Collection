# Student-StudentCourseApi-sCollection

## Description

This project involves postman collection to fetch the information of Courses ,fetch the information based on Student Id.

## Installation

### Postman

To install Postman, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## API List

The `api/postman/StudentInfoPostmanCollection.postman_collection` file contains the following APIs:

- `POST https://sisclientweb-700031.campusnexus.cloud/api/commands/Academics/Course/get`: Returns course information for a specific student.
- `POST https://sisclientweb-700031.campusnexus.cloud/api/commands/Academics/Course/create`: Used to Create a course.
- `POST https://sisclientweb-700031.campusnexus.cloud/api/commands/Academics/Course/getCourseAttributes`: Used to get the course attributes.

## Usage

After importing the `StudentInfoPostmanCollection.postman_collection` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the collection variables correctly:

- `username`: student environment username
- `password`: student environment password
