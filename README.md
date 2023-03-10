# CodeLib
CodeLib is an ai that generates answers related to programming and it even help you by generating specific code or syntax that will help you in you developement. CodeLib even understand code and it can even explain you the given input code by the user. Users can ask step-by-step methods to solve any programming query. Users can ask for even easy to understand code or steps like asking anything and ending with explain it to me like i am 5 years old . CodeLib is build in Javascript (Vanilla Js) using OpenAI API that helps generating the response to the questions and requests.

#
![codelib](https://user-images.githubusercontent.com/81036521/224355588-69e8b89a-604a-40f2-9a96-2392474c0a31.JPG)

#

## Documentaion for users to edit and use it at local server.

To run the server in local server.

create an .env file in server folder and enter :

> ```OPENAI_API_KEY = "YOUR_OPENAI_API_KEY"```

You can get the api key from openai officail wesite : [OpenAI API](https://platform.openai.com/account/api-keys)

After implementing the changes in server folder go to terminal > go to the server folder in the project > Type Command :

```
  npm install or npm i
  npm run server
```
your server is running and will be available on localhost:5000

To run the Frontend / Client side :

Do some changes first :

Go to file : `client > script.js`

change the server link to the local host link

```
// fetch data from server -> bot's response

  const response = await fetch('http://localhost:5000', {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json'
    },
    body: JSON.stringify({
      prompt: data.get('prompt')
    })
  })
 ```
 
 Then open terminal > Go into the client folder in the project > Type the command :
 ```
  npm install or npm i
  npm run dev 
```

Now the client site is running no local server too

it may be runnig no this local host http://127.0.0.1:5173/ or can be another 

#

The scroll feature in OpenAi may be having some bug or glitch. if you find any thing regarding this share. will be a great help.

Have Fun 😉
