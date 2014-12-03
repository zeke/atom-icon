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

<p align="center">
  <img alt="Very old Atom icon" src="https://raw.githubusercontent.com/zeke/atom-icon/master/old-icon/1.png" width="100" height="100"> <img alt="Old Atom icon" src="https://raw.githubusercontent.com/zeke/atom-icon/master/old-icon/2.png" width="100" height="100">
</p>
<p align="center">⬇︎</p>
<p align="center">
  <img alt="The new fantastic Atom icon" src="https://raw.githubusercontent.com/zeke/atom-icon/master/atom.png" width="252" height="252">
</p>

## Use It

Open the terminal and execute:

```sh
curl https://github.com/zeke/atom-icon/raw/master/atom.icns \
  --location > /Applications/Atom.app/Contents/Resources/atom.icns

# all this junk clears the OS X icon cache:
sudo find /private/var/folders/ -name com.apple.dock.iconcache -exec rm {} \;
killall Dock
touch /Applications/Atom.app
```

## Build It

OS X uses ICNS files. Use `sips` to convert the PNG:

```
sips -s format icns atom.png --out atom.icns
```
