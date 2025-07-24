# git-commit
You are given the following context:
$ARGUMENTS

Create a structured git commit for the current changes.

**Process:**
1. Analyze the staged changes using `git diff --staged`
2. Identify the type and scope of changes
3. Generate a commit message following conventional commits format

**Commit Message Structure:**
```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

**Types:**
- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- style: Changes that do not affect the meaning of the code
- refactor: A code change that neither fixes a bug nor adds a feature
- perf: A code change that improves performance
- test: Adding missing tests or correcting existing tests
- chore: Changes to the build process or auxiliary tools

**Guidelines:**
- Use the imperative mood in the subject line
- Keep the subject line under 50 characters
- Capitalize the subject line
- Do not end the subject line with a period
- Use the body to explain what and why vs. how

**Steps:**
1. Run `git diff --staged` to analyze changes
2. Determine the appropriate commit type and scope
3. Write a clear, concise commit message
4. Include body text if additional explanation is needed
5. Add any relevant footers (breaking changes, issues closed)

**Example:**
```
feat(auth): add OAuth2 integration

Implement Google OAuth2 authentication flow with proper
token handling and user session management.

Closes #123
```