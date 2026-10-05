# interactor-ml-fire-juan-mosaic

A command-line sample that restyles a PNG with a mosaic style-transfer network in ONNX format, on the GPU or the CPU.

## What it is for

It reads an image, runs the bundled style-transfer model on it through an ONNX runtime's C API, and writes the restyled image. The runtime libraries and headers are checked in prebuilt, so it runs only on the desktop platform they were built for.

## Build and run

```sh
cmake -B build
cmake --build build
mosiac.bat
```

`mosiac.bat` runs the executable on the sample image.

## Licence

MIT; see `LICENSE`. The sample source keeps its upstream MIT notice.
