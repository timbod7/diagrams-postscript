1.1 (28 May 2014)
------------------

    - Changes to reflect `Measure` refactoring.
    - Allow `diagrams-core-1.2` and `diagrams-lib-1.2`
    - Allow `semigroups-0.15`
    - Allow `lens-4.2`
    - Allow `mtl-2.2`
    
1.0.2.4 (10 April 2014)
----------------------

    - Allow `semigroups-0.13`

1.0.2.2 (19 March 2014)
----------------------

  - Allow `lens-4.1`

1.0.2.1 (18 March 2014)
-----------------------

- Allow `dlist-0.7`

1.0.2 (8 March 2014)
--------------------

* **New features**

  - Experimental support for raw CMYK colors.

* **Dependency/version changes**

  - Allow `diagrams-core-1.1` and `diagrams-lib-1.1`.

1.0.1.2 (6 February 2014)
-------------------------

- require diagrams-lib >= 1.0.1 (for Hashable SizeSpec2D instance)

1.0.1.1 (30 January 2014)
-------------------------

- Work around a bug in GHC 7.4.2, which chokes when deriving Generic
  instances for associated data types.

1.0.1 (26 January 2014)
-----------------------

- Add `Hashable (Options Postscript R2)` instance

1.0.0.2 (1 January 2014)
------------------------

- allow semigroups-0.12

1.0.0.1 (30 November 2013)
--------------------------

- Allow dlist-0.6

1.0 (25 November 2013)
----------------------

- Add support for miter limit attribute.
- Use new command-line interface from `diagrams-lib`.
- Export `B` as an alias for `Postscript` token.

0.7.0.2 (27 September 2013)
---------------------------

* allow semigroups-0.11

0.7.0.1 (15 August 2013)
------------------------

* Fix deprecation warning

0.7: 9 August 2013
------------------

First release as an officially supported diagrams backend.

* Simple animation support.
* Upgrade to `monoid-extras-0.3`.
* Allow `base-4.7`.
