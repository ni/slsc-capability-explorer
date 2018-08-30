1. At first, you need to install JSONtext library (from https://lavag.org/files/file/294-jsontext/?do=download&csrfKey=562fb0ed657f09b529d2c8ee73b802b4 or in VI Package Manager).
   And click the checkbox of "JDP Science Common Utilities" when installing the JOSNtext library.
   Please note that this library requires LabVIEW 2017 and later, so this Offline Caps Explorer tool basing on the library can only be used in LabVIEW 2017 and beyond.

2. Open Mainpage.vi, and you can click "Open" button to open a JSON file. 
    The default path for capabilities files is located at "C:\ProgramData\National Instruments\nislsc\capabilities".

3. When you want to modify a property, you can select it by one click, modify its value and click confirm button.

4. When you want to add a new property, firstly you need to select a property where you want to add the new property, then the Explorer knows which physical channels or the property index you want to add after. 
    Enter the property name/value/bitfield... in the prompt window and click Ok button.

5. Delete a property by selecting it and clicking remove button.

6. Save the changes to a new JSON Caps file by clicking save button. 