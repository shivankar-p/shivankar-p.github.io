{
    "schema": {
        "type": "https://w3c-ccg.github.io/vc-json-schemas/",
        "id": "did:schema:f1461939-557b-46d3-8900-8445fb7fa45d",
        "version": "1.0.0",
        "name": "Proof of Academic Evaluation Credential",
        "author": "did:rcw:6b9d7b31-bc7f-454a-be30-b6c7447b1cff",
        "authored": "2022-12-19T09:22:23.064Z",
        "schema": {
            "$id": "Proof-of-Academic-Evaluation-Credential-1.0",
            "$schema": "https://json-schema.org/draft/2019-09/schema",
            "description": "The holder has secured the <PERCENTAGE/GRADE> in <PROGRAMME> from <ABC_Institute>.",
            "type": "object",
            "properties": {
                "grade": {
                    "type": "string",
                    "description": "Grade (%age, GPA, etc.) secured by the holder."
                },
                "programme": {
                    "type": "string",
                    "description": "Name of the programme pursed by the holder."
                },
                "certifyingInstitute": {
                    "type": "string",
                    "description": "Name of the instute which certified the said grade in the said skill"
                },
                "evaluatingInstitute": {
                    "type": "string",
                    "description": "Name of the institute which ran the programme and evaluated the holder."
                }
            },
            "required": [
                "grade",
                "programme",
                "certifyingInstitute",
                "evaluatingInstitute"
            ],
            "additionalProperties": true
        }
    },
    "tags": [
        "tag1",
        "tag2"
    ],
    "status": "DRAFT",
    "createdAt": "2024-11-07T05:07:49.927Z",
    "updatedAt": "2024-11-07T05:07:49.927Z",
    "deletedAt": null,
    "createdBy": null,
    "updatedBy": null
}
