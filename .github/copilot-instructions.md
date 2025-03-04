Code should match the style of the file it's in.

Changes should be minimal to resolve a problem in a clean way.

User-visible changes to behavior should be considered carefully before committing. They should always be flagged.

Large changes should always include test changes.

When considering how output should look, solicit advice from @baronfel.

When using strings, prefer having them localized in .resx files

Do not modify .xlf files, instead prompt the user to do so by running `/t:UpdateXlf` on MSBuild

Avoid skipping tests unless specifying an issue within this repo as a reason. 