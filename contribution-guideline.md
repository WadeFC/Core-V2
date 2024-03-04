# GIT GUIDELINES

## How We Contribute

- Clone the repository
- Create a new branch (Always work from a personal branch)
- NEVER EVER PUSH TO MAIN BRANCH

## **How We Name Branches:**
- When writing a branch name, using hyphen (-) increases the readability of the name.
### Example
feature-user-management

- Begin the name of a branch with a category word, which indicates the type of task that is being solved with that branch:

| Syntax      | Description |
| ----------- | ----------- |
| hotfix      | for quickly fixing critical issues, usually with a temporary solution       |
| bugfix      | for fixing a bug |
| feature      | for adding, removing or modifying a feature |
|  test  | for experimenting something which is not an issue |

_______________________

## **How We Commit:**

### **Always commit changes in files separately**

This approach makes it easier to isolate and fix problems and also makes it easier to review changes as each commit only contains changes to one file.

Except in cases where changes to different files are related and should be committed together as a single unit of work. 

This approach makes it easier to see the changes as a whole and understand their purpose and impact. 

It's also useful when changes to multiple files are required to complete a feature or fix a bug.

In general, it's a good idea to aim for small, focused commits, but if related changes to multiple files are required to complete a task, it's okay to commit them together. 

The key is to be consistent and make sure your commits are clear, concise, and meaningful, with a descriptive message that accurately reflects the changes being made.

### **How we write commit messages**

A well-crafted Git commit message is the best way to communicate the purpose of a change to the codebase.

Here are some guidelines to help you write clear, concise, and meaningful Git commit messages:

#### **Keep the title short and descriptive:** 
The title should be in the title case; no more than 50 characters and should clearly describe the change being made.

**ALWAYS** Use a prefix in the commit title:

| Syntax      | Description |
| ----------- | ----------- |
|"feat:" |for a new feature|
|"fix:" |for a bug fix |
|"ref:" | for a code refactoring |
|"chore:" | for maintenance tasks such as dependency updates, build process improvements, etc.|

#### **Use the body to explain the details (if need be):** 
The body of the commit message can provide a more detailed explanation of the change (if need be), including any relevant context and reasoning behind the change.

#### **Use the imperative mood**: 

Write the title and body of the commit message in the imperative mood, as if you were giving a command to the codebase, and use the appropriate prefix. For example, "fix: display login page correctly" instead of "fixed a bug in the login page."
Keep the commit atomic: Each commit should represent a single, self-contained change. Avoid making multiple unrelated changes in a single commit.
