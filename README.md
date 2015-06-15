# ircd-kaffe [![Build Status](http://gitbots.co.vu/api/badge/github.com/clinr/ircd-kaffe/status.svg?branch=master)](http://gitbots.co.vu/github.com/clinr/ircd-kaffe)

ircd-kaffe is a fork of Elemental-IRCd to suit the needs of KaffeNet, which
is an IRC network at `irc.kaffenet.tk`. The official channel, on that network, is
`#kaffenet-ircd`. Please direct all ircd-kaffe support questions there.

# Elemental-IRCd

**Elemental-IRCd** is a high performance, lightweight, and scalable
IRC daemon. It is a fork of the now-defunct ShadowIRCD and seeks to continue in
the direction ShadowIRCD was headed.

## Supported Platforms

All modern \*NIX systems should work. You need the equivalent of the following
Debian packages:

 - `libssl-dev`
 - `flex`
 - `bison`
 - `build-essential`

```
Cassy | If you put something on a platform which cannot support it
      | it may tip and fall and become broken. Simple physics.
```

Read the included documentation for detailed compilation and install
directions.

## Support

The official channel for Elemental-IRCd is `#elemental-ircd` on
`irc.yolo-swag.com`. Anyone with push access to the repository will have halfop
(`+h`, `%`) or higher.

Atheme and Anope (1.8 and 2.0) modules are included in the source tree of
Elemental-IRCd. For most cases the default `protocol/elemental-ircd` module in
Atheme should be fine, but this version will always be more up-to-date.

To report bugs, please use the GitHub issue tracker.
