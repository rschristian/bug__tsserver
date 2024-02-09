# Instructions

1. Clone repo
2. Install dependencies
3. Open `src/index.tsx`
4. Notice `Cannot find name 'React'` error, despite having configured JSX to use Preact in the `tsconfig.json`
5. Attempt to jump to config file
    - Depends on the editor/keybindings
6. Notice no config is loaded

7. Rename `index.tsx` to anything else
    - `mv src/index.tsx src/not-index.tsx`
8. Notice the error is resolved
