 - <b id="#/properties/namespace">namespace</b>
	 - **Description:** URI identifier for the source of the animal identifier
	 - **Type:** `string`
 - <b id="#/properties/identifier">identifier</b>
	 - **Description:** a unique value for the given identifier for the animal
	 - **Type:** `string`
 - <b id="#/properties/state">state</b>
	 - **Description:** State of the animalId (birth, current, historic)
	 - **Type:** `string`
 - <b id="#/properties/validFrom">validFrom</b>
	 - **Description:** Start date of the Identifer
	 - **Type:** `string`
 - <b id="#/properties/validThrough">validThrough</b>
	 - **Description:** End date of the Identifier
	 - **Type:** `string`
 - <b id="#/properties/identifierType">identifierType</b>
	 - **Description:** Type of animal identifer. Each animal identifier SHOULD  also specify the type of identifier (Official, Management, Electronic, Tattoo, Brand, Calculated) so that a receiving system which is unable to interpret namespaces may use a generic method to interpret the identifier.
	 - **Type:** `string`

_Generated with [json-schema-md-doc](https://brianwendt.github.io/json-schema-md-doc/)_