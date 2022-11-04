# React Query

This repository is focused on React Query

## Changelog
**React Query 4.0 (TanStack Query)**
1. Imports: `@tanstack/react-query` instead of `react-query`
2. Query keys are now arrays instead of strings
3. devtools are now installed separately and imported from `@tanstack/react-query-devtools`
4. setLogger was removed. Logger is now aded as a QueryClient option
5. onSuccess is no longer called from setQueryData