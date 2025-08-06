## How to use sg_api.py
This is the documentation for the sg_api.py API wrapper.

This package contains only 2 functions, both of which return json strings with content dependent on what arguments you add.

### Functions
`characters()`: prints JSON about Squid Game characters

`episodes()`: prints JSON about Squid Game episodes

### How to use
First, import the package and the functions that you need:
```
import sg_api_py
from sg_api_py import characters, episodes
```
This is the structure of the two functions:
```
characters(2, 100, "title")
# function, season, filename, field (optional)
```
As shown above, you only need one line to either get a list of key:value pairs about a Squid Game character or specify what you want with the (optional) field.
### Fields
These are the fields you can choose to use for its respective function.
#### Characters
`title`: Character title

`name`: Character's real name (if available)

`aliases`: Other names for the character

`family`: Character's related family

`relations`: Character's relations

`occupation`: Character's occupation

`born`: Character's date of birth

`fate`: Characters death info

`appearances`: First/last appearances

#### Episodes
`title`: Episode title

`episode_details`: Minor episode details

`episode_guide`: Previous/next episode

