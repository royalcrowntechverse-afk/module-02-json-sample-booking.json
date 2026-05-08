### Get Octocat's GitHub profile
GET https://api.github.com/users/octocat

###
### Create a test post
POST https://jsonplaceholder.typicode.com/posts
Content-Type: application/json

{
  "caller_name": "Royalcrown",
  "appointment_requested": true
}

###
### Get Nigeria weather (authenticated)
GET https://api.openweathermap.org/data/2.5/weather?q=Nigeria&appid=cfd8ca99da2b14f0d59b5b88444c89eb
