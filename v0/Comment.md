# Comment

### Comment added to a Case

```json
{
    "_id": "~24728",
    "_type": "audit",
    "base": true,
    "context": {
        "_id": "~40976512",
        "_type": "case",
        "caseId": 3,
        "createdAt": 1683314327257,
        "createdBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": {},
        "description": "Test 3",
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
        "updatedAt": 1683357200975,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683357200987,
    "createdBy": "user@thehive.local",
    "details": {
        "author": "user@thehive.local"
    },
    "id": "~24728",
    "object": {
        "alert": null,
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
            "updatedAt": 1683357200975,
            "updatedBy": "user@thehive.local"
        },
        "message": "Test"
    },
    "objectId": "~20632",
    "objectType": "comment",
    "operation": "Creation",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:197",
    "rootId": "~40976512",
    "startDate": 1683357201281
}
```

---

### Comment on a Case edited

```json
{
    "_id": "~20520",
    "_type": "audit",
    "base": true,
    "context": {
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
        "updatedAt": 1683360331742,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683360331755,
    "createdBy": "user@thehive.local",
    "details": {
        "author": "user@thehive.local"
    },
    "id": "~20520",
    "object": {
        "alert": null,
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
            "updatedAt": 1683360331742,
            "updatedBy": "user@thehive.local"
        },
        "message": "Test; EDITED"
    },
    "objectId": "~20632",
    "objectType": "comment",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:490",
    "rootId": "~40976512",
    "startDate": 1683360332507
}
```

---

### Comment on a Case deleted

```json
{
    "_id": "~40984816",
    "_type": "audit",
    "base": true,
    "context": {
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
        "updatedAt": 1683360449454,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683360449470,
    "createdBy": "user@thehive.local",
    "details": {},
    "id": "~40984816",
    "objectId": "~20632",
    "objectType": "comment",
    "operation": "Delete",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:496",
    "rootId": "~40976512",
    "startDate": 1683360450531
}
```
