# v1.5.0 (2016-12-02)

* Add support for manually numbered tables of contents and generation of
  table of contents pages.

# v1.4.3 (2016-12-02)

* Allow "proprietary" attributes through. `epub` prefixed attributes count as proprietary.

# v1.4.2 (2016-12-01)

* Include items in the spine on the basis of mime-type not chapter name.
  This let's us have HTML pages that aren't in the index but ARE in the
  spine.

# v1.4.1 (2016-11-13)

* Fix bug that was causing browsing order to not match table of contents
  order if chapters were added out-of-order.

# v1.4.0 (2016-10-09)

* Only pass content through normalizeXHTML if it has an XHTML mimetype.
* Allow zero as an index order value.

# v1.3.0 (2016-10-04)

* Author URLs are now included in such a way that Calibre will import them
* In `stream.newFile`: Make filename optional when content is a stream.
* Improve documentation around producing objects for Streampub to consume.

# v1.2.0 (2016-09-25)

* Added changelog ([@meinaart](https://github.com/meinaart))
* Added support for adding files/assets (for example images or stylesheets) ([@meinaart](https://github.com/meinaart))
* Support for cover image ([@meinaart](https://github.com/meinaart))
* Much improved documentation ([@meinaart](https://github.com/meinaart)) ([@iarna](https://github.com/iarna))
* The interface to newChapter was changed to match the documentation. ([@iarna](https://github.com/iarna))
* Added `setId` interface to match constructor option ([@iarna](https://github.com/iarna))
