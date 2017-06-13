# [TODO.TXT][todo] Bird's Eye View Reporter

Generates a textual report of pending and completed tasks in all projects and contexts.

## USAGE
```sh
todo.sh birdseye [todo.txt] [done.txt]
```

### USAGE NOTES

Expects two text files as parameters, each of which formatted as follows:

- One todo per line, ie, "`call Mom`"
- with an optional project association indicated as such: "`+projectname`"
- with the context in which the tasks should be completed, indicated as such: "`@context`"
- with the task priority optionally listed at the front of the line, in parens, ie, "`(A)`"

For example, 4 lines of todo.txt might look like this:

    +garagesale @phone schedule Goodwill pickup
    (A) @phone Tell Mom I love her
    +writing draft Great American Novel
    (B) smell the roses

The done.txt file is a list of completed todos from todo.txt.

## OUTPUT

Displays a list of:
- working projects and their percentage complete
- contexts in which open todos exist
- contexts and projects with tasks that have been prioritized
- projects which are completely done (don't have any open todos)

## [CHANGELOG]

[todo]: http://todotxt.com
[CHANGELOG]: CHANGELOG.md

## CONTRIBUTING

The [contributing guide](CODE_OF_CONDUCT.md) is a good place to start. If you have questions, feel free to ask.

## LICENSE

GPLv3 © [Gina Trapani][ginatrapani]

[ginatrapani]: https://github.com/ginatrapani
