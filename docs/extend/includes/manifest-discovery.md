These optional properties help users discover and learn about your extension:


|    Property     |                                                                  Description                                                                   |                                                                                                                                                                                                                                                     Notes                                                                                                                                                                                                                                                     |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **description** |                                    *A few sentences describing the extensions. Limited to 200 characters.*                                     |                                                                                                                                                            The description should be your extension's "elevator pitch" - a couple of lines to describe your extension in the Marketplace and make people want to install it. See the example below                                                                                                                                                            |
|    **icons**    |                                               *Dictionary of icons representing the extension.*                                                |                                                                                                                                      Valid keys: `default` (128x128 pixels) of type BMP, GIF, EXIF, JPG, PNG and TIFF). Other keys such as `large` (512x512 pixels) may be supported in the future. The value of each key is the path to the icon file in the extension                                                                                                                                       |
|    **tags**     |                                           *Array of string tags to help users find your extension.*                                            |                                                                                                                                                                                                                          Examples: `agile`, `project management`, `task timer`, etc.                                                                                                                                                                                                                          |
| **screenshots** |                                      *Array of images that could not be included in your \*\*content*\*.                                       |                                                                               Screenshots are more valuable when featured in your **content**, and should be used there to help make a quality market details page for your extension. Use **screenshots** for less important images not featured in your **content**. Each image should be 1366x768 pixels. The `path` of each item is the path to the file in the extension.                                                                                |
|   **content**   |                                      *Dictionary of content files that describe your extension to users.*                                      | *Every* extension should include solid content-it's how you'll show users what your extension can do; make it rich, consumable, and include screenshots where necessary. Include an `overview.md` file as your base content piece. Each file is assumed to be in [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/) format. The `path` of each item is the path to the markdown file in the extension. Valid keys: `details`. Other keys will be supported in the future. |
|    **links**    |                         *Dictionary of links that help users learn more about your extension, get support, and move.*                          |                                                          Valid keys: `getstarted` - first steps, how to setup or use. `learn` - deeper content to help users better understand your extension or service. `license` - end user license agreement. `privacypolicy` - privacy policy for an extension. `support` - get help and support for an extension. The value of each key is an object with a `uri` field, which is the absolute URL of the link                                                          |
| **repository**  |                                *Dictionary of properties describing the source code repository for the extension*                     |                                                                                                                                                                                                       Valid Keys: `type` - Type of repository. Example: *git*. `uri` - Absolute URL of the repository.                                                                                                                                                                                                        |
|   **badges**    | *Array of links to external metadata badges like TravisCI, Appveyor etc from the [approved badges sites]*(/azure/devops/extend/develop/manifest#approvedbadges) |                                                                                                                                                 Valid keys: `href` - Link the user navigates to when clicking the badge. `uri` - The absolute URL of the badge image to be displayed. `description` - Description of the badge, to be displayed on hover.                                                                                                                                                 |
|  **branding**   |                                                   *Dictionary of brand-related properties.*                                                    |                                                                                                                     Valid keys: `color` - primary color of the extension or publisher; can be a hex (#ff00ff), RGB (rgb(100,200,50)), or supported HTML color names (blue). `theme` - complements the color; use *dark* for dark branding colors, or *light* for lighter branding colors.                                                                                                                     |
