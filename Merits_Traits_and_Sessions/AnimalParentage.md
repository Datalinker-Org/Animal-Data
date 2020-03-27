 - <b id="#/properties/parentIdentifiers">parentIdentifiers</b>
	 - **Description:** The parentage properties of an animal can be comprised of a set of elements, including the birth dam, genetic dam, rearing dam, and sireId as stipulated in parentType
	 - **Type:** `array`
	 - <b id="animalidentifieranimalidentifier.md">Link to schema: [AnimalIdentifier](AnimalIdentifier.md)</b>
 - <b id="#/properties/parentMethod">parentMethod</b>
	 - **Description:** Documents how parentage was assessed: - Observed (e.g. Dam observed giving birth to progeny), Associated (e.g. Dam seen feeding progeny), Derived (e.g. Sire derived from mating records), DNA (the result of a DNA parentage test)
	 - **Type:** `string`
 - <b id="#/properties/parentsAge">parentsAge</b>
	 - **Description:** Calculated age of parent in years at the time animal was born. May be known as 'ageOfDam' in some systems
	 - **Type:** `string`
 - <b id="#/properties/parentType">parentType</b>
	 - **Description:** This specifies the type of parentage that is claimed: Dam (natural dam), ET Recipient Dam, ET Donor (Genetic) Dam, Rearing Dam (reared, but did not give birth to the progeny), Sire (multiple sire records may be recorded, each with its own DNA probability if DNA testing indicates multiple matches) Excluded Sire (unable to confirm the sire, but definitely not this animal)
	 - **Type:** `string`

_Generated with [json-schema-md-doc](https://brianwendt.github.io/json-schema-md-doc/)_