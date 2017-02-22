# set-tab-status-icon

A single function that will change the current page's favicon (displayed in the tab bar) to a simple colored status icon, on demand.

## Install

**npm**
This package is [published on npm](https://www.npmjs.com/package/set-tab-status-icon).

```
> npm install --save get-tab-status-icon
```

Then:

```javascript
import setTabStatusIcon from 'set-tab-status-icon';
setTabStatusIcon('pass');
```

## Usage

```javascript
setTabStatusIcon('not-started'); // Gray icon
setTabStatusIcon('in-progress'); // Blue icon
setTabStatusIcon('pass'); // Green icon
setTabStatusIcon('fail'); // Red icon
setTabStatusIcon('#ff00dd'); // Pass any custom color
```

