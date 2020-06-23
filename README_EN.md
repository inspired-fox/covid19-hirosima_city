#The City of Hiroshima's COVID-19 task force website
# [![COVID-19 Task Force website](https://github.com/inspired-fox/covid19-hirosima_city/blob/develop/static/logo-hiroshima-city.png)](https://github.com/inspired-fox/covid19-hirosima_city)

### [日本語](./README.md) | English 

## How to Contribute

All contributions are welcome!
Please check [How to contribute](./.github/CONTRIBUTING_EN.md) for details.

## Code of Conduct

Please check [Code of conduct for developers](./.github/CODE_OF_CONDUCT_EN.md) for details.

## License
This software is released under [the MIT License](./LICENSE.txt).

## For Developers

### How to Set Up Environments

- Required Node.js version: 10.19.0 or higher

**Use yarn**
``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev
```

**Use docker**
```bash
# serve with hot reload at localhost:3000
$ docker-compose up --build
```

### Deployment to Staging & Production Environments

When `master` branch is updated, the HTML files will be automatically built onto `production` branch,
and then the production site (https://stopcovid19-hiroshima-city.hiroshima-cu.ac.jp) will be also updated.  

