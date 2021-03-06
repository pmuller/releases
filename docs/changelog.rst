=========
Changelog
=========

* :support:`15` Add :doc:`</concepts>` to flesh out some assumptions not
  adequately explained in :doc:`/usage`.
* :release:`0.3.0 <2013-11-21>`
* :feature:`11` Fix up styling so changelogs don't look suboptimal under `the
  new Read The Docs theme
  <http://ericholscher.com/blog/2013/nov/4/new-theme-read-the-docs/>`_. Still
  looks OK under their old theme too!
* :support:`0` Move to actual Sphinx docs so we can use ourselves.
* :support:`0` Created a basic test suite to protect against regressions.
* :bug:`9` Clean up additional 'unreleased' display/organization behavior,
  including making sure ALL unreleased issues show up as 'unreleased'. Thanks
  to Donald Stufft for the report.
* :feature:`1` (also :issue:`3`, :issue:`10`) Allow using ``-`` or ``0`` as a
  dummy issue 'number', which will result in no issue number/link being
  displayed.  Thanks to Markus Zapke-Gründemann and Hynek Schlawack for patches
  & discussion.

    * This feature lets you categorize changes that aren't directly related
      to issues in your tracker. It's an improvement over, and replacement
      for, the previous "vanilla bullet list items are treated as bugs"
      behavior.
    * Said behavior (non-role-prefixed bullet list items turning into
      regular bugs) is being retained as there's not a lot to gain from
      deactivating it.

* :release:`0.2.4 <2013.10.04>`
* :support:`0 backported` Handful of typos, doc tweaks & addition of a
  .gitignore file.  Thanks to Markus Zapke-Gründemann.
* :bug:`0` Fix duplicate display of "bare" (not prefixed with an issue role)
  changelog entries. Thanks again to Markus.
* :support:`0 backported` Edited the README/docs to be clearer about how
  Releases works/operates.
* :support:`0 backported` Explicitly documented how non-role-prefixed line
  items are preserved.
* :bug:`0` Updated non-role-prefixed line items so they get prefixed with a
  '[Bug]' signifier (since they are otherwise treated as bugfix items.)
* :release:`0.2.3 <2013.09.16>`
* :bug:`0` Fix a handful of bugs in release assignment logic.
* :release:`0.2.2 <2013.09.15>`
* :bug:`0` Ensured Python 3 compatibility.
* :release:`0.2.1 <2013.09.15>`
* :bug:`0` Fixed a stupid bug causing invalid issue hyperlinks.
* :release:`0.2.0 <2013.09.15>`
* :feature:`0` Basic functionality.
