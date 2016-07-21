### flow-stats

Check total Flow coverage for the project.

#### Install

##### Global

- `npm install flow-stats -g`

##### Local

- `npm install flow-stats --save-dev`
- Add [run script](https://docs.npmjs.com/misc/scripts): `"flow-stats": "flow-stats --glob 'src/components/**.js'"`
- Run with `npm run flow-stats`

#### Example

```bash
$ flow-stats --glob 'src/components/**.js'
```

```bash
Matching src/components/**.js, found 44 file(s):

97.83 src/components/List.js
96.89 src/components/EditableTitle.js
86.77 src/components/Color.js
75.65 src/components/Popup.js
50.22 src/components/Selection.js
```
