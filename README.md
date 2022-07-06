# svelte attribute bottleneck

This svelte app has a svg element with a very big attribute value.

Because of this attribute, the internal Svelte parser uses a tremendous amount of time just generating the code for running the application.