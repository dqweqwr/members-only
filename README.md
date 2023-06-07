models needed:
  -Post:
    title: string
    body: text
    belongs_to: user

  -User:
    name: string
    email: string
    password: string
    has_many: posts

-Generate a controller for posts
  -Only new, create, and index routes
