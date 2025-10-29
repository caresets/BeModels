# BeModelNursingPrescription - CareSets - data models v0.1.0

## : BeModelNursingPrescription 

 
Data model for the nursing prescription referral. 

**Usages:**

* This Logical Model is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/hl7.be.fhir.models|current/StructureDefinition/BeModelNursingPrescription)

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
  "id" : "BeModelNursingPrescription",
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
  "url" : "http://example.org/StructureDefinition/BeModelNursingPrescription",
  "version" : "0.1.0",
  "name" : "BeModelNursingPrescription",
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
  "description" : "Data model for the nursing prescription referral.",
  "fhirVersion" : "4.0.1",
  "kind" : "logical",
  "abstract" : false,
  "type" : "http://example.org/StructureDefinition/BeModelNursingPrescription",
  "baseDefinition" : "http://example.org/StructureDefinition/BeModelReferralPrescription",
  "derivation" : "specialization",
  "differential" : {
    "element" : [
      {
        "id" : "BeModelNursingPrescription",
        "path" : "BeModelNursingPrescription",
        "short" : "BeModelNursingPrescription",
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
        "id" : "BeModelNursingPrescription.feedbackNeeded",
        "path" : "BeModelNursingPrescription.feedbackNeeded",
        "short" : "Follow-up indicator (boolean) specifying whether a feedback is expected from the doctor on this treatment.",
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
                  "valueString" : "Indicateur de suivi (booléen) précisant si un retour d'information est attendu de la part du médecin sur ce traitement."
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
                  "valueString" : "Vervolgindicator (booleaans) die aangeeft of er een terugkoppeling wordt verwacht van de arts over deze behandeling."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Follow-up indicator (boolean) specifying whether a feedback is expected from the doctor on this treatment.",
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
                  "valueString" : "Indicateur de suivi (booléen) précisant si un retour d'information est attendu de la part du médecin sur ce traitement."
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
                  "valueString" : "Vervolgindicator (booleaans) die aangeeft of er een terugkoppeling wordt verwacht van de arts over deze behandeling."
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
      },
      {
        "id" : "BeModelNursingPrescription.generalRemarks",
        "path" : "BeModelNursingPrescription.generalRemarks",
        "short" : "General remarks concerning the treatment or request.",
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
                  "valueString" : "Remarques générales concernant le traitement ou la demande."
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
                  "valueString" : "Algemene opmerkingen over de behandeling of het verzoek."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "General remarks concerning the treatment or request.",
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
                  "valueString" : "Remarques générales concernant le traitement ou la demande."
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
                  "valueString" : "Algemene opmerkingen over de behandeling of het verzoek."
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
      },
      {
        "id" : "BeModelNursingPrescription.contraIndications",
        "path" : "BeModelNursingPrescription.contraIndications",
        "short" : "Medical contraindications (e.g. 'Latex allergy'). 103306004 : 'Contraindication to (x)\"",
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
                  "valueString" : "Contre-indications médicales (par exemple, \"allergie au latex\"). 103306004 : \"Contre-indication à (x)\""
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
                  "valueString" : "Medische contra-indicaties (bijv. 'Latexallergie'). 103306004 : \"Contra-indicatie voor (x)\"."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Medical contraindications (e.g. 'Latex allergy'). 103306004 : 'Contraindication to (x)'",
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
                  "valueString" : "Contre-indications médicales (par exemple, \"allergie au latex\"). 103306004 : 'Contre-indication à (x)'"
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
                  "valueString" : "Medische contra-indicaties (bijv. 'Latexallergie'). 103306004 : 'Contra-indicatie voor (x)'."
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
        "id" : "BeModelNursingPrescription.medicalReason",
        "path" : "BeModelNursingPrescription.medicalReason",
        "short" : "Medical reasons for the prescription (e.g. 'Infected wound requiring follow-up'). 410666004 : \"Reason For (x)\"",
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
                  "valueString" : "Raisons médicales de la prescription (par exemple : \"Plaie infectée nécessitant un suivi\"). 410666004 : \"Raison pour (x)\""
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
                  "valueString" : "Medische redenen voor het voorschrift (bijv. 'Geïnfecteerde wond die follow-up vereist'). 410666004 : \"Reden voor (x)\"."
                }
              ],
              "url" : "http://hl7.org/fhir/StructureDefinition/translation"
            }
          ]
        },
        "definition" : "Medical reasons for the prescription (e.g. 'Infected wound requiring follow-up'). 410666004 : 'Reason For (x)'",
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
                  "valueString" : "Raisons médicales de la prescription (par exemple : \"Plaie infectée nécessitant un suivi\"). 410666004 : 'Raison pour (x)'"
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
                  "valueString" : "Medische redenen voor het voorschrift (bijv. 'Geïnfecteerde wond die follow-up vereist'). 410666004 : 'Reden voor (x)'."
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
      }
    ]
  }
}

```
