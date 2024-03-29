# Commit Message Protocol

When making commits to this repository, please adhere to the following guidelines for writing commit messages:

1. Use the imperative mood:
   - Start the commit message with a verb in the imperative tense.
   - Examples: "Add feature", "Fix bug", "Update documentation".

2. Prefix your commit message with a commit type:
   - Use one of the following commit types:
     - **Feat**: For adding a new feature.
     - **Fix**: For fixing a bug.
     - **Docs**: For changes to the documentation.
     - **Style**: For style or formatting changes.
     - **Perf**: For improvements in code performance.
     - **Test**: For adding or modifying tests.

3. Limit the subject line to 50 characters:
   - Keep the subject line concise, ideally under 50 characters.
   - Use the subject line to provide a brief summary of your changes.

4. Separate subject from body with a blank line:
   - If the commit message requires a more detailed explanation, leave a blank line after the subject line and provide additional information in the body of the commit message.

5. Reference related issues or pull requests:
   - If the commit resolves or relates to any GitHub issues or pull requests, include references to them in the commit message body using GitHub's syntax (e.g., "Fixes #123").

Example Commit Message:

Feat: Add authentication middleware

This commit adds middleware to handle user authentication
using JSON Web Tokens (JWT). It includes routes for user
registration, login, and logout.

Fixes #123


