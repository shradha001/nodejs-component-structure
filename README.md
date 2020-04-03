# NodeJs Boilerplate

This project structure aims at structuring the code based on components.

## Features

- **Component based** project structure
- [Celebrate](https://www.npmjs.com/package/celebrate) to **validate request parameters**

- Log using [Winston](https://www.npmjs.com/package/winston) and [Morgan](https://www.npmjs.com/package/morgan)

- **Swagger documentation** for the APIs.

- [Nodemon](https://www.npmjs.com/package/nodemon) to automatically restart the application when file changes

- **ESLint** for identifying and reporting on patterns found in ECMAScript/JavaScript code.

- **Prettier** as the code formatter

- Test cases using **Mocha** and **Chai**

- **Coverage report** using [nyc](https://www.npmjs.com/package/nyc)

- **Build** and **lint commit messages** using commitizen and commitlint

- **MongoDB database** integration

- **Git hooks** to check for lint before commit and test cases before a git push

## Prerequisites

- [MongoDB](https://www.mongodb.com/download-center/community)

- [Node.js](https://nodejs.org/en/download/)

## Getting Started

- Clone the repository first.

git clone https://github.com/shradha001/nodejs-component-structure.git

- Change directory
  `cd nodejs-component-structure`

- Install dependencies
  `npm install`
- Run the application in dev mode
  `npm run dev`

## Testing the API in Swagger

1. Once your application is up, open the url [http://localhost:9596/documentation/](http://localhost:9596/documentation/) in browser to access the swagger documentation.

## Scripts

- `dev` : Run the application in development mode

- `test`: Run the test cases

- `coverage`: Check the code coverage

- `report`: Generate the code coverage in html format(After running this script, open the file `coverage/index.html` in browser)

- `lint`: lint code

- `lint:fix`: Fix linting issue

- `formatter`: Run prettier code formatter

- `commit`: Create commit message

## Contributing

This boilerplate is open for any suggestions and contribution which makes it better.

## Authors

This boilerplate is developed by Shradha Mallik.

## License

MIT License

Copyright (c) 2020 Shradha

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
