tmmount
=======

Are you using `netatalk` to run a Time Machine server on your Linux server?
`tmmount` provides an easy mechanism for mounting and unmounting Time Machine
sparse bundles in Linux.

This project contains two scripts:

* `tmmount` - mount a Time Machine sparse bundle for read-only browsing. It is
  a layer on top of [sparsebundlefs] and [tmfs]
* `tmumount` - unmount a Time Machine sparse bundle mounted by `tmmount`

Credits
=======

* [sparsebundlefs]
* [tmfs]

  [sparsebundlefs] https://github.com/torarnv/sparsebundlefs
  [tmfs] https://github.com/abique/tmfs
