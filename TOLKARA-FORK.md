# Tolkara's downstream Wine fork

This branch (`tolkara/darwin-arm64`) is Wine, from bylaws' `upstream-arm64ec`
tree, with changes for running on arm64 Darwin (macOS and, under Tolkara,
iPadOS) without Rosetta. It is maintained by the Tolkara project
(https://github.com/tolkara) as a downstream fork.

**Not for upstream submission.** The changes on this branch were written
with an LLM-based coding tool. Wine's Clean Room Guidelines say: "Don't use
an LLM tool to generate code." Out of respect for that rule, nothing on this
branch is to be submitted to WineHQ, to bylaws' tree, or to any other
upstream. It exists only so that Tolkara can carry a Windows runtime while
the projects concerned settle how 32-bit and 64-bit x86 programs run on
arm64 Darwin. The commits follow Wine's coding style and one-change-per-commit
convention so that the branch stays reviewable and rebaseable, not to
prepare them for upstream.

Wine is LGPL 2.1 or later; see LICENSE. The changes here are under the same
licence.
