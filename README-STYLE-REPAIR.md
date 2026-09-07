# Style repair

Your page is unstyled because the previous macOS folder replacement replaced the
entire `static` directory with only `static/uploads`, removing HugoBricks'
`static/css` files.

This repair restores the CSS from the HugoBricks source you originally uploaded,
keeps your portrait, and restores the original HugoBricks data files while
preserving the corrected favicon settings.

IMPORTANT: copy the CONTENTS of `static` and `data` into the corresponding
folders in your existing HugoBricks project. Choose MERGE if Finder offers it;
do not delete the existing project folders.

Then run:

    hugo server
