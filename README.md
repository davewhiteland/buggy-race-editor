# Proto-buggy-racing-editor repo

This is a copy of the GitHub repo
[buggyrace/buggy-race-editor](https://github.com/buggyrace/buggy-race-editor).

The Buggy Race Editor is the part of the [Buggy Racing
project](https://www.buggyrace.net) that the students start with. That is, at
the start of the project, students start with a copy of the Buggy Editor source
code — it's a Python Flask application.

That repo — being that it's something students may be encouraged to fork — is
something of a special case regarding its (commit) history. It's really an
asset that will exist within each students' project. As such, anything other
than a single "initial commit" in its history is at best irrelevant and at
worst confusing. Similarly, there should be no branches in it.

(Whether or not students use version control in the Buggy Racing project is
optional; it depends on how the teachers/tutors are running the project.)

For now I'm keeping **this repo** with some history of how the editor has
changed. This is currently the real "source" of the contents of the
single-commit `main` branch in
[buggyrace/buggy-race-editor](https://github.com/buggyrace/buggy-race-editor).
A snapshot of _that_ commit is what's used inside the latest version of the
race server (at
[buggyrace/buggy-race-server](https://github.com/buggyrace/buggy-race-server)).

I _think_ it's more confusing to have this repo in the `buggyrace` account,
because it's only of use to developers who are working on the project itself.
Hence this copy here, in my personal account.

## Branches

* `main`  
This `README.md` is the only file in "orphan branch" `main` so it appears here
on the GitHub repo page.

* `snapshot`  
The "clean" latest version of the repo which will always be lying about its
history by claiming one "initial commit". Ideally this is attributed to an
author that won't confuse students.

* `development` (and others)  
Where the changes are compounded — including specific changes from other
sites, e.g., the things we did for the `rhul-2024-25-term-3` run which we've
brought back into the main project.

## Buggy Racing Links

* [full project documentation](https://www.buggyrace.net/)
* [demo site at `demo.buggyrace.net`](https://demo.buggyrace.net/)
* ["Buggy Race" on GitHub](https://github.com/buggyrace)
   * [`buggy-race-server`](https://github.com/buggyrace/buggy-race-server)
   * [`buggy-race-editor`](https://github.com/buggyrace/buggy-race-editor)
   * [`buggy-race-about`](https://github.com/buggyrace/buggy-race-about)

