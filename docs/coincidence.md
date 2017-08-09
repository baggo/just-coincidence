
# Coincidence

All coincidences have the fields:

 - `version`: The version of the data.  So we can make incompatible changes
 - `description`: An abstract description what the coincidence is

They may also optionally have the fields:

 - `evidence`: An array of [evidence](./evidence) to improve your score inside algorithms

## RepetitiveCoincidence

```js
interface RepetitiveCoincidence extends Coincidence {


}
```
