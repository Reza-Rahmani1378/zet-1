# How to write better git commit message
A good commit should complete the following sentence
```
If applied, this commit <will your subject line here>
```
## Commit Sample

```
[type](optional scope): [subject]
[optional body]
[optional footer]
```

## Types
Must be one of the following:

* build - Build related changes
* ci - CI related changes
* chore - Build process or auxiliary tool changes
* docs - Documentation only changes
* feat - A new feature
* fix - A bug fix
* perf - A code change that improves performance
* refactor - A code change that neither fixes a bug or adds a feature
* revert - Reverting things
* style - Markup, white-space, formatting, missing semi-colons...
* test - Adding missing tests

## Scope
A scope may be provided to a commit’s type, to provide additional contextual information and is contained within parenthesis, e.g., feat(parser): add the ability to parse arrays.

## Subject
The subject contains a succinct description of the change:

Use the imperative, present tense: "change" not "changed" nor "changes"
No dot (.) at the end.

## Body
Just as in the subject, use the imperative, present tense: "change" not "changed" nor "changes". The body should include the motivation for the change and contrast this with previous behavior.

## The 7 rules of a great commit message:
1. Separate subject from the body with a blank line
1. Limit the subject line to 50 characters
1. Summary in the present tense. Not capitalized.
1. Do not end the subject line with a period
1. Use the imperative mood in the subject line
1. Wrap the body at 72 characters
1. Use the body to explain what and why vs. how

Tags:
```
#git #commit #commit_message
```
Related:
```
* https://dev.to/helderburato/patterns-for-writing-better-git-commit-messages-4ba0
```
