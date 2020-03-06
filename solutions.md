# APP

## app.js

- Line 10 - missing comma (h/t to Brooke)

# MODELS

## models/conn.js

- NO ERRORS

## models/parks.js

- Line 34 - missing return statement

## models/users.js

- Line 2 - missing bcrypt import
- Line 20 - missing underscore in `first_name`

# VIEWS

## views/partial-index

- Line 9 - missing closing `}`

## views/partial-login.html

- Line 1 - Wrong action URL `/users/login`

## views/partial-signup.html

- Line 1 - Wrong action URL `/users/signup` (not _SINGup_)

## views/partial-single-park.html

- Line 7 - missing opening backtick `

## views/template.html

- Line 20 - added `>>`

# CONTROLLERS (ROUTERS)

## routes/index.js

- Line 3 - missing Parks Model import

## routes/parks.js

- Line 14 - incorrect partial name

## routes/users.js

- Line 2 - misspelled `bycrypt`
- Line 46 - typo in `user.addUser()`
