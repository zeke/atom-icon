# Atom Logo

[Atom](http://atom.io/) is a hackable text editor for the 21st Century. It's
the greatest thing since sliced bread, but its logo perpetuates a stereotypical
misrepresentation of atomic structure:

![](atom-old.png)

Electrons don't travel in elliptical orbits around a nucleus, as depicted above.
They move wildly and unpredictably in what's called an [orbital](http://en.wikipedia.org/wiki/Atomic_orbital#Orbital_names),
with a high probability of being close to the nucleus at any give time.

My new logo attempts to more accurately represent an atom:

![](atom.png)

Paradoxially, atoms themselves are "smaller" than light, so they literally cannot
be observed. As such, this is an absurdist exercise. Forgive me.

For more info about atoms (the particle, not the editor), I recommend watching
[Introduction to the atom](https://www.khanacademy.org/science/chemistry/introduction-to-the-atom/v/introduction-to-the-atom), a fascinating
and digestible video from Khan Academy.

## Use It

https://github.com/zeke/atom-icon

## Build It

OS X uses ICNS files. Use `sips` to convert the PNG:

```
sips -s format icns atom.png --out atom.icns
```
