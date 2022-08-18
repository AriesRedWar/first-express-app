# Project REST-Rant
-----------------
TBD - Summary



## Routes
-----------------

| Method | Path | Purpose |
|--------|------|---------|
| GET    | /    |Home page|
| GET    | /places  |Places index page|
| GET    | /places  |Create new place|
| GET    | /places/new  |Form page for creating a new place|
| GET    | /places/:id  |Details about a particular place|
| GET    | /places/:id  |Update a particular place|
| GET    | /places/:id/edit  |Form page for editing an existing place|
| GET    | /places/:id  |Delete a particular place|
| GET    | /places/:id/rant  |Create a rant (comment) about a particular place|
| GET    | /places/:id/rant/:rantId  |Delete a rant (comment) about a particular place|
| GET    | *   |404 page (matches any route not defined above)|

## Database
-------------------
#### places

| field | Type |
|-------|------|
| Name  | (string) |
| City  | (string) |
| Cuisines | (string) |
| Pic | (string) |
