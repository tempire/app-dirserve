## Simple directory listing over HTTP

- Inspired by 'python -m SimpleHTTPServer'
- Uses Perl & Mojolicious for maximum pwn
- Only one pre-requisite:
  - Mojolicious

## Usage

	usage: dirserve [OPTIONS]
	
	These options are available:
	  --directory    Directory to serve.  Defaults to current directory.
	  --index-page   Page to show by default.  Defaults to directory listing.
	  --port         Port to serve on.  Defaults to 3000.
	  --with-dots    Allow navigating to parent directories via '..'.
