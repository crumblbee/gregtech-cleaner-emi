A resourcepack for Minecraft 1.20.1 that improves the integration between [GregTech](https://github.com/GregTechCEu/GregTech-Modern) and [EMI](https://github.com/emilyploszaj/emi). This was created for use with [Monifactory](https://github.com/emilyploszaj/emi/wiki/Hiding-and-Adding-Index-Stacks), but should mostly work with other GregTech-Modern packs as well.

- You can now search "EBF" or "LCR" in EMI without spelling out the acronyms.
- A lot of recipes that are useless post-LV are hidden, to make the recipe overview less bloated. This includes things like the "hammer two ingots into one plate in the crafting grid" recipes, or "mold 8 ingots into 1 gear in an alloy smelter", or "craft four small dusts into one dust". The recipes still work. You can show them again by extracting the resourcepack and removing the `assets/emi/recipe/filters/hide-post-lv.json` file or renaming its file extension.
- A lot of recipes and items that never had any use to begin with are now hidden. This includes topaz plates, GT cocoa dust, and GT stone gears. **This is specific to the 0.13.8 version of the [Monifactory](https://github.com/emilyploszaj/emi/wiki/Hiding-and-Adding-Index-Stacks) modpack**.

This was made possible by the frankly fantastic [EMI wiki](https://github.com/emilyploszaj/emi/wiki).

***

This project and its assets are MIT licensed.

The versioning system is undefined for now, because I don't know how to suitably define an API for this.
