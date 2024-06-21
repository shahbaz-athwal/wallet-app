- Clone the repo

```jsx
git clone https://github.com/shahbaz-athwal/wallet-app
```

- npm install
- Run postgres either locally or on the cloud (neon.tech)

```jsx
docker run  -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
```

- Copy over all .env.example files to .env
- Update .env files everywhere with the right db url
- Go to `packages/db`
    - npx prisma migrate dev
- Go to `apps/user-app` , run `npm run dev`
