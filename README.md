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

### 1. Download Postman or Insomnia for testing.

### 2. Start server in development mode:

```yarn dev```

### 3. Make all requests to http://localhost:3000/

#### GET

Returns all transactions

In this case, the following will be returned: 

[<br/>
    {<br/>
        "id": 1,<br/>
        "amount": 25,<br/>
        "to": "joe"<br/>
    }
]


#### POST

To send a post request use the following key/value pair format:

{<br/>
        "id": number,<br/>
        "amount": number,<br/>
        "to": "string"<br/>
}

Example:

{<br/>
        "id": 2,<br/>
        "amount": 30,<br/>
        "to": "francis"<br/>
}


#### DELETE

To delete a post send a delete request to: 

{<br/>
        "id": number<br/>
}

Example:

{<br/>
        "id": 2<br/>
}


