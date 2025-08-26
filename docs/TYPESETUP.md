# TypeScript Setup and Fixes for medhelm-supplies

## Type Declarations

- `src/types/svg.d.ts`: Allows importing SVG files in TypeScript.
- `src/types/other-modules.d.ts`: Allows importing other common asset types (png, jpg, jpeg, gif).
- `src/vite-env.d.ts`: Enables support for `import.meta.env` with Vite.

## Asset

- `src/assets/medhelm-logo.svg`: Placeholder SVG logo. Replace with your real logo if needed.

## Required Dev Dependencies

After pulling these changes, **run the following command** to install required type definitions:

```
npm install --save-dev @types/express @types/nodemailer @types/jsonwebtoken
```

This ensures TypeScript can check your backend code using these modules.