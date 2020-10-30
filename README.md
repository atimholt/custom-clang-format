My Custom .clang-format
=======================

This project is intended to be a “playground” for working out my `clang-format`
preferences. It may grow in scope.

Copious use of git is planned for the purposes of comparisons, so the “fullest”
version of this project includes many git branches, rather than any given
revision or changeset.

—Or it might not. I might just go through each setting one by one and pick
whatever, and potentially be done. Whatever happens happens. 🤷

What might happen—I could create tags or branches that tweak my settings for
different purposes or environments. Dunno—this is a really casual repo.

Why Should You Care?
--------------------

I hope that the way I've laid out my `.clang-format` file is helpful to others
who also balk at the mess that a flat, *mostly* alphabetical `yaml` file is for
the kinds of people who desire to edit such things manually.

Aside from structural comments, you may also find meaningful explanations for
certain choices made (if I've felt any were necessary). Whether or not I
actually have any such comments, I think a `.clang-format` file is the perfect
place to explain project formatting decisions. That is, if anyone deems such
justification to be worth writing comments about—allowing coding standards to
speak for themselves is also a viable route.

At a future date, it's possible I will add a script or program to be wrapped
around invocation of `clang-format` to overcome some of `clang-format`'s
shortcomings. It's no secret that `clang-format` is extremely limited, but this
is usually justified by noting that it's much more important to simply stop
bikeshedding code formatting and get relatively good results.

—However, if this bikeshedding is compartmentalized into its own highly casual
side project with very low aspirations, the owner of the project (or a fork of
it) can tweak bits and justify whatever they want at their leisure, and arrive
at whatever solution they want for their own “green field” projects (or for
their “who hired this guy?” ill-conceived, dumb standards they've decided to
make their co-devs/underlings suffer, as the case may be). With enough
accumulated free-time bikeshedding, they may arrive at a more robust solution
that they'd be happy to use in commit hooks without creating sad, lumpy, mushy
parameter lists (as an example) littering their code.

<!-- vim: set tw=80 noet ts=4 sw=0 sts=0 : -->
