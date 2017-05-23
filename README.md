# Author

Created by Qian Shao

# FreeCodeCamp API Projects: URL Shortener Microservice
## 用户故事：
1. 用户在浏览器输入该地址时，把一个合法的 URL 作为参数，返回一个 JSON 格式的段地址
2. 如果用户输入的是一个无效的 URL 地址（不符合 http://www.example.com 格式）作为参数，则返回错误
3. 如果用户输入前边生成的段地址，则会重定向到相应的合法地址

## Example creation usage:

```js
https://shurli.herokuapp.com/new/https://www.google.com 
https://shurli.herokuapp.com/new/http://freecodecamp.com/news
```

## Example creation output:

```js
{ "original_url": "http://freecodecamp.com/news", "short_url": "https://shurli.herokuapp.com/4" }
```

## Usage:

`https://shurli.herokuapp.com/4`

### Will redirect to:

`http://freecodecamp.com/news`
