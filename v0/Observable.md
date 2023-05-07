# Observable

### Observable added

```json
{
    "_id": "~40988832",
    "_type": "audit",
    "base": true,
    "context": {
        "_id": "~12336",
        "_type": "case_artifact",
        "case": {
            "_id": "~40976512",
            "_type": "case",
            "caseId": 3,
            "createdAt": 1683314327257,
            "createdBy": "user@thehive.local",
            "customFieldValues": {},
            "customFields": {},
            "description": "Test 3",
            "endDate": null,
            "extendedStatus": "New",
            "flag": false,
            "id": "~40976512",
            "impactStatus": null,
            "owner": "user@thehive.local",
            "pap": 2,
            "permissions": [],
            "resolutionStatus": null,
            "severity": 2,
            "stage": "New",
            "startDate": 1683314322379,
            "stats": {},
            "status": "Open",
            "summary": null,
            "tags": [],
            "title": "Test 3",
            "tlp": 2,
            "updatedAt": 1683315002806,
            "updatedBy": "user@thehive.local"
        },
        "createdAt": 1683315002778,
        "createdBy": "user@thehive.local",
        "data": "1.1.1.1",
        "dataType": "domain",
        "id": "~12336",
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "This is the description",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683315002778,
        "stats": {},
        "tags": [
            "a-sample-tag"
        ],
        "tlp": 2
    },
    "createdAt": 1683315002815,
    "createdBy": "user@thehive.local",
    "details": {
        "_createdAt": 1683315002778,
        "_createdBy": "user@thehive.local",
        "_id": "~12336",
        "_type": "Observable",
        "data": "1.1.1.1",
        "dataType": "domain",
        "extraData": {},
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "This is the description",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683315002778,
        "tags": [
            "a-sample-tag"
        ],
        "tlp": 2
    },
    "id": "~40988832",
    "object": {
        "_id": "~12336",
        "_type": "case_artifact",
        "case": {
            "_id": "~40976512",
            "_type": "case",
            "caseId": 3,
            "createdAt": 1683314327257,
            "createdBy": "user@thehive.local",
            "customFieldValues": {},
            "customFields": {},
            "description": "Test 3",
            "endDate": null,
            "extendedStatus": "New",
            "flag": false,
            "id": "~40976512",
            "impactStatus": null,
            "owner": "user@thehive.local",
            "pap": 2,
            "permissions": [],
            "resolutionStatus": null,
            "severity": 2,
            "stage": "New",
            "startDate": 1683314322379,
            "stats": {},
            "status": "Open",
            "summary": null,
            "tags": [],
            "title": "Test 3",
            "tlp": 2,
            "updatedAt": 1683315002806,
            "updatedBy": "user@thehive.local"
        },
        "createdAt": 1683315002778,
        "createdBy": "user@thehive.local",
        "data": "1.1.1.1",
        "dataType": "domain",
        "id": "~12336",
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "This is the description",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683315002778,
        "stats": {},
        "tags": [
            "a-sample-tag"
        ],
        "tlp": 2
    },
    "objectId": "~12336",
    "objectType": "case_artifact",
    "operation": "Creation",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:346",
    "rootId": "~40976512",
    "startDate": 1683315003836
}
```

---

### Add Tag to an Observable

```json
{
    "_id": "~40980528",
    "_type": "audit",
    "base": true,
    "context": {
        "_id": "~12336",
        "_type": "case_artifact",
        "case": {
            "_id": "~40976512",
            "_type": "case",
            "caseId": 3,
            "createdAt": 1683314327257,
            "createdBy": "user@thehive.local",
            "customFieldValues": {},
            "customFields": {},
            "description": "A totally new description",
            "endDate": null,
            "extendedStatus": "InProgress",
            "flag": false,
            "id": "~40976512",
            "impactStatus": null,
            "owner": "user@thehive.local",
            "pap": 2,
            "permissions": [],
            "resolutionStatus": null,
            "severity": 2,
            "stage": "InProgress",
            "startDate": 1683314322379,
            "stats": {},
            "status": "Open",
            "summary": null,
            "tags": [
                "first-tag",
                "second-tag"
            ],
            "title": "Test 3",
            "tlp": 2,
            "updatedAt": 1683360607307,
            "updatedBy": "user@thehive.local"
        },
        "createdAt": 1683315002778,
        "createdBy": "user@thehive.local",
        "data": "1.1.1.1",
        "dataType": "domain",
        "id": "~12336",
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "This is the description",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683315002778,
        "stats": {},
        "tags": [
            "a-sample-tag",
            "new-tag"
        ],
        "tlp": 2,
        "updatedAt": 1683360607316,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683360607326,
    "createdBy": "user@thehive.local",
    "details": {
        "tags": [
            "a-sample-tag",
            "new-tag"
        ]
    },
    "id": "~40980528",
    "object": {
        "_id": "~12336",
        "_type": "case_artifact",
        "case": {
            "_id": "~40976512",
            "_type": "case",
            "caseId": 3,
            "createdAt": 1683314327257,
            "createdBy": "user@thehive.local",
            "customFieldValues": {},
            "customFields": {},
            "description": "A totally new description",
            "endDate": null,
            "extendedStatus": "InProgress",
            "flag": false,
            "id": "~40976512",
            "impactStatus": null,
            "owner": "user@thehive.local",
            "pap": 2,
            "permissions": [],
            "resolutionStatus": null,
            "severity": 2,
            "stage": "InProgress",
            "startDate": 1683314322379,
            "stats": {},
            "status": "Open",
            "summary": null,
            "tags": [
                "first-tag",
                "second-tag"
            ],
            "title": "Test 3",
            "tlp": 2,
            "updatedAt": 1683360607307,
            "updatedBy": "user@thehive.local"
        },
        "createdAt": 1683315002778,
        "createdBy": "user@thehive.local",
        "data": "1.1.1.1",
        "dataType": "domain",
        "id": "~12336",
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "This is the description",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683315002778,
        "stats": {},
        "tags": [
            "a-sample-tag",
            "new-tag"
        ],
        "tlp": 2,
        "updatedAt": 1683360607316,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~12336",
    "objectType": "case_artifact",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:537",
    "rootId": "~40976512",
    "startDate": 1683360607688
}
```

---

### Observable deleted

```json
{
    "_id": "~81940656",
    "_type": "audit",
    "base": true,
    "context": {
        "_id": "~40976560",
        "_type": "Share"
    },
    "createdAt": 1683360734678,
    "createdBy": "user@thehive.local",
    "details": {
        "data": "1.1.1.1",
        "dataType": "domain"
    },
    "id": "~81940656",
    "objectId": "~12336",
    "objectType": "case_artifact",
    "operation": "Delete",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:546",
    "rootId": "~40976512",
    "startDate": 1683360735682
}
```
