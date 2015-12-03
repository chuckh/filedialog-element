filedialog-element
==================

**filedialog-element** is a Polymer based web component button (version >= 1.0) that when clicked, provides a file dialog for opening and reading local files as text, binary string, data url, or array buffer from the browser.

The element has 4 assignable properties:

**buttonText** -- a string to label the button

**format** -- specifies the reading format.  Acceptable values are 'text', 'binarystring', 'url', 'array' (default: 'text')

**just_filename** -- a boolean which if `true` the component will fire an event, sending only the file name selected and not read/send the file contents (default: `false`)

**show_progress** -- a boolean which controls display of a progress bar during the reading (default: `false`)

----------

**filedialog-element** fires the *filedialog-result* event with the following object:

{fileResult: *the file's contents or data url*, fileName: *the file name selected*, fileStatus: *OK or an error message*}

When **just_filename** is `true` then the event *filedialog-filename* is fired with the following object: 

{fileName: *the file name selected*}

----------

The Bower file *bower.json* file is provided for installing **filedialog-element's** two dependencies **polymer** and **progress-element**.
