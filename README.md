# Using the SLSC Caps Explorer

## Installing the JSONtext Library

The SLSC Caps Explorer requires the JSONtext library. You can install the [JSONtext library](https://lavag.org/files/file/294-jsontext/?do=download&csrfKey=562fb0ed657f09b529d2c8ee73b802b4) and add the `JDP Science Common Utilities` folder to your project or the `<vi.lib>/JDP Science` directory.

## Opening a JSON File

Open **Mainpage.vi** and click the **Open** button to open a JSON file. The file is located at `C:\ProgramData\National Instruments\nislsc\capabilities` or `<Explorer project>/Caps/slscModulePrototype_Caps.json`.

## Modifying a Property

To modify a property, You can select a property, modify the value, and click the **Confirm** button.

## Adding a Property

To add a new property, you must select an existing property to indicate the physical channels or the property index for the new property. Enter `new property name/value/bitfield...` and click the **OK** button.

## Removing a Property

To delete a property, you can select a property and click the **Remove** button.

## Saving Changes

Click the **Save** button to save the changes to a new JSON Caps file. 
