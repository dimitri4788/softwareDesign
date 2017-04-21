# How to Write a Git Commit Message

### Why good commit messages matter
A well written Git commit message is the best way to communicate context about a change to other developers. A diff will tell you what changed, but only the commit message can properly tell you why.

### Rules of a good Git commit message
- Limit the subject line to 50 characters
- Separate subject from body with a blank line
- Capitalize the subject line
- Do not end the subject line with a period
- Use the imperative mood in the subject line
- Wrap the body at 72 characters
- Use the body to explain what and why vs. how

**A Model Git commit message:**

``` bash
Short (50 chars or less) summary of changes

More detailed explanatory text, if necessary.  Wrap it to
about 72 characters or so.  In some contexts, the first
line is treated as the subject of an email and the rest of
the text as the body.  The blank line separating the
summary from the body is critical (unless you omit the body
entirely); tools like rebase can get confused if you run
the two together.

Further paragraphs come after blank lines.

- Bullet points are okay, too

- Typically a hyphen or asterisk is used for the bullet,
followed by a single space, with blank lines in
between, but conventions vary here

For an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```
