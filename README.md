# Changes
Fixed go module imports in order to enable a simple `go get github.com/jon-ryan/go-zebra-scanner/devices` and `go get github.com/jon-ryan/go-zebra-scanner/snapi`


# Zebra/Symbol/Motorola Barcode Scanner Daemon

This project provides client software for barcode scanners made by
Zebra (or their earlier incarnations Symbol or Motorola).

`zebrascand` is a Websocket server which exposes connected barcode
scanners to web applications.

The `snapi` package is a Go interface to Zebra's proprietary SNAPI
protocol.


## Copying

Copyright 2018 Sam Hanes

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
