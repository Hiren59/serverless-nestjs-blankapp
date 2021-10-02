

<br />
<p align="center">
  <h3 align="center">Serverless NestJS blank-app</h3>
  
  <p align="center">
  <img src="https://i.ibb.co/k9vGNHf/Logo-Makr-3h5n-Cq.png">
</p>
  
  <p align="center">
    A simple blank-app to kickstart your NestJS project using AWS lambda.
    <br />
    <a href="https://github.com/alexbdet/sls-nest-blankapp/issues">Report Bug</a>
    ·
    <a href="https://github.com/alexbdet/sls-nest-blankapp/issues">Request Feature</a>
  </p>
</p>



<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

## About the project

## Getting Started

### Prerequisites
- [AWS](aws.amazon.com) account
- [NodeJS](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- serverless CLI : `npm install -g serverless`

### Installation

Clone the repository :<br/>
```git clone https://github.com/alexbdet/serverless-nestjs-blankapp.git```

Run those commands :
```
cd sls-nest-blankapp
npm install
npm run build
sls offline
```

Hit `localhost:3000/dev`, if everything went well you should see the "Hello World!" message !

To deploy on AWS, use :
```
npm run build
serverless deploy
```
The CLI will deploy your code and create the required services (usually : API gateway & lambda function).

## License

This project uses "unlicense". See `LICENSE` for more information.



## Contact

Alexandre Beaudet - [@alex_bdet](https://twitter.com/alex_bdet) - alexandre.bdet@gmail.com


## Acknowledgements
* [NestJS](nestjs.com)
