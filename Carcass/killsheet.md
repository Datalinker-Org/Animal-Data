{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "type": "object",
  "properties": {
    "carcass": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-Carcass",
      "@type": "@id",
      "type": "string",
      "format": "uri",
      "dldescription": "Url to get Animal Killsheet data",
      "dltype": "https://www.datalinker.org/context/CarcassData"
    },
    "transactionId": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-TransactionId",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Unique identifier for the transaction in the source system"
    },
    "lineId": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-LineId",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Identifies the transaction line in the source system"
    },
    "dateReceived": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-DateReceived",
      "@type": "xsd:date",
      "type": "string",
      "dldescription": "Date on which the animals were received by the processor"
    },
    "dateProcessed": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-DateProcessed",
      "@type": "xsd:date",
      "type": "string",
      "dldescription": "Date on which the animals were processed"
    },
    "reference": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-Reference",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "A reference code such as an invoice number or purchase order number. Sometimes called 'Line' or 'Reference' or 'Advice Number'"
    },
    "location": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-Location",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Location of the farm from which the animals have been sent"
    },
    "otherPartyContact": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-OtherPartyContact",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Name, short form contact details of supplier/receiver (in this instance Farmer or Producer.). Only intended for reference, not e-commerce"
    },
    "otherPartyId": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-OtherPartyId",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "An identifier of another party within the source system (in this instance the Producer Location)"
    },
    "processorName": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-ProcessorName",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Meat processor ID or name"
    },
    "plantName": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-PlantName",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "ID or name of plant where animal is killed"
    },
    "plantId": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-PlantId",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "URN identifier of Plant Location"
    },
    "quantity": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-Quantity",
      "@type": "xsd:decimal",
      "type": "number",
      "dldescription": "Number of animals handled in the transaction"
    },
    "speciesCommonName": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-SpeciesCommonName",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Common term for species. Enumeration: Cattle, Deer, Goats, Sheep"
    },
    "stockClassName": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-StockClassName",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Text name of the stock class"
    },
    "scheduleName": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-ScheduleName",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Schedule Name"
    },
    "scheduleId": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-ScheduleId",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Schedule Id"
    },
    "mobId": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-MobId",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Unique identifier that represents the line of animals being killed"
    },
    "groupName": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-GroupName",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "Name of the group within the processor's location"
    },
    "eASDReference": {
      "@id": "https://www.datalinker.org/context/CarcassKillsheet-eASDReference",
      "@type": "xsd:string",
      "type": "string",
      "dldescription": "A reference code to the relavent movement document used to officially declare the animal movement, e.g. Animal Status Declaration for New Zealand"
    }
  }
}
