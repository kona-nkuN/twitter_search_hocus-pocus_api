# Twitter Search Hocus Pocus API

## Description
Twitter Search Hocus Pocus API is a RESTful API that offers two methods to get tweets easily. 

They are:

1. to get a list of tweets with a given hashtag in JSON format.
2. to get a list of tweets certain user has on his/her own feed in JSON format.

Here is how the API works.

If you want to get tweets with a hashtag #Avengers, 

```
curl -X GET "http://localhost:5000/hashtags/Avengers" -H "accept: application/json"
```

Likewise, if you want to get tweets someone specific(let's say Kyary Pamyu Pamyu) has on his/her feed,

```
curl -X GET "http://localhost:5000/users/pamyurin" -H "accept: application/json"
```

## Requirements

### python version
- python>=3.0

### pip 
- flask>=1.0
- TwitterAPI
- (requests)

`requests` package is required only if you run tests.

## Set up

### install the required packages

Make sure you have installed python>=3.0.

run the following command.

```
pip install flask TwitterAPI
```

### Set Twitter Token to the environment variables

