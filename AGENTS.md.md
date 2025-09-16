# Agent Configuration (agent.md)

## Build / Lint / Test
- `npm run build` → compile project  
- `npm run lint` → run ESLint & Prettier checks  
- `npm run test` → run full test suite  
- `npm run test <file>` → run a single test file (e.g. `npm run test src/utils.test.ts`)  

## Code Style Guidelines
- **Imports**:  
  - Absolute imports preferred, group std → libs → local.  
  - One import per line.  

- **Formatting**:  
  - Prettier enforced, 2 spaces, semicolons required.  
  - Max line length: 100 chars.  

- **Types**:  
  - Use TypeScript strict mode.  
  - Always type function params & return values.  
  - Prefer `unknown` over `any`.  

- **Naming**:  
  - Variables camelCase, Classes/Components PascalCase, constants UPPER_SNAKE_CASE.  
  - Descriptive, no abbreviations.  

- **Error Handling**:  
  - Use `try/catch` with meaningful error messages.  
  - Never swallow errors — log or rethrow.  

## Purpose
This agent helps build stunning websites, design & implement **n8n automations**, and assist with **business operations** efficiently.
