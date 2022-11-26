# ILLO

## database
- User
    - devise/_invitable

- Thread
    - user_id:integer
    - subject:string

- ThreadPost
    - user_id:integer
    - thread_id:integer
    - belongs_to: user
    - belongs_to: thread
