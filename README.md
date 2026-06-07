# compareAnilistsHTML
Compare the anime in common between [AniList](https://anilist.co) users' lists.

## Dependencies
* [Node.js](https://nodejs.org)

## Setup
Accessing AniList's API requires the [GraphQL](https://graphql.org/) Javascript module.
In the directory of installation, run
```
npm install
```

## Usage 
Open the **index.html** file (or an HTTP server that acesses it) with a browser.
In the *Number of users* field insert the number of users which list you want to compare and press *Submit*.  
Insert the usernames and press *Compare*.
Each user's list will be displayed under their username, and under those will be the list of all titles shared between the users.

You can change from *Title language* the language in which you want the titles to be displayed.
