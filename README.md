# Documentation Writer Interview

Simple Express/Node.js app.

## Requirements

* Node.js
* Yarn or NPM
* Express.js

## Setup

### 1. Clone GitHub Repo

From your terminal, run the following commands:

```git clone git@github.com:quiknode-labs/DocumenationWriterInterview.git```<br/>

cd into working directory:

```cd DocumenationWriterInterview```<br/>
```cd Written```

### 2. Install Dependencies

```yarn```<br/>
```yarn add express```

## To Test Methods:

#### 1. Download Postman or Insomnia for testing.

#### 2. Start server in development mode:

```yarn dev```

#### 3. Make all requests to http://localhost:3000/

#### GET

Returns all transactions

In this case, the following will be returned: 
```
    {
        "id": 1,
        "amount": 25,
        "to": "joe"
    }
```


#### POST

To send a post request use the following key/value pair format:

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

#### DELETE

To delete a post send a delete request to: 
```
{
        "id": number<br/>
}
```

Example:
```
{
        "id": 2
}
```

