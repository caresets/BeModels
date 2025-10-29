# BeModelAssignment - CareSets - data models v0.1.0

## : BeModelAssignment 

 
Logical model with the information for the assignment to a referral prescription of a care provider. 

**Usages:**

* This Logical Model is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/hl7.be.fhir.models|current/StructureDefinition/BeModelAssignment)

### 

 . 

*   
*   
*   
*   

#### Constraints

**Summary**

Mandatory: 0 element(7 nested mandatory elements)

**Structures**

This structure refers to these other structures:

* [BeModelTreatmentStatus(http://example.org/StructureDefinition/BeModelTreatmentStatus)](StructureDefinition-BeModelTreatmentStatus.md)
* [BeModelOrganisationClaim(http://example.org/StructureDefinition/BeModelOrganisationClaim)](StructureDefinition-BeModelOrganisationClaim.md)

 **View** 

#### Constraints

**Summary**

Mandatory: 0 element(7 nested mandatory elements)

**Structures**

This structure refers to these other structures:

* [BeModelTreatmentStatus(http://example.org/StructureDefinition/BeModelTreatmentStatus)](StructureDefinition-BeModelTreatmentStatus.md)
* [BeModelOrganisationClaim(http://example.org/StructureDefinition/BeModelOrganisationClaim)](StructureDefinition-BeModelOrganisationClaim.md)

 

 ,  



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "BeModelAssignment",
  "language" : "en",
  "extension" : [
    {
      "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-type-characteristics",
      "valueCode" : "can-be-target"
    }
  ],
  "url" : "http://example.org/StructureDefinition/BeModelAssignment",
  "version" : "0.1.0",
  "name" : "BeModelAssignment",
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
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:42+0000\\nPO-Revision-Date: 2025-10-21 10:42+0000\\nLanguage: FR\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
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
            "valueString" : "Project-Id-Version: FHIR\\nReport-Msgid-Bugs-To: you@example.com\\nPOT-Creation-Date: 2025-10-21 10:48+0000\\nPO-Revision-Date: 2025-10-21 10:48+0000\\nLanguage: NL\\nMIME-Version: 1.0\\nContent-Type: text/plain; charset=UTF-8\\nContent-Transfer-Encoding: 8bit\\n"
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
  "description" : "Logical model with the information for the assignment to a referral prescription of a care provider.",
  "fhirVersion" : "4.0.1",
  "kind" : "logical",
  "abstract" : false,
  "type" : "http://example.org/StructureDefinition/BeModelAssignment",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Base",
  "derivation" : "specialization",
  "differential" : {
    "element" : [
      {
        "id" : "BeModelAssignment",
        "path" : "BeModelAssignment",
        "short" : "BeModelAssignment",
        "definition" : "Logical model with the information for the assignment to a referral prescription of a care provider.",
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
                  "valueString" : "Modèle logique contenant les informations relatives à l'affectation à une prescription de référence d'un prestataire de soins."
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
                  "valueString" : "Logisch model met de informatie voor de toewijzing aan een verwijzingsrecept van een zorgverlener."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        }
      },
      {
        "id" : "BeModelAssignment.identifier",
        "path" : "BeModelAssignment.identifier",
        "short" : "Business identifier. Absent during creation by client software, otherwise always present.",
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
                  "valueString" : "Identifiant de l'entreprise. Absent lors de la création par le logiciel client, sinon toujours présent."
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
                  "valueString" : "Bedrijfsidentificatie. Afwezig tijdens creatie door clientsoftware, anders altijd aanwezig."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Business identifier. Absent during creation by client software, otherwise always present.",
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
                  "valueString" : "Identifiant de l'entreprise. Absent lors de la création par le logiciel client, sinon toujours présent."
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
                  "valueString" : "Bedrijfsidentificatie. Afwezig tijdens creatie door clientsoftware, anders altijd aanwezig."
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
            "code" : "Identifier"
          }
        ]
      },
      {
        "id" : "BeModelAssignment.intent",
        "path" : "BeModelAssignment.intent",
        "short" : "Defaults to 'Order', since in this case it is always linked to a referral prescription.",
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
                  "valueString" : "La valeur par défaut est \"Ordre\", car dans ce cas, il est toujours lié à une prescription de référence."
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
                  "valueString" : "Staat standaard op 'Bestellen', omdat het in dit geval altijd gekoppeld is aan een verwijzingsrecept."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Defaults to 'Order', since in this case it is always linked to a referral prescription.",
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
                  "valueString" : "La valeur par défaut est \"Ordre\", car dans ce cas, il est toujours lié à une prescription de référence."
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
                  "valueString" : "Staat standaard op 'Bestellen', omdat het in dit geval altijd gekoppeld is aan een verwijzingsrecept."
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
        "id" : "BeModelAssignment.status",
        "path" : "BeModelAssignment.status",
        "short" : "Status of the task",
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
                  "valueString" : "Statut de la tâche"
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
                  "valueString" : "Status van de taak"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Status of the task",
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
                  "valueString" : "Statut de la tâche"
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
                  "valueString" : "Status van de taak"
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
        "id" : "BeModelAssignment.statusReason",
        "path" : "BeModelAssignment.statusReason",
        "short" : "Provides details on the status of the task",
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
                  "valueString" : "Fournit des détails sur l'état de la tâche"
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
                  "valueString" : "Geeft details over de status van de taak"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Provides details on the status of the task",
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
                  "valueString" : "Fournit des détails sur l'état de la tâche"
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
                  "valueString" : "Geeft details over de status van de taak"
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
        "id" : "BeModelAssignment.originRequestId",
        "path" : "BeModelAssignment.originRequestId",
        "short" : "Reference to the associated referral prescription",
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
                  "valueString" : "Référence à la prescription de référence associée"
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
                  "valueString" : "Verwijzing naar het bijbehorende verwijzingsvoorschrift"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Reference to the associated referral prescription",
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
                  "valueString" : "Référence à la prescription de référence associée"
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
                  "valueString" : "Verwijzing naar het bijbehorende verwijzingsvoorschrift"
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
            "code" : "Identifier"
          }
        ]
      },
      {
        "id" : "BeModelAssignment.treatmentStatusId",
        "path" : "BeModelAssignment.treatmentStatusId",
        "short" : "Reference to the 'TreatmentStatus', the treatment tracking associated with the prescription",
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
                  "valueString" : "Référence au \"TreatmentStatus\", le suivi du traitement associé à la prescription"
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
                  "valueString" : "Verwijzing naar de \"TreatmentStatus\", het bijhouden van de behandeling van het voorschrift"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Reference to the 'TreatmentStatus', the treatment tracking associated with the prescription",
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
                  "valueString" : "Référence au \"TreatmentStatus\", le suivi du traitement associé à la prescription"
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
                  "valueString" : "Verwijzing naar de \"TreatmentStatus\", het bijhouden van de behandeling van het voorschrift"
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
            "code" : "Reference",
            "targetProfile" : [
              "http://example.org/StructureDefinition/BeModelTreatmentStatus"
            ]
          }
        ]
      },
      {
        "id" : "BeModelAssignment.organizationID",
        "path" : "BeModelAssignment.organizationID",
        "short" : "Reference to the organization Task",
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
                  "valueString" : "Référence à l'organisation Tâche"
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
                  "valueString" : "Verwijzing naar de organisatie Taak"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Reference to the organization Task",
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
                  "valueString" : "Référence à l'organisation Tâche"
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
                  "valueString" : "Verwijzing naar de organisatie Taak"
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
            "code" : "Reference",
            "targetProfile" : [
              "http://example.org/StructureDefinition/BeModelOrganisationClaim"
            ]
          }
        ]
      },
      {
        "id" : "BeModelAssignment.performer",
        "path" : "BeModelAssignment.performer",
        "short" : "Information about the intended performer of the task",
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
                  "valueString" : "Informations sur l'exécutant prévu de la tâche"
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
                  "valueString" : "Informatie over de beoogde uitvoerder van de taak"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Information about the intended performer of the task",
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
                  "valueString" : "Informations sur l'exécutant prévu de la tâche"
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
                  "valueString" : "Informatie over de beoogde uitvoerder van de taak"
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
            "code" : "BackboneElement"
          }
        ]
      },
      {
        "id" : "BeModelAssignment.performer.role",
        "path" : "BeModelAssignment.performer.role",
        "short" : "Role of the provider assigned to provide the requested service",
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
                  "valueString" : "Rôle du prestataire chargé de fournir le service demandé"
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
                  "valueString" : "Rol van de dienstverlener die is toegewezen om de gevraagde dienst te verlenen"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Role of the provider assigned to provide the requested service",
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
                  "valueString" : "Rôle du prestataire chargé de fournir le service demandé"
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
                  "valueString" : "Rol van de dienstverlener die is toegewezen om de gevraagde dienst te verlenen"
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
        "id" : "BeModelAssignment.performer.actor",
        "path" : "BeModelAssignment.performer.actor",
        "short" : "NISS of the provider assigned to provide the requested service",
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
                  "valueString" : "NISS du prestataire chargé de fournir le service demandé"
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
                  "valueString" : "NISS van de dienstverlener die is toegewezen om de gevraagde dienst te verlenen"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "NISS of the provider assigned to provide the requested service",
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
                  "valueString" : "NISS du prestataire chargé de fournir le service demandé"
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
                  "valueString" : "NISS van de dienstverlener die is toegewezen om de gevraagde dienst te verlenen"
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
        "id" : "BeModelAssignment.performer.organisation",
        "path" : "BeModelAssignment.performer.organisation",
        "short" : "Organization assigned to provide the requested service (e.g. WGK, ...). In this case, it is the organization that is responsible for assigning the correct provider",
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
                  "valueString" : "Organisation chargée de fournir le service demandé (par exemple, WGK, ...). Dans ce cas, c'est l'organisation qui est responsable de l'attribution du bon fournisseur."
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
                  "valueString" : "Organisatie die is aangewezen om de gevraagde dienst te verlenen (bijv. WGK, ...). In dit geval is de organisatie verantwoordelijk voor het toewijzen van de juiste provider."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Organization assigned to provide the requested service (e.g. WGK, ...). In this case, it is the organization that is responsible for assigning the correct provider",
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
                  "valueString" : "Organisation chargée de fournir le service demandé (par exemple, WGK, ...). Dans ce cas, c'est l'organisation qui est responsable de l'attribution du bon fournisseur."
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
                  "valueString" : "Organisatie die is aangewezen om de gevraagde dienst te verlenen (bijv. WGK, ...). In dit geval is de organisatie verantwoordelijk voor het toewijzen van de juiste provider."
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
        "id" : "BeModelAssignment.performer.startdate",
        "path" : "BeModelAssignment.performer.startdate",
        "short" : "Start date of the prescription execution (encoded by the healthcare provider who performs the treatment)",
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
                  "valueString" : "Date de début de l'exécution de la prescription (encodée par le prestataire de soins de santé qui exécute le traitement)"
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
                  "valueString" : "Begindatum van de uitvoering van het recept (gecodeerd door de zorgverlener die de behandeling uitvoert)"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Start date of the prescription execution (encoded by the healthcare provider who performs the treatment)",
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
                  "valueString" : "Date de début de l'exécution de la prescription (encodée par le prestataire de soins de santé qui exécute le traitement)"
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
                  "valueString" : "Begindatum van de uitvoering van het recept (gecodeerd door de zorgverlener die de behandeling uitvoert)"
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
            "code" : "dateTime"
          }
        ]
      },
      {
        "id" : "BeModelAssignment.performer.endDate",
        "path" : "BeModelAssignment.performer.endDate",
        "short" : "End date of the prescription execution (encoded by the healthcare provider who performs the treatment)",
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
                  "valueString" : "Date de fin de l'exécution de la prescription (encodée par le prestataire de soins de santé qui exécute le traitement)"
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
                  "valueString" : "Einddatum van de uitvoering van het recept (gecodeerd door de zorgverlener die de behandeling uitvoert)"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "End date of the prescription execution (encoded by the healthcare provider who performs the treatment)",
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
                  "valueString" : "Date de fin de l'exécution de la prescription (encodée par le prestataire de soins de santé qui exécute le traitement)"
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
                  "valueString" : "Einddatum van de uitvoering van het recept (gecodeerd door de zorgverlener die de behandeling uitvoert)"
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
            "code" : "dateTime"
          }
        ]
      }
    ]
  }
}

```
