# VSF TR-06-3 Test Registration Repository

This is a test repository for the Payload Format Descriptor to be used in the 
upcoming VSF TR-06-3. This is **not** an official registration for this 
field. An official one will be created in the near future.

This repository has been created to start and demonstrate the process.

## How to add new entries to the table

**Important:** The table is a Microsoft Excel file with formulas. It
must only be edited with Excel. Other tools may break it.

The steps are:

1. Carefully review section 5.1.7 of VSF TR-06-3 for the rules on how
to assign values.
1. Use the drop-down in the **Organization** column to select the
organization from which the document originates.
1. Once you make a selection, the **ID Type** field will be
automatically populated with the correct code. Do not change this
value.
1. Enter the document number as per instructions in TR-06-3 section
5.1.7.
1. If the document has a part or sub-part, enter it in the
**Part/Sub-Part** field. Otherwise, you can leave it blank. For
organizations whose documents have no parts or sub-parts (e.g., RFCs),
this field is ignored.
1. If the document defines multiple packets formats, they are
differentiated by the **ID Flavor** field. The first packet format in
the document gets ID Flavor 0, the next gets 1, and so on.
1. The field **Descriptor (Dec)** will automatically compute the value
of the Packet Format Descriptor in decimal. The same value will be
presented in **Descriptor (Hex)** in 32-bit hexadecimal.
1. Put a textual description of the format in the **Description**
field.
1. Unfortunately, git is unable to merge Excel files. Once you compute
your new entry, send it by e-mail to [the list
maintainers](mailto:reg@rist.tv).
