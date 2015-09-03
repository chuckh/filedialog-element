filedialog-element
==================

**filedialog-element** is a Polymer based web component (version >= 1.0) to provide a file dialog for opening and reading local text or image files from the browser.

The element has four assignable properties:

**buttonText** -- a string to label the button

**format** -- specifies a 'text' or 'image' read (default: 'text')

**just_filename** -- a boolean which if `true` will send only the file name selected and not read the text or image data (default: `false`)

**show_progress** -- a boolean which controls display of a progress bar during the reading (default: `false`)

----------

**filedialog-element** fires the *filedialog-result* event with the following object:

	{fileResult: *the text or url source of the image*, fileName: *the file name*, fileStatus: *OK or an error message*}

For **format** equal to 'image' the *fileResult* would typically be the *src* property for an html image element.

----------

The Bower file *bower.json* file is provided for installing **filedialog-element's** two dependencies **polymer** and **progress-element**.
