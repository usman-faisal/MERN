# MERN

fullstack webapp with user authentication

## installation for client

`cd client`
`npm install`
`npm run dev`

make sure to add these env variables.

1. GOOGLE_CLIENT_ID
2. GOOGLE_CLIENT_SECRET
3. GITHUB_ID
4. GITHUB_SECRET

**cd server && npm install**

# run backend

**cd server && npm run dev**

# run react frontend

**cd client && npm run start**

# MongoDB local installation

Head over to https://www.mongodb.com/try/download/community and install community version of mongo db
after installation.. open mongodb compass, and find out the default port where the server would be running.
go to index.ts file in server folder and adjust mongo db url in line # 6
