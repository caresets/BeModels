# CodeSysteem voor gemeenschappelijke CareSets woordenlijst - CareSets - data models v0.1.0

## CodeSystem: CodeSysteem voor gemeenschappelijke CareSets woordenlijst (Experimenteel) 

 
Dit codesysteem definieert concepten die worden gebruikt in de BeSafe CareSets voor algemene termen. 

Dit codesysteem wordt gebruikt in de volgende waardesets:

* Dit CodeSystem wordt hier niet gebruikt; het wordt mogelijk elders gebruikt (bijv. specificaties en/of implementaties die deze content gebruiken)

Taal: en

Profiels: `http://hl7.org/fhir/uv/crmi/StructureDefinition/crmi-shareablecodesystem`, `http://hl7.org/fhir/uv/crmi/StructureDefinition/crmi-publishablecodesystem`

Dit case-insensitive codesysteem `http://example.org/CodeSystem/BeSafeShareGlossary` definieert de volgende codes:

**Additionele taalweergaven**

-------

 [Beschrijving van bovenstaande tabel(len)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "BeSafeShareGlossary",
  "meta" : {
    "profile" : [
      "http://hl7.org/fhir/uv/crmi/StructureDefinition/crmi-shareablecodesystem",
      "http://hl7.org/fhir/uv/crmi/StructureDefinition/crmi-publishablecodesystem"
    ]
  },
  "language" : "en",
  "url" : "http://example.org/CodeSystem/BeSafeShareGlossary",
  "version" : "0.1.0",
  "name" : "BeSafeShareGlossary",
  "_name" : {
    "extension" : [
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "fr"
          },
          {
            "url" : "content",
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:40+0000\\nPO-Revision-Date: 2025-10-21 10:40+0000\\nLanguage: FR\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      },
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "nl"
          },
          {
            "url" : "content",
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:47+0000\\nPO-Revision-Date: 2025-10-21 10:47+0000\\nLanguage: NL\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      }
    ]
  },
  "title" : "CodeSystem for common CareSets glossary",
  "_title" : {
    "extension" : [
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "nl"
          },
          {
            "url" : "content",
            "valueString" : "CodeSysteem voor gemeenschappelijke CareSets woordenlijst"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      },
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "fr"
          },
          {
            "url" : "content",
            "valueString" : "CodeSystem pour le glossaire des ensembles de soins communs"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      }
    ]
  },
  "status" : "draft",
  "experimental" : true,
  "date" : "2025-10-29T07:49:40+00:00",
  "publisher" : "RIZIV/INAMI",
  "_publisher" : {
    "extension" : [
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "fr"
          },
          {
            "url" : "content",
            "valueString" : "RISQUE/INAMI"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      },
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "nl"
          },
          {
            "url" : "content",
            "valueString" : "RISICO/INAMI"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      }
    ]
  },
  "contact" : [
    {
      "name" : "RIZIV/INAMI",
      "telecom" : [
        {
          "system" : "url",
          "value" : "http://example.org/example-publisher"
        }
      ]
    }
  ],
  "description" : "This code system defines concepts used in the BeSafe CareSets for common glossary terms.",
  "_description" : {
    "extension" : [
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "fr"
          },
          {
            "url" : "content",
            "valueString" : "Ce système de codes définit les concepts utilisés dans les ensembles de soins BeSafe pour les termes du glossaire commun."
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      },
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "nl"
          },
          {
            "url" : "content",
            "valueString" : "Dit codesysteem definieert concepten die worden gebruikt in de BeSafe CareSets voor algemene termen."
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      }
    ]
  },
  "caseSensitive" : false,
  "content" : "complete",
  "count" : 4,
  "concept" : [
    {
      "code" : "careset-business-identifier",
      "display" : "Business Identifier of the careset",
      "designation" : [
        {
          "language" : "nl",
          "value" : "Bedrijfsidentificatie van de zorgset"
        },
        {
          "language" : "fr",
          "value" : "Identifiant d'entreprise de l'ensemble de soins"
        }
      ]
    },
    {
      "code" : "recorded-date",
      "display" : "Date the record was first created in the system",
      "designation" : [
        {
          "language" : "fr",
          "value" : "Date de création de l'enregistrement dans le système"
        },
        {
          "language" : "nl",
          "value" : "Datum waarop het record voor het eerst is aangemaakt in het systeem"
        }
      ]
    },
    {
      "code" : "recorder",
      "display" : "Person who recorded the information"
    },
    {
      "code" : "patient",
      "display" : "The patient that is the subject of the record"
    }
  ]
}

```
