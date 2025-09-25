# Warcraft III Rampage Maps

Very WIP maps where you direct a giant monster to crush and devour (almost) everything. Press an arrow key once to move, press the same direction again to stop.

Built off version 1.26.0.6401 of the classic edition.

The sound resources and Rampage Objects file are not necessary to play. Maps are standalone.

If you're curious to view these in the editor, be aware of the following hex edit:

Inside ``worldedit.exe`` at ``0x3BA2D0``, replace ``0x77`` with ``0x00``.

Doing this makes custom files import to the map's root, which is how most custom models expect their textures. The vanilla game is fine with this, but unmodded editors will goof up custom texture paths due to the default import location being different.
