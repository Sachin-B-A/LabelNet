
<a name="readme-top"></a>

# LabelNet - Decentralized Freelancing Platform for Data Labeling

![Decentralized Freelancing Platform for Data Labeling]

<!-- Table of Contents -->
<details>
<summary>

# : Table of Contents

</summary>

- [Folder Structure](#folder-structure)
- [Getting Started](#toolbox-getting-started)
- [Screenshots](#camera-screenshots)
- [Tech Stack](#gear-tech-stack)
- [Features](#star-features)
- [Contribute](#raised_hands-contribute)
- [Acknowledgements](#gem-acknowledgements)
- [Buy Me a Coffee](#coffee-buy-me-a-coffee)
- [Follow Me](#rocket-follow-me)
- [Learn More](#books-learn-more)
- [Deploy on Vercel](#page_with_curl-deploy-on-vercel)
- [Give A Star](#star-give-a-star)

</details>

## : Folder Structure

Here is the folder structure of this app.

```bash
freelance-platform/
  |- app/
    |-- auth/
        |--- sign-in/
        |--- sign-up/
        |--- layout.tsx
    |-- root/
        |--- tasks/
            |---- [id]/update/
            |---- create/
        |--- payments/
        |--- profile/
        |--- layout.tsx
        |--- page.tsx
    |-- api/
        |--- uploadthing/
          |---- core.ts
          |---- route.ts
        |--- webhook/
          |---- solana/
            |----- route.ts
    |-- favicon.ico
    |-- globals.css
    |-- layout.tsx
  |- components/
    |-- shared/
    |-- ui/
  |- config/
    |-- site.ts
  |- constants/
    |-- index.ts
  |- lib/
    |-- actions/
        |--- task.actions.ts
        |--- payment.actions.ts
        |--- user.actions.ts
    |-- database/
        |--- models/
            |---- task.model.ts
            |---- payment.model.ts
            |---- user.model.ts
        |--- index.ts
    |-- uploadthing.ts
    |-- utils.ts
    |-- validator.ts
  |- public/assets/
    |-- icons/
    |-- images/
  |- types/
    |-- index.ts
  |- .env.example
  |- .env.local
  |- .gitignore
  |- components.json
  |- middleware.ts
  |- next.config.js
  |- package-lock.json
  |- package.json
  |- postcss.config.js
  |- tailwind.config.ts
  |- tsconfig.json
```

<br />



## :gear: Tech Stack

[![React JS](https://skillicons.dev/icons?i=react "React JS")](https://react.dev/ "React JS") [![Next JS](https://skillicons.dev/icons?i=next "Next JS")](https://nextjs.org/ "Next JS") [![Typescript](https://skillicons.dev/icons?i=ts "Typescript")](https://www.typescriptlang.org/ "Typescript") [![Solana](https://skillicons.dev/icons?i=solana "Solana")](https://solana.com/ "Solana") [![MongoDB](https://skillicons.dev/icons?i=mongodb "MongoDB")](https://mongodb.com/ "MongoDB") [![AWS](https://skillicons.dev/icons?i=aws "AWS")](https://aws.amazon.com/ "AWS")

## Getting Started

This is a Next.js project bootstrapped with `create-next-app`.

To start the development server, use one of the following commands:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## :star: Features

- **Crowdsourced Data Labeling** - Decentralized task allocation and labeling.
- **Crypto Payments via Solana** - Fast and secure payments with blockchain technology.
- **Secure Uploads** - User-uploaded content securely managed using AWS S3.
- **Global Accessibility** - Leveraging Web3’s decentralized framework.


