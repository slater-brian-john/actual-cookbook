# actual-cookbook
Markdown recipe book, for personal use but you are welcome to see the weird things I eat

## Structure

This cookbook is organized into chapters, with each recipe in its own directory. Each recipe contains:
- **manifest.json**: Recipe metadata including date and file locations
- **ingredients.md**: List of ingredients needed
- **mise-en-place.md**: Preparation steps and equipment needed
- **recipe.md**: Cooking instructions and serving suggestions

## Chapters

### [Blacksheep Takeover](recipes/blacksheep-takeover/recipe.md)
A delicious recipe that takes over your taste buds.
- **Date**: 2025-10-20
- **Files**: [Manifest](recipes/blacksheep-takeover/manifest.json) | [Ingredients](recipes/blacksheep-takeover/ingredients.md) | [Mise en Place](recipes/blacksheep-takeover/mise-en-place.md) | [Recipe](recipes/blacksheep-takeover/recipe.md)

## Manifest Format

Each recipe includes a `manifest.json` file with the following structure:

```json
{
  "title": "Recipe Name",
  "date": "YYYY-MM-DD",
  "files": {
    "ingredients": "ingredients.md",
    "mise_en_place": "mise-en-place.md",
    "recipe": "recipe.md"
  }
}
```

The manifest always includes:
- **date**: The date when the recipe was added to the cookbook
- **files**: File locations for ingredients list, mise en place, and recipe markdown
