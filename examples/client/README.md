# react/nextjs example

you will need a `.env` with a `NEXT_PUBLIC_RPC_URL` for this to work

all code here runs clientside, so you will have unpredictable speeds across devices but compute is offloaded to the user, so you never have to worry about your server crashing or crazy high server costs

`npm run dev` to start the app, all code is in a `"use client"` component so you know it only runs in the browser.