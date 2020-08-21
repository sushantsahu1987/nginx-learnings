# my-react-app


### Docker
    docker build -t sushantsahu/my-react-app:1.0.4 .
    docker pull sushantsahu/my-react-app:1.0.4
    docker run -p 80:3000 sushantsahu/my-react-app:1.0.4

### Important
    If using Azure, follow this step:
    - App Service => Configuration => App. Settings => WEBSITES_PORT 3000

    reason being: https://docs.microsoft.com/en-us/azure/app-service/configure-custom-container