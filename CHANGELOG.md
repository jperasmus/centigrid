## Changes since 2013-01-01



  Usage: index [options]

  Options:

    -h, --help              output usage information
    -o, --owner <name>      Repository owner name.  If not provided, the "username" option will be used.
    -r, --repo <repo>       Repository name (required).
    -u, --username <name>   Your GitHub username (only required for private repos).
    -p, --password <pass>   Your GitHub password (only required for private repos).
    -f, --file <filename>   Output file.  If the file exists, log will be prepended to it.  Default is to write to stdout.
    -s, --since <iso-date>  Last changelog date.  If the "file" option is used and "since" is not provided, the mtime of the output file will be used.
    -m, --merged            List merged pull requests only.
    -e, --header <header>   Header text.  Default is "Changes since <since>".
    -t, --template <path>   Handlebar template to format data.The default bundled template generates a list of issues in Markdown

