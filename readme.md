<h1>Postman</h1>

//Register//<br>
//body<br>
{
  "user": {
    "username": "aboba",
    "email": "delirius@mail.ru",
    "password": "98765"
  }
}<br>
//response<br>
{
    "user": {
        "username": "aboba",
        "email": "delirius@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNGVjMGEzM2NmNzA1MWIwMDgyYjBjOSIsInVzZXJuYW1lIjoiYWJvYmEiLCJleHAiOjE2NzEyODk1MDcsImlhdCI6MTY2NjEwNTUwN30.ChTJzH0f-GZVSbcQrIZduFZHQ6t4DsABDZj0Jup22-4"
    }
}<br>
//login//<br>
//body<br>
{
  "user": {
    "email": "delirius@mail.ru",
    "password": "98765"
  }
}<br>
//response<br>
{
    "user": {
        "username": "aboba",
        "email": "delirius@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNGVjMGEzM2NmNzA1MWIwMDgyYjBjOSIsInVzZXJuYW1lIjoiYWJvYmEiLCJleHAiOjE2NzEyODk2NzUsImlhdCI6MTY2NjEwNTY3NX0.2iGk0ECzsZTLbcIt6n8dF-e1kwbVgE40O4TdA1vGE3E"
    }
}<br>
//Get current user<br>
{
    "user": {
        "username": "aboba",
        "email": "delirius@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNGVjMGEzM2NmNzA1MWIwMDgyYjBjOSIsInVzZXJuYW1lIjoiYWJvYmEiLCJleHAiOjE2NzEyODk4MjMsImlhdCI6MTY2NjEwNTgyM30.d9Z1U9bvWVaaWPtVgLf87ivNy2hcpchtRuvQVM1SZJg"
    }
}