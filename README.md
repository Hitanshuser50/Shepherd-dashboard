
# Shepherd-dashboard

This project provides a visually guided dashboard experience using Shepherd.js (https://blog.shepherdpro.com/). It's designed to enhance user onboarding and engagement with interactive tutorials and step-by-step guides.


# Hi, I'm Hitansh! 👋


## Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express


## Screenshots

![App Screenshot](![image](https://github.com/Hitanshuser50/Shepherd-dashboard/assets/122915291/1112996e-7899-469a-bf01-77c33698f711))


Installation

1) Prerequisites:

Node.js and npm (or yarn) installed on your system. You can download them from https://nodejs.org/en

## Run Locally

Clone the project

```bash
  git clone https://github.com/Hitanshuser50/Shepherd-dashboard.git

```

Go to the project directory

```bash
  cd Shepherd-dashboard
```

Install dependencies

```bash
  
npm install  # or yarn install

```

Start the server

```bash
  npm start  # or yarn dev (depending on your preference)

```


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Authors

- [@octokatherine](https://www.github.com/octokatherine)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

