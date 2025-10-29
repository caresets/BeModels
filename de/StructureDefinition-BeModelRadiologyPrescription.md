# BeModelRadiologyPrescription - CareSets - data models v0.1.0

## : BeModelRadiologyPrescription 

 
Data model for the nursing prescription referral. 

**Usages:**

* This Logical Model is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/hl7.be.fhir.models|current/StructureDefinition/BeModelRadiologyPrescription)

### 

 . 

*   
*   
*   
*   

**Summary**

Mandatory: 0 element(1 nested mandatory element)

 **View** 

**Summary**

Mandatory: 0 element(1 nested mandatory element)

 

 ,  



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "BeModelRadiologyPrescription",
  "language" : "en",
  "extension" : [
    {
      "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-type-characteristics",
      "valueCode" : "can-be-target"
    },
    {
      "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-type-characteristics",
      "valueCode" : "can-be-target"
    }
  ],
  "url" : "http://example.org/StructureDefinition/BeModelRadiologyPrescription",
  "version" : "0.1.0",
  "name" : "BeModelRadiologyPrescription",
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
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:43+0000\\nPO-Revision-Date: 2025-10-21 10:43+0000\\nLanguage: FR\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
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
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:49+0000\\nPO-Revision-Date: 2025-10-21 10:49+0000\\nLanguage: NL\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
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
  "description" : "Data model for the nursing prescription referral.",
  "fhirVersion" : "4.0.1",
  "kind" : "logical",
  "abstract" : false,
  "type" : "http://example.org/StructureDefinition/BeModelRadiologyPrescription",
  "baseDefinition" : "http://example.org/StructureDefinition/BeModelReferralPrescription",
  "derivation" : "specialization",
  "differential" : {
    "element" : [
      {
        "id" : "BeModelRadiologyPrescription",
        "path" : "BeModelRadiologyPrescription",
        "short" : "BeModelRadiologyPrescription",
        "definition" : "Data model for the nursing prescription referral.",
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
                  "valueString" : "Modèle de données pour l'orientation des prescriptions infirmières."
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
                  "valueString" : "Gegevensmodel voor de verpleegkundige voorschriftverwijzing."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        }
      },
      {
        "id" : "BeModelRadiologyPrescription.priority",
        "path" : "BeModelRadiologyPrescription.priority",
        "short" : "The priority of the referral or transfer request.",
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
                  "valueString" : "La priorité de la demande de renvoi ou de transfert."
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
                  "valueString" : "De prioriteit van de doorverwijzing of transferaanvraag."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The priority of the referral or transfer request.",
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
                  "valueString" : "La priorité de la demande de renvoi ou de transfert."
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
                  "valueString" : "De prioriteit van de doorverwijzing of transferaanvraag."
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
        "id" : "BeModelRadiologyPrescription.priorityReason",
        "path" : "BeModelRadiologyPrescription.priorityReason",
        "short" : "The reason for the priority assigned to a referral or transfer request.",
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
                  "valueString" : "La raison de la priorité attribuée à une demande de renvoi ou de transfert."
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
                  "valueString" : "De reden voor de prioriteit die aan een verwijzings- of doorverwijsverzoek is toegekend."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "The reason for the priority assigned to a referral or transfer request.",
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
                  "valueString" : "La raison de la priorité attribuée à une demande de renvoi ou de transfert."
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
                  "valueString" : "De reden voor de prioriteit die aan een verwijzings- of doorverwijsverzoek is toegekend."
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
        "id" : "BeModelRadiologyPrescription.additionalInfo",
        "path" : "BeModelRadiologyPrescription.additionalInfo",
        "short" : "Additional information that may be needed in the future to act on the request.",
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
                  "valueString" : "Les informations supplémentaires qui pourraient être nécessaires à l'avenir pour donner suite à la demande."
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
                  "valueString" : "Aanvullende informatie die in de toekomst nodig kan zijn om op het verzoek te reageren."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Additional information that may be needed in the future to act on the request.",
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
                  "valueString" : "Les informations supplémentaires qui pourraient être nécessaires à l'avenir pour donner suite à la demande."
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
                  "valueString" : "Aanvullende informatie die in de toekomst nodig kan zijn om op het verzoek te reageren."
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
        "id" : "BeModelRadiologyPrescription.previousExams",
        "path" : "BeModelRadiologyPrescription.previousExams",
        "short" : "Procedures that are related to this referral request.",
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
                  "valueString" : "Procédures liées à cette demande de renvoi."
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
                  "valueString" : "Procedures die verband houden met dit verwijzingsverzoek."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Procedures that are related to this referral request.",
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
                  "valueString" : "Procédures liées à cette demande de renvoi."
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
                  "valueString" : "Procedures die verband houden met dit verwijzingsverzoek."
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
        "id" : "BeModelRadiologyPrescription.pssInfo",
        "path" : "BeModelRadiologyPrescription.pssInfo",
        "short" : "Identifier of the prescription in the PSS system.",
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
                  "valueString" : "Identifiant de la prescription dans le système PSS."
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
                  "valueString" : "Identificatiecode van het recept in het PSS-systeem."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Identifier of the prescription search in the PSS system.",
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
                  "valueString" : "Identifiant de la recherche de prescription dans le système PSS."
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
                  "valueString" : "Identificatiecode van het zoeken naar een recept in het PSS-systeem."
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
            "code" : "Identifier"
          }
        ]
      },
      {
        "id" : "BeModelRadiologyPrescription.indication",
        "path" : "BeModelRadiologyPrescription.indication",
        "short" : "Indications supporting the referral request.",
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
                  "valueString" : "Indications à l'appui de la demande de renvoi."
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
                  "valueString" : "Indicaties die de verwijzingsaanvraag ondersteunen."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Indications supporting the referral request.",
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
                  "valueString" : "Indications à l'appui de la demande de renvoi."
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
                  "valueString" : "Indicaties die de verwijzingsaanvraag ondersteunen."
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
        "id" : "BeModelRadiologyPrescription.explanationForRequest",
        "path" : "BeModelRadiologyPrescription.explanationForRequest",
        "short" : "Explanation/Justification for the referral.",
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
                  "valueString" : "Explication/justification de la saisine."
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
                  "valueString" : "Uitleg/rechtvaardiging voor de verwijzing."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Explanation/Justification for the referral.",
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
                  "valueString" : "Explication/justification de la saisine."
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
                  "valueString" : "Uitleg/rechtvaardiging voor de verwijzing."
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
            "code" : "Annotation"
          }
        ]
      },
      {
        "id" : "BeModelRadiologyPrescription.bodySite",
        "path" : "BeModelRadiologyPrescription.bodySite",
        "short" : "Anatomical location where the treatment should be applied (for example: 'Left arm').",
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
                  "valueString" : "Lieu anatomique où le traitement doit être appliqué (par exemple : \"Bras gauche\")."
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
                  "valueString" : "Anatomische locatie waar de behandeling moet worden toegepast (bijvoorbeeld: \"Linkerarm\")."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Anatomical location where the treatment should be applied (for example: 'Left arm').",
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
                  "valueString" : "Lieu anatomique où le traitement doit être appliqué (par exemple : \"Bras gauche\")."
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
                  "valueString" : "Anatomische locatie waar de behandeling moet worden toegepast (bijvoorbeeld: \"Linkerarm\")."
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
        "id" : "BeModelRadiologyPrescription.bodyLaterality",
        "path" : "BeModelRadiologyPrescription.bodyLaterality",
        "short" : "Laterality of the anatomical location where the treatment should be applied (for example: 'Left').",
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
                  "valueString" : "Latéralité de l'emplacement anatomique où le traitement doit être appliqué (par exemple : \"gauche\")."
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
                  "valueString" : "Lateraliteit van de anatomische locatie waar de behandeling moet worden toegepast (bijvoorbeeld: \"Links\")."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Laterality of the anatomical location where the treatment should be applied (for example: \"Left\").",
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
                  "valueString" : "Latéralité de l'emplacement anatomique où le traitement doit être appliqué (par exemple : \"Gauche\")."
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
                  "valueString" : "Lateraliteit van de anatomische locatie waar de behandeling moet worden toegepast (bijvoorbeeld: \"Links\")."
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
        "id" : "BeModelRadiologyPrescription.pssIdentifier",
        "path" : "BeModelRadiologyPrescription.pssIdentifier",
        "short" : "Identifier of the prescription in the PSS system.",
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
                  "valueString" : "Identifiant de la prescription dans le système PSS."
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
                  "valueString" : "Identificatiecode van het recept in het PSS-systeem."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Identifier of the prescription in the PSS system.",
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
                  "valueString" : "Identifiant de la prescription dans le système PSS."
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
                  "valueString" : "Identificatiecode van het recept in het PSS-systeem."
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
            "code" : "Identifier"
          }
        ]
      }
    ]
  }
}

```
