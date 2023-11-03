# url_file_size_monitor
Monitor urls (ftp/http) for changes by polling the file size and notify when they change.

Must have protocol in conf (http:// or ftp://).

If a ftp url requires a username/pass other than anonymous/anonymous, specify it as ftp://username:password@server.com/path/to/file

Based on code from commit_file_monitor for github.

See https://github.com/JRPdata/commit_file_monitor for general setup notes.

Each url has a .conf and it must be in 'conf/urls/'. You can move confs you want to keep but not use by moving them up to conf/

The notable difference is the confs for each url in conf/url only have one line (the url).

