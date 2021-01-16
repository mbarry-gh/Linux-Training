# Wget
needing to download a tarball, or a config file, to a server from a web page. Or within a script I need to know that I can query both local and remote web servers over HTTP(S) to check uptime
or the presence of certain content.

![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ yum install wget <br  />
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ wget http://www.k8slab.in/abc.tar.gz (download tar file) <br />
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ wget -nc http://www.k8slab.in/abc.tar.gz (avoid overwriting a previously downloaded file) <br />
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ wget --output-file logfile_for_errors http://www.k8slab.in/abc.tar.gz (Error written)![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ wget --quiet ftp://ftp.chrisbinnie.tld/largefile.tar.gz (Avoid writing log)
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ wget --input-file=loads_of_links ( Provide a list of URL's)
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ wget -r http://k8slab.in/inner-directory/files (download everything from URL)
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ wget --user=k8slab --password=binnie http://portal.azure.com/logo.jpg (With username & password)
![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) $ wget --user=chris --ask-password http://portal.azure.com/logo.jpg (Asking password)
