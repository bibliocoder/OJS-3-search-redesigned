# OJS 3 Search Redesigned
Improvement of the OJS 3 search by redesigning the search bar and results page.

## Features
- The search bar now consists of a search icon (expandable) and an "Advanced Search" button next to it
- The search results page does only show a "No Results" message when a search query was sent

![Screenshot Demo OJS_3_search_redesigned](https://user-images.githubusercontent.com/71929510/94372569-2279cc00-00ff-11eb-82b6-592234113f0e.gif)

This modification is solely based on adding template and CSS code.

## Installation
1. Copy modified **searchForm_simple.tpl** to `/templates/frontend/components/`

2. Copy modified **search.tpl** to `/templates/frontend/pages/`

3. Apply custom CSS file **OJS_3_search_redesigned.css** to your journal (Settings > Website > Appearance > Advanced > Journal style sheet > Upload .css file > Save)

Tested with latest OJS 3.2.1-1, but these changes should also be applicable to OJS 3.x versions prior than that.

## License
This software is released under the the [GNU General Public License](LICENSE).

See the file [LICENSE](LICENSE) included with this distribution for the terms
of this license.
