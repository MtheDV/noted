# Noted
A simple note-taking web application inspired by my lifestyle, to help me potentially better keep track of my life.

## Design guidelines
1. Focus on simplicity and minimalism
2. Ensure that it can be used on both mobile and desktop devices with ease

## Development guidelines
1. Avoid doing it all from scratch, this is a personal project so do what's simple
2. Write clean code, there's no room to cut corners
3. Each area should be sectioned into their own modules, why?
   - Group together common areas of the codebase for easier navigation
   - Less cross-app changes required avoiding conflict with other developers
   - A "flatter" code-base requiring less nesting
4. The application should be designed simply enough such that an AI could go through and make changes without causing bugs/issues
5. Components must be PascalCase and folders must be kebab case

### Example
1. Editor module contains the components, stores, composables, etc required to manage the editor
2. The globals module contains shared components, stores, composables, etc that are shared across other modules

## Development tools
1. TipTap editor, for easy WYSIWYG editing
2. Pinia, for state management
3. Pinia Colada, for the data fetching and updating layer
4. VueUse, for pre-made composables
5. Supabase, for API and data storage and user authentication
