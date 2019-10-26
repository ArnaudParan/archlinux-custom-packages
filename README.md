if you have access to a debian repository like

```

http://test.repository.com identifier main

```

to get access to the sums and the paths of the packages, you should curl

```

http://test.repository.com/dists/identifier/Release

```

```

http://test.repository.com/dists/identifier/InRelease

```

And for the key

```

http://test.repository.com/dists/identifier/Release.gpg

```

With that you get where the Packages files are, those will tell you where the binaries are. You will also get access to the Release and Sources files
