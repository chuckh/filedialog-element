filedialog-element
==================

**filedialog-element** is a Polymer based web component (version >= 1.0) to provide a file dialog for opening and reading local text or binary files from the browser.

The element has two attribute:

**buttonText** -- a string to label the button

**format** -- specifies a 'text' or 'binary' read (default = 'text')

----------

**filedialog-element** fires the *filedialog-data* event with the following object:

{fileData: *the text or binary data*, fileName: *the file name*, fileStatus: *OK or Error*}

If **format** is not assigned then the event returns just a file name with *fileData* as null.

----------

The Bower file *bower.json* file is provided for installing **filedialog-element's** one dependency **polymer**.
