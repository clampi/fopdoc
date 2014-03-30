fopdoc
======

Documentation for the Fallout 3 and Fallout: New Vegas plugin file formats. These are not well documented anywhere to the best of my knowledge. A good working knowledge of the formats is present within the source code for [TES5Edit](https://code.google.com/p/skyrim-plugin-decoding-project/) though, and I hope to extract that information from the Delphi code and adapt it into documentation that programmers can use to implement plugin read/write code in languages of their choice.

The model for this documentation is the file format documentation for Oblivion and Skyrim on [UESP.net](http://www.uesp.net/wiki/Tes5Mod:Mod_File_Format). My primary motiviation is to make it easier to implement support for Fallout 3 and Fallout: New Vegas in [CBash](https://github.com/WrinklyNinja/CBash).

The documentation will be written in Markdown, and be laid out in a style similar to that used by UESP.net, with each record type getting its own page containing its field tables, and using relative links between pages.

I'm unfamiliar with Delphi, so could do with help reading the TES5Edit source, and I'll welcome anyone who wants to contribute. Just fork the repository, and feel free to open issues on its issue tracker if you want to discuss something. You don't even need to have Git installed, since it's all editable through your browser.

Since FO3 and FNV plugins have a very similar format, it's probably best to complete the FO3 documentation first, and then refer to it for FNV pages where there are no differences. The FO3 definitions in TES5Edit are found [here](https://code.google.com/p/skyrim-plugin-decoding-project/source/browse/TES5Edit/trunk/Delphi+XE/wbDefinitionsFO3.pas).

As for the name, it's frome FallOut Plugin DOCumentation. It's the only pronouncable thing I could come up with. :P