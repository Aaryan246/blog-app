# Blog-app

## Overview

A brief description of your project, what it does, and why it exists.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**
```
git clone https://github.com/Aaryan246/blog-app.git
cd blog-app
```
2. **Install Dependencies**
```
npm install
```
3. **Set up MongoDB**  
-Ensure MongoDB is installed and running on your machine.  
-Create a .env file in the root directory and add your MongoDB connection string
```
MONGODB_URI=your_mongodb_connection_string
```
4. **Start up the application**
```
node app.js
```
## Usage  

- Open your browser and navigate to `http://localhost:3000.`  
- Follow the on-screen instructions to interact with the application.

## Features

1. **Compose**  
-Create a new blog by providing a title and the content of the blog on `/compose`

2. **View**  
- View the posted blogs on the home page

3. **Expand**  
- Click on Read More to read the full content of the blogs.

## Technologies  

+ Express: Web framework for Node.js.
+ EJS: Templating engine for generating HTML.
+ MongoDB: NoSQL database for storing data.


## Contributing  

1. Fork the repository.
2. Create a new branch `git checkout -b feature-branch`.
3. Make your changes.
4. Commit your changes `git commit -m 'Add new feature'`.
5. Push to the branch `git push origin feature-branch`.
6. Open a Pull Request.

## License  
This project is licensed under the MIT License.
