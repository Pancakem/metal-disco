# RACECARS

This one was fairly simple. 

When you first run the program
```
./racecars
	Gimme what I want!
```

From the assembly dump, I realized the program checks for 47, ascii
code for '/', in the string in argv[0]. It does this by looking at the
character before the last character. In order to achieve this and get
the flag, rename the program to a single character name.

Like so
`mv racecars r`

Now when you run the program, you get the flag
```
./r
	That's exactly what I wanted!
```
