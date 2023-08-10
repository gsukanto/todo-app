Todo app for testing AWS Amplify Studio and Figma.

## Getting Started

First, setup the Amplify CLI:

```bash
npm install -g @aws-amplify/cli
amplify configure
```
https://docs.amplify.aws/cli/start/install/

Then create a new Amplify project:

```bash
amplify init
```
https://docs.amplify.aws/cli/start/workflows/#amplify-init

Using the Amplify Studio link the Figma project to the Amplify project.
https://docs.amplify.aws/console/uibuilder/figmatocode/

Then pull the Amplify project:

```bash
amplify pull
```
This will create the /ui-components folder with the components generated from the Figma project.

To run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

