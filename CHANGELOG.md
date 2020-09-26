## Changelog
- 2.1.3
    + Fix null ref exception when using array of TypedArray.
- 2.1.2
    + Fix module resolution with commonjs and esmodule.
- 2.1.1
    + Derializer method `BinarySerializer.Deserialize(dataBuffer:Uint8Array)` now support `Uint8Array|ArrayBuffer` for parameter `databuffer`
    + Change main script to es module at `package.json`
- 2.1.0
    + Change output BufferType from `ArrayBuffer` to `Uint8Array`.
    + Support `DataType.TypedArray` for `Uint8Array | Uint16Array | Uint32Array | Int32Array | Int16Array | Int8Array | Float32Array | Float64Array`
- 2.0.0
    + Add DataType `map<string,T>`.
    + Add `UVariant32` and `Variant32` for variant encoding/decoding.
    + Remove third-party library depdendency for UTF8 text encoding.
    + Add `BinaryBufferDebug` for convinent debug incorrect decorator labeling.
- 1.2.0
    + Add Float16 dataType.
- 1.1.0
    + Optimize performance
    + Fix some bugs
    + Add serialization support for object created by `Object.Create()`
- 1.0.0 
    + First version
