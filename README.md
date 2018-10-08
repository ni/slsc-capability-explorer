# Using the SLSC Caps Explorer

## Installing the JSONtext Library

The SLSC Caps Explorer requires the JSONtext library. You can refer to [http://sine.ni.com/nips/cds/view/p/lang/en/nid/216651](http://sine.ni.com/nips/cds/view/p/lang/en/nid/216651) to download and install the JSONtext library. NI recommends that you download and install the JSONtext library through VIPM.

## Opening a JSON File

Open **Mainpage.vi** and click the **Open** button to open a JSON file. The file is located at `C:\ProgramData\National Instruments\nislsc\capabilities` or `<Explorer project>/Caps/slscModulePrototype_Caps.json`.

## Modifying a Property

To modify a property, You can select a property, modify the value, and click the **Confirm** button.

## Adding a Property

To add a new property, select an existing property to indicate the physical channels or the property index for the new property. Click the **Add** button to open the **PropertyAdd.vi**. Specify information about the new property and click the **OK** button.

## Removing a Property

To remove a property, select a property and click the **Remove** button.

## Saving Changes

Click the **Save** button to save the changes to a new JSON Caps file. 
