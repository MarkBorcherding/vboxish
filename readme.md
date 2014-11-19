# VBoxish (Simple VBox CLI)

`vboxish` is simple vbox CLI.

## Usage

### Listing VMs

    vboxish list

### Snapshotting a VM

When snapshotting you can pass part of the VM name.

    vboxish snapshot
    $ ./vboxish snapshot va snapshot_name
    ==> Snapshotting some_vagrant
    0%...10%...20%...30%...40%...50%...60%...70%...80%...90%...100%
    ==> Created snapshot snapshot_name

### Restoring a snapshot

Similar when restoring, can pass part of a vm name

    $ ./vboxish restore va snapshot_name
    ==> Powering off some_vagrant
    ==> Restoring snapshot snapshot_name
    Restoring snapshot f9f1a6e3-f113-46ec-913f-dd231b7ed794
    0%...10%...20%...30%...40%...50%...60%...70%...80%...90%...100%
    ==> Powering on some_vagrant
    Waiting for VM "some_vagrant" to power on...
    VM "some_vagrant" has been successfully started.


## License
The MIT License (MIT)

Copyright (c) 2014 Mark Borcherding

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


