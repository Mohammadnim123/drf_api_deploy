[Repo](https://github.com/Mohammadnim123/drf_api_deploy)

[PR1](https://github.com/Mohammadnim123/drf_api_deploy/pull/1)

[PR3](https://github.com/Mohammadnim123/drf_api_deploy/pull/3)

[Live server](https://movies-api-nemrawi.herokuapp.com/api/v1/movies/)

**.env**

```
DEBUG=off
SECRET_KEY=6af((y!u)*m5_3f*ly58g(r6=h)-)%vpe=e&u5=7)wo)@%dvhl
DATABASE_NAME=postgres
DATABASE_USER=postgres
DATABASE_PASSWORD=postgres
DATABASE_HOST=db
DATABASE_PORT=5432
ALLOWED_HOSTS=0.0.0.0,localhost,127.0.0.1,.movies-api-nemrawi.com,movies-api-nemrawi.herokuapp.com
```

# Overview

It’s time to deploy!

First steps are to make sure your Application is able to run well in a remote environment.

Once you are confident that your Application is *deployable` then time to research deployment options.

**Feature Tasks and Requirements**

NOTE: You can use previous lab’s Application as a starting point or start from scratch.

Modify your application to store SECRET_KEY, ALLOWED_HOSTS, DEBUG and DATABASE information in .env file.

Add CORS capabilities to your app and whitelist allowed origins.

All the code changes will be in settings.py so check the demo code for CORS and Env related lines.

In a nutshell - make your own Application similar to the demo, and put it on the web.