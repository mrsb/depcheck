depcheck
========

Depcheck was hastily hacked together, rehacked, changed, tweaked and expanded in a horendously messy way.

It was an urgent requirement of the Mageia QA team as a workaround to The Bug Whose Name We Dare Not Mention (TBWNWDNM)

- https://bugs.mageia.org/show_bug.cgi?id=2317

depcheck is no longer required and was never tidied up but can still be useful for listing package versions in
the various medias.

eg.

	$ depcheck thunderbird
	Mageia release 4 (Official) for x86_64
	------------------
	Core 32bit Release
	thunderbird-24.2.0-1.mga4
	------------------
	Core 32bit Updates
	thunderbird-24.3.0-1.mga4
	thunderbird-24.4.0-1.mga4
	thunderbird-24.5.0-1.mga4
	thunderbird-24.6.0-1.mga4
	thunderbird-24.7.0-1.mga4
	------------------
	Core Release
	thunderbird-24.2.0-1.mga4
	------------------
	Core Updates
	thunderbird-24.3.0-1.mga4
	thunderbird-24.4.0-1.mga4
	thunderbird-24.5.0-1.mga4
	thunderbird-24.6.0-1.mga4
	thunderbird-24.7.0-1.mga4
	------------------

dep is just a shortcut for depcheck with common options and dodep uses dep but takes a list of packages from a file
which was useful for larger updates. All now defunct. 
