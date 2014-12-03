# An alternative icon for Atom.app

[Atom](http://atom.io/) is a hackable text editor for the 21st Century. It's
the greatest thing since sliced bread, but its logo perpetuates a stereotypical
misrepresentation of atomic structure.

Electrons don't travel in elliptical orbits around a nucleus: They move wildly
and unpredictably in what's called an [orbital](http://en.wikipedia.org/wiki/Atomic_orbital#Orbital_names),
with a high probability of being close to the nucleus at any give time.

Paradoxially, atoms themselves are "smaller" than light, so they literally cannot
be observed. As such, this could be described as an absurdist exercise. Forgive me.

For more info about atoms (the particle, not the editor), I recommend watching
[Introduction to the atom](https://www.khanacademy.org/science/chemistry/introduction-to-the-atom/v/introduction-to-the-atom)
, a fascinating and newb-friendly video from Khan Academy.

## The Old Ones

![](old-icon/1.png)

![](old-icon/2.png)

## The New One

![](atom.png)

## Use It

Open the terminal and execute:

    curl https://github.com/zeke/atom-icon/raw/master/atom.icns --location > /Applications/Atom.app/Contents/Resources/atom.icns

Mac OS X may cache the old icon, in which case you'll have to restart to see the new one.

## Build It

OS X uses ICNS files. Use `sips` to convert the PNG:

```
sips -s format icns atom.png --out atom.icns
```
