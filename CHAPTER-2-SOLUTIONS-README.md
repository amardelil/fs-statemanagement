# Full Stack Open – Chapter 2 Solutions

Solutions for the six Chapter 2 exercises, using the supplied `fs-statemanagement` repository.

## Included exercises
1. **Unicafe revisited:** Zustand stores feedback; statistics calculate total, average, and positive percentage.
2. **Running tests:** Playwright tests are in `unicafe-tests`; GitHub Actions runs on pushes to `main`.
3. **Anecdotes, step 1:** Voting increments the selected anecdote's vote count in Zustand.
4. **Anecdotes, step 2:** An uncontrolled form adds new anecdotes.
5. **Anecdotes, step 3:** UI split into `AnecdoteList` and `AnecdoteForm`.
6. **Anecdotes, step 4:** Anecdotes sorted by descending votes with non-mutating `toSorted()`.

## Run Unicafe
```powershell
cd unicafe
npm install
npm install zustand
npm run dev
```
In another terminal:
```powershell
cd unicafe-tests
npm install
npx playwright install chromium
npm test
```

## Run Anecdotes
```powershell
cd anecdotes
npm install
npm run dev
```

The supplied test folders and repository files are retained. If `npm ci` reports a lockfile mismatch, run `npm install` in the affected project to regenerate its lockfile. Review the code and understand the state updates before submitting coursework.
