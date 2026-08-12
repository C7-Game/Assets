# Contributing assets to OpenCiv3

This repository houses media assets used in [OpenCiv3](https://github.com/C7-Game/OpenCiv3/), a free open source game. Since these assets are of mixed origins and ownership, there is no singular license on the repository as a whole as explained in the [README](README.md). We welcome submissions or recommendations of both newly created and found assets that are usable in the game. See [the wiki](https://github.com/C7-Game/Assets/wiki/Asset-Guidelines) for more detailed guidance on the selection and creation of assets. 

## Selection of assets

As OpenCiv3 originated out of and for the Civ3 modding community, those existing assets are generally preferred when there is something of sufficient quality and relevance. The [Civilization III Downloads Database](https://forums.civfanatics.com/resources/categories/civilization-iii-downloads.13/) at Civfanatics is the go-to source, along with the associated subforums. Lacking that, original or found open-source compatible works are welcomed, with temporary placeholders as a last resort.

In any case, OpenCiv3 must be permitted to freely use, redistribute, or modify any provided assets, regardless of the original source. This means that no content derived from non-free works such as commercial games can be accepted.

New assets should not be submitted well in advance of when they are usable by the game, nor in speculation of alternative uses. We will integrate assets as the game is able to use them. If you have a proposal for a not yet available feature that would use new assets, coordinate with the development team first. We also maintain a [wiki page](https://github.com/C7-Game/pedia/wiki/Other-graphics) where you can suggest existing assets that have not yet been added.

## Creating original assets

Unless otherwise specified by the time of acceptance, contributors agree to provide their own work under the terms of [CC-BY-NC-SA-4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). This means anyone else may distribute, remix, adapt, and build upon the material in any medium or format for noncommercial purposes only, provided that attribution is given to the creator, and they license any modified material under the same or a compatible license. Creators are of course free to also separately publish the same work under any other terms or license they wish.

Generative AI output is not specifically disallowed, when acceptable alternatives are not readily available, but it is discouraged and will be considered a placeholder.

If opting to create original assets, creators should coordinate with the development team before doing significant work to agree on general characteristics, formats, etc. There is no need for original assets to conform to Civ3 formats and standards; see [the wiki](https://github.com/C7-Game/Assets/wiki/Asset-Guidelines) for preferred formats and artistic guidelines. It is also strongly recommended that creators provide raw working files used to create the assets, to allow for easier customization.

A list of specific placeholder assets that should be prioritized for replacement is maintained in [placeholders.yml](placeholders.yml). New contributors are encouraged to start there.

## Submitting assets for inclusion

When contributing or updating assets, whether your own or something you found, [open a PR](https://docs.github.com/en/pull-requests/how-tos/create-pull-requests/creating-a-pull-request) and complete its [checklist of terms](.github/pull_request_template.md) or call out any exceptions before submitting it. Be sure to include or update the credits in the README file in each directory where you are adding or replacing files, to cite the source of any assets that you did not create yourself.

Credits format for README.md (note each line ends with two spaces for line breaks):
```
"{name of asset}" by {asset creator}  
{list filenames, if it is not the whole directory}  
{URL of download page}  
{specify any known license or other terms by the creator}  
{indicate any modifications to the original files}  
```
