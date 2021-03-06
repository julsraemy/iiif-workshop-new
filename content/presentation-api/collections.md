---
title: "Collections"
date: 2018-04-15T14:53:52-04:00
weight: 120
---

Collections group separate IIIF manifests. Institutions have taken a couple of different approaches to creating collections.

<!-- #backlog:540 comment on permanence of collections? -->

## Approaches

### Newspapers

http://universalviewer.io/uv.html?manifest=http://dams.llgc.org.uk/iiif/newspapers/3100020.json

You can open a [truncted version of this manifest](/manifests/collection-newspapers-truncated.json).

Note the use of the `navDate` which the viewer can use to order the manifests by date.

<!-- #backlog:170 add something more about navDate -->

### Curated

Papers of [Michael Collins][collins] (1890-1922)
https://data.ucd.ie/api/img/collection/ivrla:10905

### Facets

https://wellcomelibrary.org/service/collections/

### Search

[NCSU Libraries collection][ncsu]

## Examples

You can see some of the top-level collections that have been published here:

- [JSON file containing some of the IIIF Universe](https://github.com/ryanfb/iiif-universe/blob/gh-pages/iiif-universe.json)
- [spreadsheet collecting collections](https://docs.google.com/spreadsheets/d/1apQKFkfBV89BvycaBPN6v-LjeaKaVVMaMUsY6L4KRJo/edit)

<!-- #backlog:260 consider how to talk about how UV handles paged collections http://universalviewer.io/uv.html?manifest=https://d.lib.ncsu.edu/collections/catalog/manifest/page?f%5Bispartof_facet%5D%5B%5D=Nubian+Message&page=1&per_page=20 -->

[collins]: https://en.wikipedia.org/wiki/Michael_Collins_(Irish_leader)
[ncsu]: https://d.lib.ncsu.edu/collections/catalog/manifest?f%5Bispartof_facet%5D%5B%5D=Nubian+Message&page=1&per_page=20
