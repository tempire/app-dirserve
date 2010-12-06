## Simple directory listing over HTTP

- Inspired by 'python -m SimpleHTTPServer'
- Uses Perl & Mojolicious for maximum pwn
- Only one pre-requisite:
  - Mojolicious

## Install

curl -L cpanmin.us | perl - http://latest.mojolicio.us<br />
curl -O https://github.com/tempire/app-dirserve/raw/master/dirserve<br />
chmod +x dirserve

## Usage

	usage: dirserve [OPTIONS]
	
	These options are available:
	  --directory    Directory to serve.  Defaults to current directory.
	  --index-page   Page to show by default.  Defaults to directory listing.
	  --port         Port to serve on.  Defaults to 3000.
	  --no-dots      No navigating to parent directories via '..'.
	  --help         This message.

## Screenshot
<img src="https://github.com/tempire/app-dirserve/raw/master/screenshot.png" />
