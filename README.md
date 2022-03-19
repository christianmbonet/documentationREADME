# Documentation Writer Interview

![Node](https://img.shields.io/node/v/no)
![Express Logo](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png)](http://expressjs.com/)

Simple Express/Node.js app.

## Requirements

* Node: ">= 0.4"
* Yarn or NPM
* Express.js: "^4.17.1"

## Setup

#### 1. Clone GitHub Repo

From your terminal, run the following command:

```git clone git@github.com:quiknode-labs/DocumenationWriterInterview.git```<br/>

cd into working directory:

```cd DocumenationWriterInterview```<br/>
```cd Written```

#### 2. Install Dependencies

```yarn```<br/>
```yarn add express```

## To Test Methods:

##### 1. Download Postman or Insomnia for testing.

##### 2. Start server in development mode:

```yarn dev```

##### 3. Make all requests to http://localhost:3000/

#### GET

GET all transactions.

To send a GET request, send request with an empty body.

In this case, the following will be returned: 
```
    {
        "id": 1,
        "amount": 25,
        "to": "joe"
    }
```

#### POST

POST a new transaction.

To send a POST request, use the following JSON format in body of the request:

```
{
        "id": number,
        "amount": number,
        "to": "string"
}
```

Example:
```
{
        "id": 2,
        "amount": 30,
        "to": "francis"
}
```

A POST request should return the following:

```
successfully added transaction #: 1, in the amount of 30 to: francis
```

#### DELETE

DELETE a single transaction.

To DELETE a single transaction, send a delete request using the following key-value pair in the body of the request:
```
{
        "id": number
}
```

Example:
```
{
        "id": 2
}
```

A DELETE request should return the following:

```
sucessfully deleted transaction #: 1}}
```