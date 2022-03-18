# Documentation Writer Interview

## Setup

Clone GitHub Repo:

```git clone git@github.com:quiknode-labs/DocumenationWriterInterview.git``` <br/>
```cd DocumenationWriterInterview``` <br/>
```cd Written```

Install dependencies:

```yarn```<br/>
```yarn add express```

To start server in development mode:

```yarn dev```

## Methods

To test methods: start server locally and make all requests to http://localhost:3000/

#### GET

Returns all transactions

In this case, the following will be returned: 

[
    {
        "id": 1,
        "amount": 25,
        "to": "joe"
    }
]


#### POST

To send a post request use the following key/value pair format:

{
        "id": number,
        "amount": number,
        "to": "string"
}

Example:

{
        "id": 2,
        "amount": 30,
        "to": "francis"
}


#### DELETE

To delete a post send a delete request to: 

{
        "id": number
}

Example:

{
        "id": 2
}


