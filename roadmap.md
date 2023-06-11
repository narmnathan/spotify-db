modules:

-- implementing user-login and initializing database file
-- interacting with spotify api and obtaining user data

database tables:
-- user_info: user_id, username, password
-- login_info: user_id, spotify_username, spotify_password, auth_token

ideally:
client creates user profile on app -> authorizes with spotify -> retrieves all liked songs

to start:
one user -> one login -> create authorization functionality and load database first

databases:
-- private: user app login, user spotify login
connecting: 