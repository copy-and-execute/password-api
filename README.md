## Password-API
### Generate passwords of diffrent complexity

### About the API

This API lets you generate random passwords of diffrent complexity for your project. 
The api is free and can be accessed from anywhere. There is also no request limit.

You can support this and other projects by giving it a ⭐.

### Endpoint

Password-API's endpoint is at `https://api.notavirus.org/endpoints/password-api/`

End point gives you full access to the api.

### Customize

You can add url-parameters to customize the password

Available queries
- uppercase (adds uppercase letters to the password)
- lowercase (adds lowercase letters to the password)
- numbers (adds numbers to the password)
- special (adds special characters to the password)
- length (defines the length of the password)
  

## Response

The API will return responses in json:

```
{ "password" : "Vk0Vf^2dMsdU" }
```

## Example Code

```
fetch('https://api.notavirus.org/endpoints/password-api?type=numbers,uppercase,lowercase,speical&length=16')
.then((res)=> res.json())
.then((data) => console.log(data))
```

After resolving it will generate a 16 digit password with upper and lowercase letters, numbers and special characters.

## Info
This is a hobby/fun project, i will only fix major issues/bugs.
