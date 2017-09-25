<h1 align="center">Developing Desktop Apps with Electron & Ember.js</h1>

Speaker: [Aidan Nulman](https://twitter.com/anulman)

* 🔌: corber.io
    * Possibly `electron` alternative

Electron
* Simultaneous control of node.js & chromium runtimes
* Pre-package with js wrappers for several common host OS APIs
* Disclaimers:
    * "serves" via file system paths should not start with `/`
    * architecture should minimize platform-specific code
    * Be careful! You have full privileges of host OS
        * e.g. remote code execution is dangerous

Electron-Forge
* https://electronforge.io/
* Using `electron` w/ exisiting React/Angular apps

`render-vendor` (Added to desktop app for UX improvements)
* http://render-vendor.com/
* `render-vendor` is the fastest way to render HTML documents to PDFs
* From 2-3s to instantaneous feedback from html => pdf => printer

