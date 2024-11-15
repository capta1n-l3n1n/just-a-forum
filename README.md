# Just a forum(JAF) - Fullstack Reddit Clone

Built with the Next.js App Router, TypeScript & TailwindCss

## Getting started

To get started with this project, run

```bash
  git clone https://github.com/capta1n-l3n1n/just-a-forum.git
```

and copy these .env.example variables into a separate .env file:

```bash
DATABASE_URL=
NEXTAUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

REDIS_URL=
REDIS_SECRET=
```

if you'd like, you can paste this snippet for quick component creation (optional):

```typescript
// vscode settings -> user snippets -> typescriptreact.json
```

```json
"Typescript React Function Component": {
    "prefix": "fc",
    "body": [
      "import { FC } from 'react'",
      "",
      "interface ${TM_FILENAME_BASE}Props {",
      "  $1",
      "}",
      "",
      "const $TM_FILENAME_BASE: FC<${TM_FILENAME_BASE}Props> = ({$2}) => {",
      "  return <div>$TM_FILENAME_BASE</div>",
      "}",
      "",
      "export default $TM_FILENAME_BASE"
    ],
    "description": "Typescript React Function Component"
  },
```
