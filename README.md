# Github Usage Rules

## Issue
Github doesn't do enough to help users organize repositories. Public tags, stars and the ability to add repos to "Teams" are the options available but still there is friction in repo discovery, quick understanding and management. 

## Solution
The best solution right now, and just in general as a best practice, is to set and enforce a strict naming convention for repositories. The following is an evolution of options and opinion on the best version. 
## Options
### Dashes✅ or Underscores❌
Following what Microsoft does here. 
### CamelCase✅ or all lowercase❌ 
CamelCase makes it easier to differentiate words. That said, lowercase ends up being more compatible with many tools like Wordpress that seem to be all lowercase for plugins and themes, which means downloaded repos would have to be renamed after download, if in CamelCase, which is annoying and more convenient to just have the repo name be usable as final folder name for the code, if the code is to be embedded somewhere ... so this is a disadvantage of CamelCase but I guess choosing it anyway. 
## Examples

Feels like first is the winner here. I think the aim is to impose ==broad to narrow== categorization in a naming convention (e.g. Broad-Narrower-Narrowest). 

That said, looking at example below, if an org has many plugins across multiple apps then "Plugin" could be the broadest given the org could only have one. 

It seems clear it's not best to run narrowest first, as show in third column ~~but perhaps this all subjective. ~~

| AppName-Function-Detail✅ | Function-App-Detail | Detail-Function-AppName❌ |
| ------------------------ | ------------------- | ------------------------ |
| WP-Plugin-SMTPSend       | Plugin-WP-SMTPSend  | Plugin-WP-SMTPSend       |
| --Tool-LogoGenerator     | Tool--LogoGenerator | LogoGenerator-Tool--     |
| --Helper-Http            | Heleper--Http       | Http-Helper              |

