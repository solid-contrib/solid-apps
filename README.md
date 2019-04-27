# solid-apps
[![](https://img.shields.io/badge/project-Solid-7C4DFF.svg?style=flat-square)](https://github.com/solid/solid)

List of apps built on and/or implementing the [Solid platform](https://github.com/solid/solid-spec). 
[Add yours!](https://github.com/solid/solid-apps/blob/master/How-to-add-an-App.md)

## Registration / Sign up / Identity

- [Find Solid Pods](https://findsolidpods.com)
- [OpenLink YouID](http://youid.openlinksw.com) -- Identity and Credentials Doc Generator; creates X.509 
  cert, saves WebID-Profile Doc (in any Solid Pod), and sets up the relations required for WebID-TLS and 
  WebID-TLS+Delegation

## Personal Data Apps

- [Solid Focus](https://noeldemartin.github.io/solid-focus/) -- task manager app
- [Tiddlywiki](https://bourgeoa.solid.community/public/tiddlywiki/) -- with Solid syncadaptor 
  [github](https://github.com/bourgeoa/tiddlywiki-node-solid-server)
- [Markbook](https://github.com/mark-book/markbook/blob/gh-pages/README.md) -- Bookmarking
- [Solid POD Form Integration](https://www.formrouter.com/solid-project-pod-pdf-form-integration/online_forms_solid_pod.htm) submit online form data to PODs

## Sample/Tutorial Apps

- [Solid Hello World (demo app)](https://github.com/melvincarvalho/helloworld/)
- [SPARQL Fiddle](https://jeff-zucker.github.io/sparql-fiddle/) -- online fiddle to run SPARQL against Solid Pods

## Social Media / Blogging / Collaborative Apps

- [dokieli](https://github.com/linkeddata/dokieli) --
    decentralized article authoring, annotation, and social notification tool
- [Plume](https://github.com/theWebalyst/solid-plume/) -- client side blogging platform. [How to deploy](https://thewebalyst.solid.community/plume/?post=https%3A%2F%2Fthewebalyst.solid.community%2Fpublic%2Fposts%2F%2F1555171264494-how-to-deploy-plume-blog-on-your-solid-pod.ttl%23%23%23%23%23%23%23%23%23%23%23%23%23%23)
- [Twee-Fi](https://github.com/factsmission/twee-fi) -- review claims
    and rate trustworthyness of tweets [try it out](https://factsmission.github.io/twee-fi/)

## Games

- [Solid Chess](https://github.com/pheyvaer/solid-chess) -- Chess game for the browser and terminal

## Smart agents / bots

- [OpenLink Smart Data Bot (OSDB)](http://osdb.openlinksw.com) -- service that distills Actions from API Documentation 
  constructed using RDF or OpenAPI; supports WebID-OIDC for authentication

## Developer tools / file managers

- [Solid IDE](https://jeff-zucker.github.io/solid-ide/) -- file manager and IDE
- [Solid Shell](https://github.com/jeff-zucker/solid-shell) -- command-line tool and interactive shell
- [OpenLink Structured Data Editor (OSDE)](http://osde.openlinksw.com) -- RDF Editor with a "Save As" feature that 
  can save content to any Solid Pod
- [OpenLink Structured Data Sniffer (OSDS)](http://osds.openlinksw.com) -- extracts Metadata (in a variety of notations) 
  from HTML docs and enables storage to any Solid Pod via "Save As" feature
- [URIBurner](http://linkeddata.uriburner.com/sparql) -- SPARQL Query Service Endpoint that supports WebID-OIDC 
  for authenticating WebIDs en route to functionality that isn't granted to the un-authenticated Public; e.g., 
  "generating descriptions of any Web-Accessible Document in RDF, and publishing said description in 5-Star 
  Linked Data form"
- [Warp](https://github.com/linkeddata/warp) -- file browser
- [File Extractor for PODs](https://github.com/dconorozzo/Solid-RDF-HexBin-File-Extraction) extract files from POD data

## Libraries & components

- [Solid authorization Widget](https://github.com/bourgeoa/solid-file-widget) -- component for webapp 

### Experimental

- [Get tokens](https://github.com/wrmack/Get-tokens) -- demonstrates token exchanges in a native iOS app 
- [RDF-iOS](https://github.com/wrmack/RDF-iOS) -- demonstrates accessing `rdflib.js` in iOS 

## Apps that need updating

- [Solid Signup app](https://github.com/solid/solid-signup) -- for creating
    WebID accounts with Solid-compatible providers. databox.me is currently not accepting new users
- [Contacts manager (for vCards)](https://github.com/linkeddata/contacts) --
      (AngularJS, mobile friendly). Needs updating in order to work with the currently deployed version of node solid server
- [Inbox](https://github.com/solid/solid-inbox/) -- notifications/messages app. Does not support WebID-OIDC
- [WebID Profile editor](https://github.com/linkeddata/profile-editor) -- Does not support WebID-OIDC
- [Tadanime](https://github.com/pheyvaer/tadanime) -- app to rate your anime series and movies; ([live instance](https://pheyvaer.github.io/tadanime/index.html))  Does not find data, unclear how to use it
- [Cimba](https://github.com/linkeddata/cimba) -- microblogging app. Not updated for years and not working with current servers.
- [Markdown Editor](https://github.com/melvincarvalho/markdown-editor) -- markdown
    editor; Login not working
- [Meeting scheduler](https://github.com/linkeddata/app-schedule) --
    (similar to [Doodle](http://doodle.com/)); abandoned
- [Pad](https://github.com/timbl/pad) -- collaborative notes; not updated for years
- [Timeline](https://github.com/solid-social/timeline) -- decentralized social
    network; only works with WebID-OIDC
- [2048](http://github.com/webize/2048) -- Tile based puzzle game 2048; Login does not work
    
## App Wishlist

### Core Solid Apps Wishlist

- [ ] Admin app - when you launch a Solid server and visit the root URL,
    this is the app that gets served by default. Shows the status of the
    server, allows Admin users to edit/remove profiles, etc.

- [ ] Dashboard app

- [ ] People/Group Picker + ACL Manager

- [x] Profile editor
    [profile-editor](https://github.com/linkeddata/profile-editor)

- [x] Signup app / initial profile creation.
    ([solid-signup](https://github.com/solid/solid-signup))

- [ ] Welcome app - when users first sign up for a WebID account, they are
    redirected to this app. Provides links/docs/introduction to the Solid
    platform.
    (see [solid/solid/issues/18](https://github.com/solid/solid/issues/18))

### General Wishlist
Wishlist items/suggestions go here.

* Backup Manager (tar/gzip your account's data, for download, storage on S3/Glacier, etc.)

* Calendar app (e.g., [example1](http://ui.toast.com/tui-calendar/))

* Chat app

* Check-in/Location app (with GPS annotations)

* Clone of 750words.com

* Clone of [jspaint](https://github.com/1j01/jspaint)

* Clone of markdown app: https://tobloef.com/markant/

* Clone of mind map app: https://tobloef.com/text2mindmap/

* Collection Manager (books, movies, games, etc.)

* Consensus app - create decisions (similar to a Poll),
  invite people/teammates to participate,
  comments and discussion, vote on the outcome (simple majority or
  runoff voting)

* Disqus clone

* Ephemeral/temporary storage accounts

* File share app (Dropbox/public folder type thing, or Pastebin/text share)

* Friends app (add/remove w QR codes)

* Hospitality Preference (allergies, dietary restrictions, etc.)

* News app, e.g., RSS aggregator

* Pastebin clone

* Photo Album app (comments + likes + notifications)

* Presence app (i.e., online/offline indicator) (possibly combine with Check-in/Location app)

* Presentations app, e.g., https://github.com/tmcw/big/blob/gh-pages/docs/user-guide.md
