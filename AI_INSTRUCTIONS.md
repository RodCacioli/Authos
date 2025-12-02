# IMPORTANT: DO NOT MODIFY THESE CONFIGURATIONS

## CRITICAL: Package Dependencies
**DO NOT CHANGE** the following dependency in `package.json`:
- `"@google/genai": "latest"` - This is intentionally set to "latest" and must remain as is. Do not change it to a specific version or replace it with `@google/generative-ai`.

## CRITICAL: Build Script Configuration
**DO NOT MODIFY** the build script in `package.json`:
- The build command is: `"build": "tsc --noEmit || true && vite build"`
- This configuration intentionally ignores TypeScript errors during build to allow the build to complete successfully.
- Do not remove the `|| true` part or change the build command structure.

## CRITICAL: TypeScript Configuration
**DO NOT MODIFY** these settings in `tsconfig.json`:
- The `"exclude": ["vite.config.ts"]` entry must remain to prevent build conflicts.
- Do not remove this exclusion or modify the include/exclude patterns.

## CRITICAL: Git Ignore Configuration
**DO NOT MODIFY** the `.gitignore` file, especially:
- The `.env` and `.env.*` entries that prevent environment variables from being committed.
- These are intentionally configured for security purposes.

## General Rule
When making changes to this project, preserve all manual configurations and build optimizations. Do not "fix" or "improve" these specific settings as they are intentionally configured this way.

