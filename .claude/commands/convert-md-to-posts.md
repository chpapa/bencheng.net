# Convert Markdown to Blog Post

Convert the provided markdown file to a blog post, place it in the `content/posts/` directory, and publish it via git.

## Input
The markdown file path is: $ARGUMENTS

## Steps

1. **First, get the current timestamp** by running: `date +%Y-%m-%dT%H:%M:%S+08:00` - save this output to use in the frontmatter
2. Read the input markdown file
3. Extract or determine the title from the content (usually the first H1 heading, or infer from filename)
4. Create the proper frontmatter in TOML format using `+++` delimiters, using the timestamp from step 1:
   ```
   +++
   draft = false
   date = [timestamp from step 1]
   title = "[extracted title]"
   description = ""
   slug = ""
   tags = []
   categories = []
   externalLink = ""
   series = []
   +++
   ```
5. If the markdown already has frontmatter (YAML with `---` or TOML with `+++`), convert it to the required TOML format above, preserving any existing values for title, description, tags, etc.
6. Generate the output filename:
   - Convert to kebab-case (lowercase, spaces/underscores replaced with hyphens)
   - Remove special characters
   - Keep `.md` extension
7. Write the converted file to `content/posts/[kebab-case-filename].md`
8. Run `git diff` to show the changes and ask the user to confirm before proceeding
9. After user confirms, run `git add` for the new post file
10. Run `git commit` with message: "Add new post: [post title]"
11. Run `git push` to publish the changes
12. Report completion with the new filename and git status

## Example

Input file: `My Great Article.md` with content:
```
# My Great Article

This is the content...
```

Output file: `content/posts/my-great-article.md` with content:
```
+++
draft = false
date = 2025-01-22T14:35:42+08:00
title = "My Great Article"
description = ""
slug = ""
tags = []
categories = []
externalLink = ""
series = []
+++

# My Great Article

This is the content...
```

Then git commit with message "Add new post: My Great Article" and push to remote.
