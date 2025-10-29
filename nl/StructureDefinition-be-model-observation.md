# Model BeObservation - CareSets - data models v0.1.0

## Logisch model: Model BeObservation 

 
Observation logical model 

**Usages:**

* This Logical Model is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/hl7.be.fhir.models|current/StructureDefinition/be-model-observation)

### Formele weergaven van de profielinhoud

 [Beschrijving van profielen, differentials, snapshots en hun representaties](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

*  [Differentieletabel](#tabs-diff) 
*  [Momentopnametabel](#tabs-snap) 
*  [Statistieken/Referenties](#tabs-summ) 
*  [Alles](#tabs-all) 

Deze structuur is afgeleid van [Base](http://build.fhir.org/types.html#Base) 

#### Constrains

Deze structuur is afgeleid van [Base](http://build.fhir.org/types.html#Base) 

**Samenvatting**

Vereist: 0 element(8 genest vereist elements)

 **Differentieelweergave** 

Deze structuur is afgeleid van [Base](http://build.fhir.org/types.html#Base) 

 **MomentopnameweergaveView** 

#### Constrains

Deze structuur is afgeleid van [Base](http://build.fhir.org/types.html#Base) 

**Samenvatting**

Vereist: 0 element(8 genest vereist elements)

 

Andere representaties van het profiel: [CSV](../StructureDefinition-be-model-observation.csv), [Excel](../StructureDefinition-be-model-observation.xlsx) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "be-model-observation",
  "language" : "en",
  "url" : "http://example.org/StructureDefinition/be-model-observation",
  "version" : "0.1.0",
  "name" : "BeModelObservation",
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
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:41+0000\\nPO-Revision-Date: 2025-10-21 10:41+0000\\nLanguage: FR\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
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
  "title" : "BeObservation Model",
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
            "valueString" : "Modèle BeObservation"
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
            "valueString" : "Model BeObservation"
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
  "description" : "Observation logical model",
  "fhirVersion" : "4.0.1",
  "kind" : "logical",
  "abstract" : false,
  "type" : "http://example.org/StructureDefinition/be-model-observation",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Base",
  "derivation" : "specialization",
  "differential" : {
    "element" : [
      {
        "id" : "be-model-observation",
        "path" : "be-model-observation",
        "short" : "BeObservation Model",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Modèle BeObservation"
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
                  "valueString" : "Model BeObservation"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Observation logical model",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Modèle logique d'observation"
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
                  "valueString" : "Waarneming logisch model"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        }
      },
      {
        "id" : "be-model-observation.identifier",
        "path" : "be-model-observation.identifier",
        "code" : [
          {
            "system" : "http://example.org/CodeSystem/BeSafeShareGlossary",
            "code" : "careset-business-identifier"
          }
        ],
        "short" : "Unique identifier for the observation",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Identifiant unique de l'observation"
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
                  "valueString" : "Unieke identifier voor de waarneming"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Unique identifier for the observation",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Identifiant unique de l'observation"
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
                  "valueString" : "Unieke identifier voor de waarneming"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 1,
        "max" : "*",
        "type" : [
          {
            "code" : "Identifier"
          }
        ]
      },
      {
        "id" : "be-model-observation.recordedDate",
        "path" : "be-model-observation.recordedDate",
        "code" : [
          {
            "system" : "http://example.org/CodeSystem/BeSafeShareGlossary",
            "code" : "recorded-date"
          }
        ],
        "short" : "Date when the observation was recorded",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Date d'enregistrement de l'observation"
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
                  "valueString" : "Datum waarop de observatie werd geregistreerd"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Date when the observation was recorded",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Date d'enregistrement de l'observation"
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
                  "valueString" : "Datum waarop de observatie werd geregistreerd"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 1,
        "max" : "1",
        "type" : [
          {
            "code" : "dateTime"
          }
        ]
      },
      {
        "id" : "be-model-observation.observationDate[x]",
        "path" : "be-model-observation.observationDate[x]",
        "short" : "Date or period of the observation",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Date ou période de l'observation"
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
                  "valueString" : "Datum of periode van de observatie"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Date or period of the observation",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Date ou période de l'observation"
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
                  "valueString" : "Datum of periode van de observatie"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 1,
        "max" : "1",
        "type" : [
          {
            "code" : "dateTime"
          },
          {
            "code" : "Period"
          }
        ]
      },
      {
        "id" : "be-model-observation.recorder",
        "path" : "be-model-observation.recorder",
        "code" : [
          {
            "system" : "http://example.org/CodeSystem/BeSafeShareGlossary",
            "code" : "recorder"
          }
        ],
        "short" : "Person, organisation or device that recorded the observation",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Personne, organisation ou dispositif ayant enregistré l'observation"
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
                  "valueString" : "Persoon, organisatie of apparaat dat de observatie heeft geregistreerd"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Person, organisation or device that recorded the observation",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Personne, organisation ou dispositif ayant enregistré l'observation"
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
                  "valueString" : "Persoon, organisatie of apparaat dat de observatie heeft geregistreerd"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 1,
        "max" : "1",
        "type" : [
          {
            "code" : "Reference"
          }
        ]
      },
      {
        "id" : "be-model-observation.performer",
        "path" : "be-model-observation.performer",
        "short" : "The professional that performed the observation",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le professionnel qui a effectué l'observation"
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
                  "valueString" : "De professional die de observatie heeft uitgevoerd"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The professional that performed the observation",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le professionnel qui a effectué l'observation"
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
                  "valueString" : "De professional die de observatie heeft uitgevoerd"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Reference"
          }
        ]
      },
      {
        "id" : "be-model-observation.patient",
        "path" : "be-model-observation.patient",
        "code" : [
          {
            "system" : "http://example.org/CodeSystem/BeSafeShareGlossary",
            "code" : "patient"
          },
          {
            "system" : "http://snomed.info/sct",
            "code" : "410604004"
          }
        ],
        "short" : "The patient that this observation is about",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le patient sur lequel porte cette observation"
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
                  "valueString" : "De patiënt waar deze observatie over gaat"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The patient that this observation is about",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le patient sur lequel porte cette observation"
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
                  "valueString" : "De patiënt waar deze observatie over gaat"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 1,
        "max" : "1",
        "type" : [
          {
            "code" : "Reference"
          }
        ]
      },
      {
        "id" : "be-model-observation.request",
        "path" : "be-model-observation.request",
        "short" : "The request that this observation is fulfilling",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "La demande à laquelle répond cette observation"
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
                  "valueString" : "Het verzoek waaraan deze observatie voldoet"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The request that this observation is fulfilling",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "La demande à laquelle répond cette observation"
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
                  "valueString" : "Het verzoek waaraan deze observatie voldoet"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Reference"
          }
        ]
      },
      {
        "id" : "be-model-observation.partOfProcedure",
        "path" : "be-model-observation.partOfProcedure",
        "short" : "Part of referenced procedure",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Partie de la procédure référencée"
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
                  "valueString" : "Deel van procedure waarnaar wordt verwezen"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Part of referenced procedure",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Partie de la procédure référencée"
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
                  "valueString" : "Deel van procedure waarnaar wordt verwezen"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "*",
        "type" : [
          {
            "code" : "Reference"
          }
        ]
      },
      {
        "id" : "be-model-observation.specimen",
        "path" : "be-model-observation.specimen",
        "short" : "The specimen that was used when this observation was made",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le spécimen utilisé lors de cette observation"
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
                  "valueString" : "Het exemplaar dat werd gebruikt toen deze waarneming werd gedaan"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The specimen that was used when this observation was made",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le spécimen utilisé lors de cette observation"
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
                  "valueString" : "Het exemplaar dat werd gebruikt toen deze waarneming werd gedaan"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Reference"
          }
        ]
      },
      {
        "id" : "be-model-observation.device",
        "path" : "be-model-observation.device",
        "short" : "The device used to generate the observation data",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le dispositif utilisé pour générer les données d'observation"
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
                  "valueString" : "Het apparaat dat wordt gebruikt om de observatiegegevens te genereren"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The device used to generate the observation data",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le dispositif utilisé pour générer les données d'observation"
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
                  "valueString" : "Het apparaat dat wordt gebruikt om de observatiegegevens te genereren"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Reference"
          }
        ]
      },
      {
        "id" : "be-model-observation.category",
        "path" : "be-model-observation.category",
        "short" : "A code that classifies the general type of observation being made",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Un code qui classifie le type général d'observation effectuée"
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
                  "valueString" : "Een code die het algemene type observatie classificeert dat wordt gemaakt"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "A code that classifies the general type of observation being made",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Un code qui classifie le type général d'observation effectuée"
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
                  "valueString" : "Een code die het algemene type observatie classificeert dat wordt gemaakt"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "*",
        "type" : [
          {
            "code" : "CodeableConcept"
          }
        ]
      },
      {
        "id" : "be-model-observation.code",
        "path" : "be-model-observation.code",
        "short" : "Describes what was observed. Sometimes this is called the observation 'name'",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Décrit ce qui a été observé. On parle parfois de \"nom\" de l'observation"
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
                  "valueString" : "Beschrijft wat er is waargenomen. Soms wordt dit de 'naam' van de observatie genoemd"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Describes what was observed. Sometimes this is called the observation 'name'",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Décrit ce qui a été observé. On parle parfois de \"nom\" de l'observation"
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
                  "valueString" : "Beschrijft wat er is waargenomen. Soms wordt dit de 'naam' van de observatie genoemd"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 1,
        "max" : "1",
        "type" : [
          {
            "code" : "CodeableConcept"
          }
        ]
      },
      {
        "id" : "be-model-observation.value[x]",
        "path" : "be-model-observation.value[x]",
        "short" : "The value of the observation - typically a code, an amount or a date",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "La valeur de l'observation - typiquement un code, un montant ou une date"
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
                  "valueString" : "De waarde van de waarneming - meestal een code, een bedrag of een datum"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The value of the observation - typically a code, an amount or a date",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "La valeur de l'observation - typiquement un code, un montant ou une date"
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
                  "valueString" : "De waarde van de waarneming - meestal een code, een bedrag of een datum"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Quantity"
          },
          {
            "code" : "CodeableConcept"
          },
          {
            "code" : "string"
          },
          {
            "code" : "boolean"
          },
          {
            "code" : "integer"
          },
          {
            "code" : "Range"
          },
          {
            "code" : "Ratio"
          },
          {
            "code" : "time"
          },
          {
            "code" : "dateTime"
          },
          {
            "code" : "Period"
          }
        ]
      },
      {
        "id" : "be-model-observation.component",
        "path" : "be-model-observation.component",
        "short" : "Some observations have multiple component observations",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Certaines observations ont plusieurs composantes"
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
                  "valueString" : "Sommige waarnemingen hebben meerdere componentwaarnemingen"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Some observations have multiple component observations",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Certaines observations ont plusieurs composantes"
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
                  "valueString" : "Sommige waarnemingen hebben meerdere componentwaarnemingen"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "*",
        "type" : [
          {
            "code" : "BackboneElement"
          }
        ]
      },
      {
        "id" : "be-model-observation.component.code",
        "path" : "be-model-observation.component.code",
        "short" : "Describes what was observed.",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Décrit ce qui a été observé."
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
                  "valueString" : "Beschrijft wat er is waargenomen."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Describes what was observed.",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Décrit ce qui a été observé."
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
                  "valueString" : "Beschrijft wat er is waargenomen."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 1,
        "max" : "1",
        "type" : [
          {
            "code" : "CodeableConcept"
          }
        ]
      },
      {
        "id" : "be-model-observation.component.value[x]",
        "path" : "be-model-observation.component.value[x]",
        "short" : "The value of the component observation - typically a code, an amount or a date",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "La valeur de l'observation du composant - typiquement un code, un montant ou une date"
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
                  "valueString" : "De waarde van de componentwaarneming - meestal een code, een bedrag of een datum"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The value of the component observation - typically a code, an amount or a date",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "La valeur de l'observation du composant - typiquement un code, un montant ou une date"
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
                  "valueString" : "De waarde van de componentwaarneming - meestal een code, een bedrag of een datum"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Quantity"
          },
          {
            "code" : "CodeableConcept"
          },
          {
            "code" : "string"
          },
          {
            "code" : "boolean"
          },
          {
            "code" : "integer"
          },
          {
            "code" : "Range"
          },
          {
            "code" : "Ratio"
          },
          {
            "code" : "time"
          },
          {
            "code" : "dateTime"
          },
          {
            "code" : "Period"
          }
        ]
      },
      {
        "id" : "be-model-observation.status",
        "path" : "be-model-observation.status",
        "short" : "The status of the result value.",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le statut de la valeur du résultat."
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
                  "valueString" : "De status van de resultaatwaarde."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The status of the result value.",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le statut de la valeur du résultat."
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
                  "valueString" : "De status van de resultaatwaarde."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 1,
        "max" : "1",
        "type" : [
          {
            "code" : "code"
          }
        ]
      },
      {
        "id" : "be-model-observation.interpretation",
        "path" : "be-model-observation.interpretation",
        "short" : "A categorical assessment of an observation value",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Évaluation catégorique d'une valeur d'observation"
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
                  "valueString" : "Een categorische beoordeling van een waarnemingswaarde"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "A categorical assessment of an observation value",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Évaluation catégorique d'une valeur d'observation"
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
                  "valueString" : "Een categorische beoordeling van een waarnemingswaarde"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "*",
        "type" : [
          {
            "code" : "CodeableConcept"
          }
        ]
      },
      {
        "id" : "be-model-observation.referenceRange",
        "path" : "be-model-observation.referenceRange",
        "short" : "Guidance on how to interpret the value by comparison to a normal or recommended range",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Conseils sur la manière d'interpréter la valeur en la comparant à une fourchette normale ou recommandée"
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
                  "valueString" : "Richtlijnen voor de interpretatie van de waarde door vergelijking met een normaal of aanbevolen bereik"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Guidance on how to interpret the value by comparison to a normal or recommended range",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Conseils sur la manière d'interpréter la valeur en la comparant à une fourchette normale ou recommandée"
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
                  "valueString" : "Richtlijnen voor de interpretatie van de waarde door vergelijking met een normaal of aanbevolen bereik"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "*",
        "type" : [
          {
            "code" : "BackboneElement"
          }
        ]
      },
      {
        "id" : "be-model-observation.referenceRange.low",
        "path" : "be-model-observation.referenceRange.low",
        "short" : "Low Range, if relevant",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Fourchette basse, le cas échéant"
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
                  "valueString" : "Laag bereik, indien relevant"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Low Range, if relevant",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Fourchette basse, le cas échéant"
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
                  "valueString" : "Laag bereik, indien relevant"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Quantity"
          }
        ]
      },
      {
        "id" : "be-model-observation.referenceRange.high",
        "path" : "be-model-observation.referenceRange.high",
        "short" : "High Range, if relevant",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Fourchette haute, le cas échéant"
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
                  "valueString" : "Hoog bereik, indien relevant"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "High Range, if relevant",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Fourchette haute, le cas échéant"
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
                  "valueString" : "Hoog bereik, indien relevant"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "Quantity"
          }
        ]
      },
      {
        "id" : "be-model-observation.bodySite",
        "path" : "be-model-observation.bodySite",
        "short" : "The site on the subject's body where the observation was made (i.e. the target site)",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le site sur le corps du sujet où l'observation a été faite (c'est-à-dire le site cible)"
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
                  "valueString" : "De plaats op het lichaam van de proefpersoon waar de observatie werd uitgevoerd (d.w.z. de doellocatie)"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The site on the subject's body where the observation was made (i.e. the target site)",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Le site du corps du sujet où l'observation a été faite (c'est-à-dire le site cible)."
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
                  "valueString" : "De plaats op het lichaam van de proefpersoon waar de observatie werd uitgevoerd (d.w.z. de doellocatie)"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "http://example.org/StructureDefinition/be-model-bodysite"
          }
        ]
      },
      {
        "id" : "be-model-observation.certainty",
        "path" : "be-model-observation.certainty",
        "short" : "A subjective assessment of the quality of the observation",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Une évaluation subjective de la qualité de l'observation"
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
                  "valueString" : "Een subjectieve beoordeling van de kwaliteit van de observatie"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "A subjective assessment of the quality of the observation",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Une évaluation subjective de la qualité de l'observation"
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
                  "valueString" : "Een subjectieve beoordeling van de kwaliteit van de observatie"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "1",
        "type" : [
          {
            "code" : "CodeableConcept"
          }
        ]
      },
      {
        "id" : "be-model-observation.note",
        "path" : "be-model-observation.note",
        "short" : "Comments about the observation or the results",
        "_short" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Commentaires sur l'observation ou les résultats"
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
                  "valueString" : "Opmerkingen over de observatie of de resultaten"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Comments about the observation or the results",
        "_definition" : {
          "extension" : [
            {
              "extension" : [
                {
                  "url" : "lang",
                  "valueCode" : "fr"
                },
                {
                  "url" : "content",
                  "valueString" : "Commentaires sur l'observation ou les résultats"
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
                  "valueString" : "Opmerkingen over de observatie of de resultaten"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "min" : 0,
        "max" : "*",
        "type" : [
          {
            "code" : "Annotation"
          }
        ]
      }
    ]
  }
}

```
