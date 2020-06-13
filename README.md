# Let's Eradicate Exclusive Terminology in Tech! :fist:

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)

<!-- PLEASE USE SEMANTIC LINE BREAKS IN THIS DOCUMENT: https://sembr.org/ -->

There are a number of words that we use
in software, hardware, engineering etc...
that can be interpreted with racist, sexist, violent or bigoted undertones.
And even if the original intent of these words are a completely different story,
encountering these terms without further context
can be harmful, offensive or triggering,
and have a negative impact on minorities
and other people with negative associations with the terms.

If we wish to be truly inclusive as an industry,
and let's face it, we know we've struggled...
we should do everything we can to change these terms everywhere we use them.

As Clockwork say [in their blog post](https://www.clockwork.com/news/creating-inclusive-naming-conventions-in-technology/):

> It’s not hard to see that associating positive things with “white”
> (like whitelisted) and negative things with “black” (like blacklisted) is,
> at worst, deeply offensive and at best entirely unnecessary.
> So let’s change it.

## [Pledge](PLEDGE.md)

If you would like to publically indicate your support of this initiative,
and take a pledge to commit to replacing excludive terminology wherever you can,
please feel free to submit a pull request
adding yourself to [this document](PLEDGE.md).

Any contributions are subject to our [Contributing document](CONTRIBUTING.md).

## Terms

### `master`

Used as the default branch in Git along with many other

**Alternatives:**

* `primary`
* `main`
* `default`
* `develop` (git)
* `trunk` (git)
* `stable` (git)

**Where are these changes happening?**

* **Git:**
  There is movement within the Git ecosystem
  to replace the default branch name `master` with alternatives.
  There is an [open issue on GitLab](https://gitlab.com/gitlab-org/gitlab/-/issues/221164),
  and [Nat Friedman has said on twitter](https://twitter.com/natfriedman/status/1271253144442253312)
  that GitHub is working on renaming the default branch.


Beyond this, it is already possible for you to change the default branch
of your repostories on GitHub
(and most other Git platforms).
Simply push a branch with the new name you would like,
and change repository settings.
If you have a lot of GitHub repositories to deal with,
[here is a tool to do it automatically using the API](https://github.com/lf-/splice_graft).

### `master` / `slave`

**Alternatives:**

Many of these alternatives provide an even clearer
and more accurate representation
of the relationship between different entities in a system:

* `primary` / `secondary`
* `leader` / `follower`
* `active` / `standby`, `failover`
* `primary` / `replica`
* `writer` / `reader`
* `coordinator`, `conductor`, `manager` / `worker`, `helper`
* `parent` / `child`, `helper`

**Where are these changes happening?**

* [Python](https://bugs.python.org/issue34605)
* [Go](https://go-review.googlesource.com/c/go/+/236857/)

### `blacklist` / `whitelist`

**Alternatives:**

* `blocklist`, `denylist` / `allowlist`, `permitlist`

**Where are these changes happening?**

* [Ruby on Rails](https://github.com/rails/rails/issues/33677)
* [Go](https://go-review.googlesource.com/c/go/+/236857/)
* [Angular](https://github.com/angular/angular/pull/28529)
* [Chromium](https://bugs.chromium.org/p/chromium/issues/detail?id=981129)

### `man in the middle`

**Alternatives:**

* `meddler in the middle`, `monster in the middle`

## FAQ

### Does this really matter?

If you care about inclusitivy... Yes.

### But the origin of these terms aren't racist?

The original intent of the terms does not change the impact it has on someone
when they see it without that context.

### What about breaking changes?

That's what [Semantic Versioning](https://semver.org/) is for!

If you have an API that uses these terms in it,
then to fully adopt these changes,
you'll need to change your API.
Like any breaking change,
you can depricate the old terms / symbols / parameters / etc...
and then remove them in the next major version bump!

We've been known to bump major versions of software
for smaller changes than this,
and this is totally worth it!

## Resources / Posts

You may find the following resources useful,
some of them have helped inspire this document:

* [IETF - Terminology, Power and Oppressive Language](https://tools.ietf.org/id/draft-knodel-terminology-00.html)
* [Clockwork - Creating inclusive naming conventions in technology](https://www.clockwork.com/news/creating-inclusive-naming-conventions-in-technology/)

## Social Media Posts

* [Aug 2018 - @andrestaltz](https://twitter.com/andrestaltz/status/1030200563802230786)
* [June 2020 - @leahculver](https://twitter.com/leahculver/status/1269109776983547904)

## Contributions

We welcome Pull Requests that:

* Sign the [pledge](PLEDGE.md).
* Add additional terms that should be avoided, with alternatives offered.
* Add examples of technical
  (software, hardware, engineering, etc...)
  projects or products
  that have decided to make these changes.
* Expand the FAQ or any other textual elements.

Please note that this project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md).
By participating in this project you agree to abide by its terms.
