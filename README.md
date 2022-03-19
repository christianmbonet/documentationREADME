# Documentation Writer Interview

Simple Express/Node.js app.

## Requirements

* Node.js
* Yarn or NPM
* Express.js

## Setup

#### Clone GitHub Repo:

In your terminal run the following commands:

```git clone git@github.com:quiknode-labs/DocumenationWriterInterview.git```<br/>
```cd DocumenationWriterInterview```<br/>
```cd Written```

Once inside "Written" folder, install dependencies by running the following:

```yarn```<br/>
```yarn add express```

## To Test Methods:

Start server in development mode:

```yarn dev```

Use Postman or Insomnia to test methods.

Make all requests to http://localhost:3000/

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


