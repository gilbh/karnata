Pipeline for reading machine of Kannada texts in karnata.org
1.	Mackenzie uploads typed Kannada files to `/raw`
2.	Yash runs script to convert from `/raw` to `/tei`
3.	Mackenzie performs QC and adds metadata to the generates files in `/tei`
4.	Yash runs website script to read reviewed files in `/tei` to process into website database

When texts need to be corrected, Yash notifies Mackenzie, who updates the GH `/raw` and `/tei` files accordingly.
