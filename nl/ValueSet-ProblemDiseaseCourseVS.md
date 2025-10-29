# Conditie Ziekte Cursus Waardeset - CareSets - data models v0.1.0

## ValueSet: Conditie Ziekte Cursus Waardeset 

 
Condition Disease Course 

 **References** 

* [Problem Logical Model](StructureDefinition-BeModelProblem.md)

### Logical Definition (CLD)

Taal: en

* Include codes uit[`http://snomed.info/sct`](http://www.snomed.org/)versie 📍 waar concept is-a 288524001

 

### Uitbreiding

No Expansion for this valueset (not supported by Publication Tooling)

-------

 [Beschrijving van bovenstaande tabel(len)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "ProblemDiseaseCourseVS",
  "language" : "en",
  "url" : "http://example.org/ValueSet/ProblemDiseaseCourseVS",
  "version" : "0.1.0",
  "name" : "ProblemDiseaseCourseVS",
  "_name" : {
    "extension" : [
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "nl"
          },
          {
            "url" : "content",
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:50+0000\\nPO-Revision-Date: 2025-10-21 10:50+0000\\nLanguage: NL\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
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
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:43+0000\\nPO-Revision-Date: 2025-10-21 10:43+0000\\nLanguage: FR\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      }
    ]
  },
  "title" : "Condition Disease Course Value Set",
  "_title" : {
    "extension" : [
      {
        "extension" : [
          {
            "url" : "lang",
            "valueCode" : "fr"
          },
          {
            "url" : "content",
            "valueString" : "Condition Maladie Cours Ensemble de valeurs"
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
            "valueString" : "Conditie Ziekte Cursus Waardeset"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      }
    ]
  },
  "status" : "draft",
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
  "description" : "Condition Disease Course",
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
            "valueString" : "Cours sur l'état de santé et les maladies"
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
            "valueString" : "Conditie Ziekte Cursus"
          }
        ],
        "url" : "http://hl7.org/fhir/StructureDefinition/translation"
      }
    ]
  },
  "compose" : {
    "include" : [
      {
        "system" : "http://snomed.info/sct",
        "version" : "http://snomed.info/sct/11000172109",
        "_version" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "nl"
                },
                {
                  "url" : "content",
                  "valueString" : "http://snomed.info/sct/11000172109"
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
                  "valueString" : "http://snomed.info/sct/11000172109"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "filter" : [
          {
            "property" : "concept",
            "op" : "is-a",
            "value" : "288524001",
            "_value" : {
              "extension" : [
                {
                  "extension" : [
                    {
                      "url" : "lang",
                      "valueCode" : "fr"
                    },
                    {
                      "url" : "content",
                      "valueString" : "288524001"
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
                      "valueString" : "288524001"
                    }
                  ],
                  "url" : "http://hl7.org/fhir/StructureDefinition/translation"
                }
              ]
            }
          }
        ]
      }
    ]
  }
}

```
