# ModelAnnex81 - CareSets - data models v0.1.0

## Logisch model: ModelAnnex81 

 
Logical model describing the model for the Annex81 proposal and approval 

**Usages:**

* This Logical Model is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/hl7.be.fhir.models|current/StructureDefinition/BeModelAnnex81)

### Formele weergaven van de profielinhoud

 [Beschrijving van profielen, differentials, snapshots en hun representaties](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

*  [Differentieletabel](#tabs-diff) 
*  [Momentopnametabel](#tabs-snap) 
*  [Statistieken/Referenties](#tabs-summ) 
*  [Alles](#tabs-all) 

Deze structuur is afgeleid van [Base](http://build.fhir.org/types.html#Base) 

Deze structuur is afgeleid van [Base](http://build.fhir.org/types.html#Base) 

**Samenvatting**

Vereist: 0 element(11 genest vereist elements)

 **Differentieelweergave** 

Deze structuur is afgeleid van [Base](http://build.fhir.org/types.html#Base) 

 **MomentopnameweergaveView** 

Deze structuur is afgeleid van [Base](http://build.fhir.org/types.html#Base) 

**Samenvatting**

Vereist: 0 element(11 genest vereist elements)

 

Andere representaties van het profiel: [CSV](../StructureDefinition-BeModelAnnex81.csv), [Excel](../StructureDefinition-BeModelAnnex81.xlsx) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "BeModelAnnex81",
  "language" : "en",
  "extension" : [
    {
      "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-type-characteristics",
      "valueCode" : "can-be-target"
    }
  ],
  "url" : "http://example.org/StructureDefinition/BeModelAnnex81",
  "version" : "0.1.0",
  "name" : "BeModelAnnex81",
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
  "description" : "Logical model describing the model for the Annex81 proposal and approval",
  "fhirVersion" : "4.0.1",
  "kind" : "logical",
  "abstract" : false,
  "type" : "http://example.org/StructureDefinition/BeModelAnnex81",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Base",
  "derivation" : "specialization",
  "differential" : {
    "element" : [
      {
        "id" : "BeModelAnnex81",
        "path" : "BeModelAnnex81",
        "short" : "BeModelAnnex81",
        "definition" : "Logical model describing the model for the Annex81 proposal and approval",
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
                  "valueString" : "Modèle logique décrivant le modèle de proposition et d'approbation de l'annexe 81"
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
                  "valueString" : "Logisch model dat het model voor het voorstel en de goedkeuring van bijlage81 beschrijft"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        }
      },
      {
        "id" : "BeModelAnnex81.identifier",
        "path" : "BeModelAnnex81.identifier",
        "short" : "Business identifier of the Annex81 proposal / approval",
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
                  "valueString" : "Identifiant commercial de la proposition / de l'approbation de l'annexe81"
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
                  "valueString" : "Bedrijfsidentificatiecode van het voorstel / de goedkeuring in bijlage81"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Business identifier of the Annex81 proposal / approval",
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
                  "valueString" : "Identifiant commercial de la proposition / de l'approbation de l'annexe81"
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
                  "valueString" : "Bedrijfsidentificatiecode van het voorstel / de goedkeuring in bijlage81"
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
        "id" : "BeModelAnnex81.shortCode",
        "path" : "BeModelAnnex81.shortCode",
        "short" : "Business short identifier allowing the healthcare professional to find a prescription associated with a patient",
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
                  "valueString" : "Identifiant commercial court permettant au professionnel de la santé de retrouver une ordonnance associée à un patient"
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
                  "valueString" : "Korte bedrijfsidentificatie waarmee de zorgverlener een recept kan vinden dat gekoppeld is aan een patiënt"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "'Business' code allowing the healthcare professional to find a prescription associated with a patient",
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
                  "valueString" : "Code \"entreprise\" permettant au professionnel de la santé de trouver une prescription associée à un patient"
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
                  "valueString" : "Bedrijfscode waarmee de zorgverlener een recept kan vinden dat aan een patiënt is gekoppeld"
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
        "id" : "BeModelAnnex81.recordedDate",
        "path" : "BeModelAnnex81.recordedDate",
        "short" : "Date of encoding of the information by the Recorder.",
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
                  "valueString" : "Date d'encodage de l'information par l'enregistreur."
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
                  "valueString" : "Datum van het coderen van de informatie door de Recorder."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Date of encoding of the information by the Recorder.",
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
                  "valueString" : "Date d'encodage de l'information par l'enregistreur."
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
                  "valueString" : "Datum van het coderen van de informatie door de Recorder."
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
        "id" : "BeModelAnnex81.creationDate",
        "path" : "BeModelAnnex81.creationDate",
        "short" : "Creation date of the referral prescription. This date will not change throughout the process. This date corresponds to the first recordedDate recorded for this referral prescription.",
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
                  "valueString" : "Date de création de la prescription de référence. Cette date ne changera pas au cours du processus. Cette date correspond à la première date enregistrée pour cette prescription de référence."
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
                  "valueString" : "Aanmaakdatum van het verwijzingsrecept. Deze datum verandert niet tijdens het proces. Deze datum komt overeen met de eerste geregistreerdeDatum voor dit verwijzingsvoorschrift."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Creation date of the referral prescription. This date will not change throughout the process. This date corresponds to the first recordedDate recorded for this referral prescription.",
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
                  "valueString" : "Date de création de la prescription de référence. Cette date ne changera pas au cours du processus. Cette date correspond à la première date enregistrée pour cette prescription de référence."
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
                  "valueString" : "Aanmaakdatum van het verwijzingsrecept. Deze datum verandert niet tijdens het proces. Deze datum komt overeen met de eerste geregistreerdeDatum voor dit verwijzingsvoorschrift."
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
        "id" : "BeModelAnnex81.author",
        "path" : "BeModelAnnex81.author",
        "short" : "The person who encodes the prescription (e.g. a doctor, nurse, midwife or dentist) and takes responsibility for their content. The unique identifier must be the National Register Number (NISS) or bis number.",
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
                  "valueString" : "La personne qui encode la prescription (par exemple, un médecin, une infirmière, une sage-femme ou un dentiste) et qui assume la responsabilité de son contenu. L'identifiant unique doit être le numéro de registre national (NISS) ou le numéro bis."
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
                  "valueString" : "De persoon die het recept codeert (bijv. een arts, verpleegkundige, verloskundige of tandarts) en de verantwoordelijkheid neemt voor de inhoud ervan. De unieke identificatiecode moet het Nationaal Register Nummer (NISS) of bisnummer zijn."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Is the unique identifier of the person who encodes the prescription (e.g. a doctor, nurse, midwife or dentist) and takes responsibility for their content. The unique identifier must be the National Register Number (NISS) or bis number.",
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
                  "valueString" : "Il s'agit de l'identifiant unique de la personne qui code la prescription (par exemple, un médecin, une infirmière, une sage-femme ou un dentiste) et qui est responsable de son contenu. L'identifiant unique doit être le numéro de registre national (NISS) ou le numéro bis."
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
                  "valueString" : "Is de unieke identificatiecode van de persoon die het recept codeert (bijv. een arts, verpleegkundige, verloskundige of tandarts) en die verantwoordelijk is voor de inhoud ervan. De unieke identificatiecode moet het Nationaal Register Nummer (NISS) of bisnummer zijn."
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
        "id" : "BeModelAnnex81.status",
        "path" : "BeModelAnnex81.status",
        "short" : "Is the status of the referral prescription (e.g. planned, complete, stopped, suspended, in progress, ….)",
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
                  "valueString" : "Le statut de la prescription d'orientation (par exemple, prévu, complet, arrêté, suspendu, en cours, ....)."
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
                  "valueString" : "Is de status van het verwijzingsvoorschrift (bijv. gepland, voltooid, gestopt, opgeschort, in behandeling, ....)?"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Is the status of the referral prescription (e.g. planned, complete, stopped, suspended, in progress, ….)",
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
                  "valueString" : "Le statut de la prescription d'orientation (par exemple, prévu, complet, arrêté, suspendu, en cours, ....)."
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
                  "valueString" : "Is de status van het verwijzingsvoorschrift (bijv. gepland, voltooid, gestopt, opgeschort, in behandeling, ....)?"
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
        "id" : "BeModelAnnex81.statusReason",
        "path" : "BeModelAnnex81.statusReason",
        "short" : "Gives the reason for the status of the referral prescription (treatment has been changed, patient is allergic, patient refuses, …)",
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
                  "valueString" : "Indique la raison du statut de la prescription de référence (le traitement a été modifié, le patient est allergique, le patient refuse, ...)."
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
                  "valueString" : "Geeft de reden voor de status van het verwijzingsvoorschrift (behandeling is gewijzigd, patiënt is allergisch, patiënt weigert, ...)"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Gives the reason for the status of the referral prescription (treatment has been changed, patient is allergic, patient refuses, …)",
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
                  "valueString" : "Indique la raison du statut de la prescription de référence (le traitement a été modifié, le patient est allergique, le patient refuse, ...)."
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
                  "valueString" : "Geeft de reden voor de status van het verwijzingsvoorschrift (behandeling is gewijzigd, patiënt is allergisch, patiënt weigert, ...)"
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
        "id" : "BeModelAnnex81.careRequested",
        "path" : "BeModelAnnex81.careRequested",
        "short" : "Type of care requested (list of acts that each profession can do (not nomenclature code)) (snomed-ct code (procedure))",
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
                  "valueString" : "Type de soins demandés (liste des actes que chaque profession peut effectuer (pas de code de nomenclature)) (code snomed-ct (procédure))"
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
                  "valueString" : "Gevraagde zorg (lijst van handelingen die elk beroep kan uitvoeren (geen nomenclatuurcode)) (snomed-ct code (procedure))"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Type of care requested (list of acts that each profession can do (not nomenclature code)) (snomed-ct code (procedure))",
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
                  "valueString" : "Type de soins demandés (liste des actes que chaque profession peut faire (pas de code de nomenclature)) (code snomed-ct (procédure))"
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
                  "valueString" : "Gevraagde zorg (lijst van handelingen die elk beroep kan uitvoeren (geen nomenclatuurcode)) (snomed-ct code (procedure))"
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
        "id" : "BeModelAnnex81.patient",
        "path" : "BeModelAnnex81.patient",
        "short" : "The patient's identification. The unique identifier must be the National Patient Registry Number (NISS) or the patient bis",
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
                  "valueString" : "L'identification du patient. L'identifiant unique doit être le numéro du registre national des patients (NISS) ou le numéro bis du patient."
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
                  "valueString" : "De identificatie van de patiënt. De unieke identificatie moet het Nationale Patiëntenregistratienummer (NISS) of de patiënt bis zijn."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Is the patient's unique identifier. The unique identifier must be the National Patient Registry Number (NISS) or the patient bis",
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
                  "valueString" : "Est l'identifiant unique du patient. L'identifiant unique doit être le numéro du registre national des patients (NISS) ou le numéro bis du patient."
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
                  "valueString" : "Is de unieke identificatiecode van de patiënt. De unieke identificatiecode moet het National Patient Registry Number (NISS) of de patiënt bis zijn."
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
        "id" : "BeModelAnnex81.originRequestId",
        "path" : "BeModelAnnex81.originRequestId",
        "short" : "Reference to the original prescription on which the prescription is based (prescriptionId), care plan, follow-up path, ….  referenceId. Reference to the CarePlan that addresses this prescription.",
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
                  "valueString" : "Référence à la prescription originale sur laquelle la prescription est basée (prescriptionId), au plan de soins, au chemin de suivi, .... referenceId. Référence au plan de soins qui concerne cette prescription."
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
                  "valueString" : "Verwijzing naar het originele voorschrift waarop het voorschrift is gebaseerd (voorschriftId), zorgplan, vervolgpad, .... verwijzingId. Verwijzing naar het Zorgplan dat betrekking heeft op dit voorschrift."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Reference to the original prescription on which the prescription is based (prescriptionId), care plan, follow-up path, ….  referenceId. Reference to the CarePlan that addresses this prescription.",
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
                  "valueString" : "Référence à la prescription originale sur laquelle la prescription est basée (prescriptionId), au plan de soins, au chemin de suivi, .... referenceId. Référence au plan de soins qui concerne cette prescription."
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
                  "valueString" : "Verwijzing naar het originele voorschrift waarop het voorschrift is gebaseerd (voorschriftId), zorgplan, vervolgpad, .... verwijzingId. Verwijzing naar het Zorgplan dat betrekking heeft op dit voorschrift."
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
        "id" : "BeModelAnnex81.validationStartDate",
        "path" : "BeModelAnnex81.validationStartDate",
        "short" : "Start date of the prescription validity (encoded by the prescriber).",
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
                  "valueString" : "Date de début de validité de la prescription (encodée par le prescripteur)."
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
                  "valueString" : "Begindatum van de geldigheid van het recept (gecodeerd door de voorschrijver)."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Start date of the prescription validity (encoded by the prescriber).",
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
                  "valueString" : "Date de début de validité de la prescription (encodée par le prescripteur)."
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
                  "valueString" : "Begindatum van de geldigheid van het recept (gecodeerd door de voorschrijver)."
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
        "id" : "BeModelAnnex81.validationEndDate",
        "path" : "BeModelAnnex81.validationEndDate",
        "short" : "End date of the prescription validity (encoded by the prescriber)",
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
                  "valueString" : "Date de fin de validité de la prescription (encodée par le prescripteur)"
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
                  "valueString" : "Einddatum van de geldigheid van het recept (gecodeerd door de voorschrijver)"
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "End date of the prescription validity (encoded by the prescriber)",
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
                  "valueString" : "Date de fin de validité de la prescription (encodée par le prescripteur)"
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
                  "valueString" : "Einddatum van de geldigheid van het recept (gecodeerd door de voorschrijver)"
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
        "id" : "BeModelAnnex81.problem",
        "path" : "BeModelAnnex81.problem",
        "short" : "Reason for the request. The problem (code or reference) that is the main reason for this prescription (example: problem justifying the patient's inability to manage his medications).",
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
                  "valueString" : "Motif de la demande. Le problème (code ou référence) qui est la raison principale de cette prescription (exemple : problème justifiant l'incapacité du patient à gérer ses médicaments)."
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
                  "valueString" : "Reden voor het verzoek. Het probleem (code of referentie) dat de belangrijkste reden is voor dit voorschrift (voorbeeld: probleem dat het onvermogen van de patiënt rechtvaardigt om zijn medicijnen te beheren)."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Reason for the request. The problem (code or reference) that is the main reason for this prescription (example: problem justifying the patient's inability to manage his medications).",
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
                  "valueString" : "Motif de la demande. Le problème (code ou référence) qui est la raison principale de cette prescription (exemple : problème justifiant l'incapacité du patient à gérer ses médicaments)."
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
                  "valueString" : "Reden voor het verzoek. Het probleem (code of referentie) dat de belangrijkste reden is voor dit voorschrift (voorbeeld: probleem dat het onvermogen van de patiënt rechtvaardigt om zijn medicijnen te beheren)."
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
        "id" : "BeModelAnnex81.feedbackNeeded",
        "path" : "BeModelAnnex81.feedbackNeeded",
        "short" : "Boolean - true if the prescriber requests feedback. If he wants to add other care providers, this will be mentioned in free text in the note. Here by default \"True\"",
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
                  "valueString" : "Booléen - vrai si le prescripteur demande un retour d'information. S'il souhaite ajouter d'autres prestataires de soins, cela sera mentionné en texte libre dans la note. La valeur par défaut est \"True\""
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
                  "valueString" : "Booleaans - waar als de voorschrijver feedback vraagt. Als hij andere zorgverleners wil toevoegen, wordt dit in vrije tekst vermeld in de notitie. Hier standaard \"Waar\"."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Boolean – true if the prescriber requests feedback. If he wants to add other care providers, this will be mentioned in free text in the note. Here by default \"True\"",
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
                  "valueString" : "Booléen - vrai si le prescripteur demande un retour d'information. S'il souhaite ajouter d'autres prestataires de soins, cela sera mentionné en texte libre dans la note. La valeur par défaut est \"True\""
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
                  "valueString" : "Booleaans - waar als de voorschrijver feedback vraagt. Als hij andere zorgverleners wil toevoegen, wordt dit in vrije tekst vermeld in de notitie. Hier standaard \"Waar\"."
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
            "code" : "boolean"
          }
        ]
      }
    ]
  }
}

```
