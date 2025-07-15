# sg_api.py
An API wrapper for the Squid Game API.

A simple way to extract JSON content from [the Squid Game API](https://github.com/stainlesteel/squid-game-api)
You can either get character content or episode content, and filter out specific key:value pairs.

## Warning

Some JSON files you fetch may have invalid headers leading to an error.
If this occurs, open an issue on the GitHub (above).

## Usage
```python
characters(1, 218, "title")
# Cho Sang-woo
episodes(1, 4, "title")
# Stick to the Team
```

For more info, wait for the documentation or read the source code (100 lines)
## Installation
sg_api.py only requires the `requests` python package which is included with Python3
As such, you can install sg_api.py by:
```
pip3 install sg_api.py
```
## Other Information

Licensed under the MIT License.
### Credits:

BeautifulSoup: for easy HTML extraction
Squid Game Fandom: for providing information about Squid Game
