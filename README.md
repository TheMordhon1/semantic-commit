# semantic-commit


- **`<type>`**: Describes the kind of change you're making. This is mandatory.
- **`<scope>`**: Describes the part of the codebase the change affects. This is optional.
- **`<subject>`**: A brief summary of the change in the present tense. This is mandatory.

## Commit Types

1. **feat**: A new feature for the user, not a new feature for the build script.
   - Example: `feat: add user login functionality`

2. **fix**: A bug fix for the user, not a fix to the build script.
   - Example: `fix: resolve issue with user profile loading`

3. **docs**: Changes to the documentation.
   - Example: `docs: update API documentation`

4. **style**: Formatting, missing semi-colons, etc; no production code change.
   - Example: `style: format code with prettier`

5. **refactor**: Refactoring production code, e.g., renaming a variable.
   - Example: `refactor: rename 'user' to 'customer' in service layer`

6. **test**: Adding missing tests or refactoring tests; no production code change.
   - Example: `test: add unit tests for user service`

7. **chore**: Updating build tasks, package manager configs, etc; no production code change.
   - Example: `chore: update npm dependencies`

## Detailed Examples

### feat

- `feat(auth): add JWT authentication`
  - Adds a new feature related to authentication using JSON Web Tokens.

### fix

- `fix(cart): correct total price calculation`
  - Fixes a bug in the shopping cart where the total price was calculated incorrectly.

### docs

- `docs(readme): improve installation instructions`
  - Enhances the README file by providing clearer installation steps.

### style

- `style(lint): apply ESLint fixes`
  - Applies automatic code formatting changes made by ESLint, without changing any functionality.

### refactor

- `refactor(api): restructure API endpoint handling`
  - Improves the structure of API endpoint handling code, without changing its functionality.

### test

- `test(user): add integration tests for user creation`
  - Adds tests to ensure the user creation process works as expected.

### chore

- `chore(deps): update dependency versions`
  - Updates the versions of dependencies in the project, typically in `package.json` or equivalent.

## Benefits

1. **Clarity**: By using a consistent commit message format, you make it easier for others to understand the purpose of your changes.
2. **Automation**: Tools can be used to generate changelogs, release notes, and even automate versioning based on commit messages.
3. **History**: A well-maintained commit history helps in debugging and understanding the evolution of the codebase.

## Writing a Good Commit Message

1. **Use the present tense**: "Fix bug" not "Fixed bug" or "Fixes bug".
2. **Keep it concise**: Aim for around 50 characters for the subject.
3. **Capitalize the first letter**: Start with a capital letter for consistency.

By adhering to these guidelines, you ensure that your commit messages are informative, structured, and helpful for anyone working on the project now or in the future.
