Markdown Server
===============

0. OBJECTIVE

	0. Serve markdown files.

0. INSTALLING

	0. First, install python-markdown dependency.

		>  # apt-get install python-markdown
	
	0. Then run the "install" script.

		>  # ./install.sh

0. USING

	0. Run the markdown server in a directory that contains markdown
	documents.

		> $ mdserver
	
	0. You can pass the directory as argument.

		> $ mdserver -d /path/to/directory
	
	0. You can define the port.

		> $ mdserver -p 8080
	
		0. The default port is 8000.

	0. After running the server, you can load the main page from your device
	openning the browser in the url.

		> http://localhost:8000/

0. UNINSTALLING

	0. Run the "uninstall" script.

		>  # ./uninstall.sh
