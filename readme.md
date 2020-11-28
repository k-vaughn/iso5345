# Registry of Intelligent Transport System Items (RITSI) - PROTOTYPE
This site is designed as a prototype of a future site that will publish identifier assignments for registered items that are recognized by International Organization for Standardization (ISO) Technical Committee (TC) 204, _Intelligent transport systems_ (ITS). The contents of the current site are intended to demonstrate how this site will work. **Items and identifier values shown on this site are likely to contain a mixture of real and imaginary assignments and these values should not be considered normative in any way.**

## Background

Within information exchanges, there is often a need to unambiguously and concisely represent information. One way to achieve this is to define an identifier (e.g., an integer value) that can be used to concisely represent a specific meaning (e.g., the reference to a country, a standard, a protocol). The identifier might be an integer, a hierarchical structure (e.g., an ASN.1 OBJECT IDENTIFIER), a textual name, or any other concise representation (e.g., a two-character country code). 

The mappings of identifeirs to their precise meanings is provided by a list of registered items. A list of registered items is presented as a table with columns representing different attributes of each registered item and each row associating a specific registered item with its assigned identifier and other attributes (e.g. date of registration). 

Separate lists of registered items allow the same code (e.g., an integer value of '1') to be assigned different meanings in different contexts; these separate lists are known as item classes. ISO/TC 204 has identified the need for multiple item classes. Whenever a standard provides a field that can be used to reference a registered item, it must identify the item class (i.e., the specific list of registered items) to be used when populating the field.

Some lists of registered items are relatively static and are only updated when the text of the standard is updated. However, within ITS, several of these lists need to be updated in a more timely manner. ISO/TC 204 developed ISO 5345 to define the process for maintaining such lists. This website provides [a prototype of] the official lists of registered items that are maintained per ISO 5345.

## List maintenance

This site is maintained according to the procedures defined in ISO 5345, _Intelligent transport systems – Identifiers – Processes_. This standard specifies that requests to modify any list of registered items within ITS is received by the ISO/TC 204 maintenance agency secretariat and forwarded to the designated maintenance agency for review. The maintenance agency develops a recommendation, which is then typically reviewed and approved by the full ISO/TC 204 membership. If any objections are made to the action proposed by the maintenance agency, the full membershop of ISO/TC 204 will discuss the request at their next plenary meeting and make a final decision. 

The maintenance agency consists of national experts from ISO/TC 204; the current maintenance agency secretariat is listed on teh [ISO maintenance agency website](https://www.iso.org/maintenance_agencies.html#5345). Parties who wish to request any change to the list of registered items may contact the maintenance agency secretariat listed for ISO 5345.

## Item classes

### General
This website includes a number of distinct registered item listings; each listing is known as an item class. The following clauses provide the formal definition for each item class and a link to a page that lists the registered items for that item class. 

The definition of each item class includes the identification of the attribuites that are associated with each item class. The attributes referenced within these definitions are defined in ISO 5345. Each attribute is marked as mandatory (M), conditional (C), or optional (O). Requests for registering new items within a list must specify the item class and all of the applicable attributes that are marked with an asterisk; the attributes not marked with an asterisk are provided by the maintenance agency.

The following attributes are associated with registered items for all item classes.

- ID (M)
- Name (*M)
- Description (*M)
- Assignee (*M)
- Registration Date (M)
- State (M)

### [ITS-AID](its-aid.md)

ITS application identifier (ITS-AID)

An ITS-AID provides a globally unique identifier for an ITS application specification. Registered items are defined per the rules contained in the following table. The list of ITS-AID registered items is provided [here](its-aid.md). 

<table style="width: 1000px">
	<caption>ITS-AID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
  	<td>
  		<table>
  			<tr><td>Architecture reference (*O)</td></tr>
  			<tr><td>p-encoding (M)</td></tr>
			<tr><td>Specification (*M, <abbr title="Public access is conditional per Policy attribute">Pub/Priv</abbr>)</td></tr>
  			<tr><td>Uses (*M)</td></tr>
			<tr><td>URL (C, <abbr title="Required for public specifications">Pub</abbr>)</td></tr>
  		</table>
  	</td>
  	<td>Policies for ITS-AIDs</td>
  	<td>INTEGER</td>
  	<td>
  		<table>
  		<tr><td>ETSI 103 097</td></tr>
  		<tr><td>ETSI 302 636-5-1</td></tr>
  		<tr><td>IEEE 1609.2</td></tr>
  		<tr><td>IEEE 1609.3</td></tr>
  		<tr><td>ISO 16460</td></tr>
  		<tr><td>EN ISO 17423 </td></tr>
  		<tr><td>CEN ISO 17429</td></tr>
  		<tr><td>ISO 21218</td></tr>
  		<tr><td>ISO 22418</td></tr>
  		<tr><td>ISO 24102-1</td></tr>
  		<tr><td>ISO 24102-2</td></tr>
  		<tr><td>ISO 29281-1</td></tr>
  		</table>
  	</td>
  </tr>
</table>

### ITS-ATT

blah, blah, blah 

<table style="width: 1000px">
	<caption>ITS-ATT Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Specification (M, <abbr title="Public access is required">Pub</abbr>)</td></tr>
			<tr><td>URL (M)</td></tr>
		</table>
	</td>
    <td>National Body Policy</td>
    <td>INTEGER (0..255)</td>
    <td>
		<table>
		<tr><td>ISO 16460</td></tr>
		<tr><td>ISO 21218</td></tr>
		<tr><td>ISO 22418</td></tr>
		<tr><td>ISO 24102-1</td></tr>
		<tr><td>ISO 24102-3</td></tr>
		<tr><td>ISO 24102-4</td></tr>
		<tr><td>ISO 24102-6</td></tr>
		</table>
	</td>
  </tr>
</table>




