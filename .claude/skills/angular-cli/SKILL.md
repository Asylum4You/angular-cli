```markdown
# angular-cli Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches you the core development patterns and conventions used in the `angular-cli` TypeScript codebase, built with the Angular framework. You'll learn about file naming, import/export styles, commit message conventions, and how to write and organize tests. This guide is designed to help you contribute effectively and maintain consistency within the project.

## Coding Conventions

### File Naming
- Use **camelCase** for file names.
  - Example: `myComponent.ts`, `buildUtils.ts`

### Import Style
- Use **relative imports** for referencing modules within the repository.
  - Example:
    ```typescript
    import { myFunction } from './utils';
    ```

### Export Style
- Use **named exports** for all modules.
  - Example:
    ```typescript
    export function buildProject() { ... }
    export const VERSION = '1.0.0';
    ```

### Commit Message Convention
- Follow the **conventional commit** format.
- Use prefixes like `build`.
- Example:
  ```
  build: update TypeScript to version 4.5.0
  ```

## Workflows

_No explicit workflows detected in the repository._

## Testing Patterns

- **Test Framework:** Unknown (not specified in the repository)
- **Test File Pattern:** All test files follow the `*.test.*` naming convention.
  - Example: `myComponent.test.ts`
- **Test Example:**
  ```typescript
  // myComponent.test.ts
  import { myComponent } from './myComponent';

  describe('myComponent', () => {
    it('should do something', () => {
      expect(myComponent()).toBe(true);
    });
  });
  ```

## Commands
| Command | Purpose |
|---------|---------|
| /build  | Run the build process (suggested) |
| /test   | Run all tests (suggested) |
```