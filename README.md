# SLSC Offline Capability Explorer

## Overview

The SLSC Offline Capability Explorer is an open-source LabVIEW application that can add, remove, and modify the properties of a JSON capabilities file.

## Software Requirement
- LabVIEW 2017 or later
- JSONtext library

## Using the SLSC Offline Capability Explorer

### Installing the JSONtext Library

The SLSC Offline Capability Explorer requires the JSONtext library. Refer to the [JSONtext by JDP Science package](http://sine.ni.com/nips/cds/view/p/lang/en/nid/216651) to download and install the JSONtext library. NI recommends that you download and install the JSONtext library through VIPM.

__Note:__ The JSONtext library supports LabVIEW 2017 or later.

### Opening a Capabilities File

Open **Mainpage.vi** and click the **Open** button to open a capabilities file. The default location of capabilities files is `C:\ProgramData\National Instruments\nislsc\capabilities\`.

### Modifying a Property

To modify a property, select a property, modify the value, and click the **Confirm** button.

### Adding a Property

To add a new property, select an existing property to indicate the physical channels or the property index for the new property. Click the **Add** button to open the **PropertyAdd.vi**. Specify information about the new property and click the **OK** button.

### Removing a Property

To remove a property, select a property and click the **Remove** button.

### Saving Changes

Click the **Save** button to save the changes to a new capabilities file. 
