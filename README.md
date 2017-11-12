# hello-world
A sample repository.

Guidelines for commits from github.com\git-for-windows\git\wiki\Good-commits:

# Good commits

Please note that it is a best practice embraced by us to craft elegant, well-separated commits. Each commit is kind of its own little story, so if you make a typo fix, that is its own commit. If you add documentation, that is another commit. If you have multiple typo fixes, you could consider to put them into the same commit, depending on your taste.

In short, make sure that commits are *logical units of changes*.

# Commit messages

When it comes to the commit message, it is good practice to avoid repeating what is easily deduced from the code changes. Instead, try to describe ...

- ... the _why_ and the _what_ rather than the _how_;
- ... aspects of the solved problem or feature, that the reader might not be aware of;
- ... aspects that you would want any reviewer to know in addition to the actual code change.

If you made a change whose benefit is not obvious from reading the code changes associated with the commit, it is a wonderful idea to outline the benefit in the commit message.

When the commit is the result of a public discussion, it is good practice to summarize it and then add the hyper link to said discussion.

If you tried several strategies to solve your problem, you will want to describe what you tried and why it did not work, unless it appears too obvious in hindsight.

Also important:

- The commit message should always start with a single, short line summarizing the change.
- Sign off on your change (i.e. state that you release this patch as Open Source, if applicable with your employer's consent).
- Format the commit message to wrap at 76 columns per line.
