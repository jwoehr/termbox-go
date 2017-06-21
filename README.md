*This fine piece of open source software is forked into github.com/jwoehr*
*solely so that we can select further changes which might affect*
*github.com/jwoehr/goublu. Copious thanks to the original author(s).*
*Jack Woehr 2017-06-21*

## Termbox
Termbox is a library that provides a minimalistic API which allows the programmer to write text-based user interfaces. The library is crossplatform and has both terminal-based implementations on *nix operating systems and a winapi console based implementation for windows operating systems. The basic idea is an abstraction of the greatest common subset of features available on all major terminals and other terminal-like APIs in a minimalistic fashion. Small API means it is easy to implement, test, maintain and learn it, that's what makes the termbox a distinct library in its area.

### Installation
Install and update this go package with `go get -u github.com/jwoehr/termbox-go`

### Examples
For examples of what can be done take a look at demos in the _demos directory. You can try them with go run: `go run _demos/keyboard.go`
