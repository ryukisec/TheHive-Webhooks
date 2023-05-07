# Case

### Case Created

```json
{
    "_id": "~12376",
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
        "updatedAt": null,
        "updatedBy": null
    },
    "createdAt": 1683314327296,
    "createdBy": "user@thehive.local",
    "details": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "assignee": "user@thehive.local",
        "customFields": {},
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "New",
        "startDate": 1683314322379,
        "status": "New",
        "tags": [],
        "timeToDetect": 0,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": [
            "manageCase/create",
            "manageAlert/update",
            "manageCaseTemplate",
            "manageProcedure",
            "managePage",
            "manageObservable",
            "manageCase/delete",
            "manageAlert/create",
            "manageAlert/delete",
            "accessTheHiveFS",
            "manageAction",
            "manageCase/update",
            "manageShare",
            "manageAnalyse",
            "manageFunction/invoke",
            "manageTask",
            "manageCase/merge",
            "manageCustomEvent",
            "manageAlert/import",
            "manageCase/changeOwnership",
            "manageUser",
            "manageComment",
            "manageTag",
            "manageConfig",
            "manageFunction/create",
            "manageKnowledgeBase"
        ]
    },
    "id": "~12376",
    "object": {
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
        "updatedAt": null,
        "updatedBy": null
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Creation",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:313",
    "rootId": "~40976512",
    "startDate": 1683314327579
}
```

```json
{
    "_id": "~40968192",
    "_type": "audit",
    "base": false,
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
        "updatedAt": null,
        "updatedBy": null
    },
    "createdAt": 1683314327291,
    "createdBy": "user@thehive.local",
    "details": {
        "share": {
            "organisation": "sample-org",
            "profile": "org-admin"
        }
    },
    "id": "~40968192",
    "object": {
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
        "updatedAt": null,
        "updatedBy": null
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:313",
    "rootId": "~40976512",
    "startDate": 1683314327872
}
```

---

### Status Changed

Status changed from `New` to `In Progress`

```json
{
    "_id": "~40980608",
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
        "tags": [],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683315315617,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683315315625,
    "createdBy": "user@thehive.local",
    "details": {
        "stage": "InProgress",
        "status": "InProgress"
    },
    "id": "~40980608",
    "object": {
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
        "tags": [],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683315315617,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3: 187ec6a2aad: -8000: 381",
    "rootId": "~40976512",
    "startDate": 1683315315897
}
```

---

### Tag added to a Case

```json
{
    "_id": "~8344",
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
            "new-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356171734,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683356171751,
    "createdBy": "user@thehive.local",
    "details": {
        "tags": [
            "new-tag"
        ]
    },
    "id": "~8344",
    "object": {
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
            "new-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356171734,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:92",
    "rootId": "~40976512",
    "startDate": 1683356172953
}
```

A second tag is added, but it seems impossible to determine what tag was first. 

```json
{
    "_id": "~16536",
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
        "updatedAt": 1683356440463,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683356440474,
    "createdBy": "user@thehive.local",
    "details": {
        "tags": [
            "first-tag",
            "second-tag"
        ]
    },
    "id": "~16536",
    "object": {
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
        "updatedAt": 1683356440463,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:114",
    "rootId": "~40976512",
    "startDate": 1683356441014
}
```

A third tag (`aaa`) was added

```json
{
    "_id": "~40972536",
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
            "second-tag",
            "aaa"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356541847,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683356541863,
    "createdBy": "user@thehive.local",
    "details": {
        "tags": [
            "first-tag",
            "second-tag",
            "aaa"
        ]
    },
    "id": "~40972536",
    "object": {
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
            "second-tag",
            "aaa"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356541847,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:121",
    "rootId": "~40976512",
    "startDate": 1683356543103
}
```

Adding multiple tags at once

```json
{
    "_id": "~40964336",
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
            "mult3",
            "mult2",
            "mult1",
            "aaa",
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356761056,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683356761744,
    "createdBy": "user@thehive.local",
    "details": {
        "tags": [
            "mult3",
            "mult2",
            "mult1",
            "aaa",
            "first-tag",
            "second-tag"
        ]
    },
    "id": "~40964336",
    "object": {
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
            "mult3",
            "mult2",
            "mult1",
            "aaa",
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356761056,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:168",
    "rootId": "~40976512",
    "startDate": 1683356762118
}
```

---

### Tag removed from a Case

One and only tag is removed

```json
{
    "_id": "~40964144",
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
        "tags": [],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356330762,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683356331455,
    "createdBy": "user@thehive.local",
    "details": {
        "tags": []
    },
    "id": "~40964144",
    "object": {
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
        "tags": [],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356330762,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:100",
    "rootId": "~40976512",
    "startDate": 1683356331861
}
```

One tag (`aaa`) is removed

```json
{
    "_id": "~8232",
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
            "mult3",
            "mult2",
            "mult1",
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356907338,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683356907349,
    "createdBy": "user@thehive.local",
    "details": {
        "tags": [
            "mult3",
            "mult2",
            "mult1",
            "first-tag",
            "second-tag"
        ]
    },
    "id": "~8232",
    "object": {
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
            "mult3",
            "mult2",
            "mult1",
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683356907338,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:178",
    "rootId": "~40976512",
    "startDate": 1683356908206
}
```

Multiple tags are removed

```json
{
    "_id": "~40968432",
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
        "updatedAt": 1683357060971,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683357060982,
    "createdBy": "user@thehive.local",
    "details": {
        "tags": [
            "first-tag",
            "second-tag"
        ]
    },
    "id": "~40968432",
    "object": {
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
        "updatedAt": 1683357060971,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:187",
    "rootId": "~40976512",
    "startDate": 1683357061233
}
```

---

### Description changed

```json
{
    "_id": "~81932464",
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
        "updatedAt": 1683358654975,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683358654984,
    "createdBy": "user@thehive.local",
    "details": {
        "description": "A totally new description"
    },
    "id": "~81932464",
    "object": {
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
        "updatedAt": 1683358654975,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:226",
    "rootId": "~40976512",
    "startDate": 1683358655835
}
```

---

### Case closed as Other

```json
{
    "_id": "~40988920",
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
        "endDate": 1683361345072,
        "extendedStatus": "Other",
        "flag": false,
        "id": "~40976512",
        "impactStatus": null,
        "owner": "user@thehive.local",
        "pap": 2,
        "permissions": [],
        "resolutionStatus": null,
        "severity": 2,
        "stage": "Closed",
        "startDate": 1683314322379,
        "stats": {},
        "status": "Resolved",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683361345100,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683361345108,
    "createdBy": "user@thehive.local",
    "details": {
        "endDate": 1683361345072,
        "stage": "Closed",
        "status": "Other",
        "summary": "Closed as Other"
    },
    "id": "~40988920",
    "object": {
        "_id": "~40976512",
        "_type": "case",
        "caseId": 3,
        "createdAt": 1683314327257,
        "createdBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": {},
        "description": "A totally new description",
        "endDate": 1683361345072,
        "extendedStatus": "Other",
        "flag": false,
        "id": "~40976512",
        "impactStatus": null,
        "owner": "user@thehive.local",
        "pap": 2,
        "permissions": [],
        "resolutionStatus": null,
        "severity": 2,
        "stage": "Closed",
        "startDate": 1683314322379,
        "stats": {},
        "status": "Resolved",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683361345100,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:638",
    "rootId": "~40976512",
    "startDate": 1683361345987
}
```

---

### Case reopened

```json
{
    "_id": "~40988912",
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
        "endDate": 1683361345072,
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
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683361471761,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683361471769,
    "createdBy": "user@thehive.local",
    "details": {
        "stage": "InProgress",
        "status": "InProgress"
    },
    "id": "~40988912",
    "object": {
        "_id": "~40976512",
        "_type": "case",
        "caseId": 3,
        "createdAt": 1683314327257,
        "createdBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": {},
        "description": "A totally new description",
        "endDate": 1683361345072,
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
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683361471761,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:647",
    "rootId": "~40976512",
    "startDate": 1683361472069
}

```

---

### Case closed as TruePositive with Impact

```json
{
    "_id": "~40993008",
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
        "endDate": 1683361544346,
        "extendedStatus": "TruePositive",
        "flag": false,
        "id": "~40976512",
        "impactStatus": "WithImpact",
        "owner": "user@thehive.local",
        "pap": 2,
        "permissions": [],
        "resolutionStatus": null,
        "severity": 2,
        "stage": "Closed",
        "startDate": 1683314322379,
        "stats": {},
        "status": "Resolved",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683361544372,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683361544379,
    "createdBy": "user@thehive.local",
    "details": {
        "endDate": 1683361544346,
        "impactStatus": "WithImpact",
        "stage": "Closed",
        "status": "TruePositive"
    },
    "id": "~40993008",
    "object": {
        "_id": "~40976512",
        "_type": "case",
        "caseId": 3,
        "createdAt": 1683314327257,
        "createdBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": {},
        "description": "A totally new description",
        "endDate": 1683361544346,
        "extendedStatus": "TruePositive",
        "flag": false,
        "id": "~40976512",
        "impactStatus": "WithImpact",
        "owner": "user@thehive.local",
        "pap": 2,
        "permissions": [],
        "resolutionStatus": null,
        "severity": 2,
        "stage": "Closed",
        "startDate": 1683314322379,
        "stats": {},
        "status": "Resolved",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "title": "Test 3",
        "tlp": 2,
        "updatedAt": 1683361544372,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:656",
    "rootId": "~40976512",
    "startDate": 1683361545084
}

```

---

### Case deleted

```json
{
    "_id": "~41005288",
    "_type": "audit",
    "base": true,
    "context": {
        "_id": "~40964176",
        "_type": "organisation",
        "createdAt": 1683223840663,
        "createdBy": "admin@thehive.local",
        "description": "sample-org",
        "id": "~40964176",
        "links": [],
        "locked": false,
        "name": "sample-org",
        "observableRule": "manual",
        "taskRule": "manual"
    },
    "createdAt": 1683378965075,
    "createdBy": "user@thehive.local",
    "details": {
        "number": 3,
        "title": "Test 3"
    },
    "id": "~41005288",
    "objectId": "~40976512",
    "objectType": "case",
    "operation": "Delete",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1450",
    "rootId": "~40964176",
    "startDate": 1683378966226
}
```

---

### Create a Case from an Alert with a Template

```json
{
    "_id": "~41013480",
    "_type": "audit",
    "base": true,
    "context": {
        "_id": "~81948848",
        "_type": "case",
        "caseId": 4,
        "createdAt": 1683379107590,
        "createdBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": {},
        "description": "Hello world",
        "endDate": null,
        "extendedStatus": "New",
        "flag": false,
        "id": "~81948848",
        "impactStatus": null,
        "owner": "user@thehive.local",
        "pap": 1,
        "permissions": [],
        "resolutionStatus": null,
        "severity": 1,
        "stage": "New",
        "startDate": 1683379107537,
        "stats": {},
        "status": "Open",
        "summary": null,
        "tags": [
            "one-tag"
        ],
        "title": "[Import in progress: 0%] TestAlert1",
        "tlp": 1,
        "updatedAt": null,
        "updatedBy": null
    },
    "createdAt": 1683379108025,
    "createdBy": "user@thehive.local",
    "details": {
        "_createdAt": 1683379107590,
        "_createdBy": "user@thehive.local",
        "_id": "~81948848",
        "_type": "Case",
        "alertDate": 1683379038000,
        "alertImportedDate": 1683379107539,
        "alertInProgressDate": 1683379107539,
        "alertNewDate": 1683379038953,
        "assignee": "user@thehive.local",
        "customFields": {},
        "description": "Hello world",
        "extraData": {},
        "flag": false,
        "fromAlert": {
            "_id": "~40997104",
            "source": "API",
            "sourceRef": "API_1",
            "title": "TestAlert1",
            "type": "API"
        },
        "newDate": 1683379107540,
        "number": 4,
        "pap": 1,
        "severity": 1,
        "stage": "New",
        "startDate": 1683379107537,
        "status": "New",
        "tags": [
            "one-tag"
        ],
        "timeToDetect": 0,
        "title": "TestAlert1",
        "tlp": 1,
        "userPermissions": [
            "manageCase/create",
            "manageAlert/update",
            "manageCaseTemplate",
            "manageProcedure",
            "managePage",
            "manageObservable",
            "manageCase/delete",
            "manageAlert/create",
            "manageAlert/delete",
            "accessTheHiveFS",
            "manageAction",
            "manageCase/update",
            "manageShare",
            "manageAnalyse",
            "manageFunction/invoke",
            "manageTask",
            "manageCase/merge",
            "manageCustomEvent",
            "manageAlert/import",
            "manageCase/changeOwnership",
            "manageUser",
            "manageComment",
            "manageTag",
            "manageConfig",
            "manageFunction/create",
            "manageKnowledgeBase"
        ]
    },
    "id": "~41013480",
    "object": {
        "_id": "~81948848",
        "_type": "case",
        "caseId": 4,
        "createdAt": 1683379107590,
        "createdBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": {},
        "description": "Hello world",
        "endDate": null,
        "extendedStatus": "New",
        "flag": false,
        "id": "~81948848",
        "impactStatus": null,
        "owner": "user@thehive.local",
        "pap": 1,
        "permissions": [],
        "resolutionStatus": null,
        "severity": 1,
        "stage": "New",
        "startDate": 1683379107537,
        "stats": {},
        "status": "Open",
        "summary": null,
        "tags": [
            "one-tag"
        ],
        "title": "[Import in progress: 0%] TestAlert1",
        "tlp": 1,
        "updatedAt": null,
        "updatedBy": null
    },
    "objectId": "~81948848",
    "objectType": "case",
    "operation": "Creation",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1471",
    "rootId": "~81948848",
    "startDate": 1683379108331
}
```

```json
{
    "_id": "~40984768",
    "_type": "audit",
    "base": false,
    "context": {
        "_id": "~81948848",
        "_type": "case",
        "caseId": 4,
        "createdAt": 1683379107590,
        "createdBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": {},
        "description": "Hello world",
        "endDate": null,
        "extendedStatus": "New",
        "flag": false,
        "id": "~81948848",
        "impactStatus": null,
        "owner": "user@thehive.local",
        "pap": 1,
        "permissions": [],
        "resolutionStatus": null,
        "severity": 1,
        "stage": "New",
        "startDate": 1683379107537,
        "stats": {},
        "status": "Open",
        "summary": null,
        "tags": [
            "one-tag"
        ],
        "title": "[Import in progress: 0%] TestAlert1",
        "tlp": 1,
        "updatedAt": null,
        "updatedBy": null
    },
    "createdAt": 1683379108022,
    "createdBy": "user@thehive.local",
    "details": {
        "caseId": "~81948848"
    },
    "id": "~40984768",
    "object": {
        "_id": "~40997104",
        "_type": "alert",
        "artifacts": [],
        "case": "~81948848",
        "caseTemplate": null,
        "createdAt": 1683379038961,
        "createdBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": {},
        "date": 1683379038000,
        "description": "Hello world",
        "externalLink": null,
        "follow": true,
        "id": "~40997104",
        "pap": 1,
        "severity": 1,
        "similarCases": [],
        "source": "API",
        "sourceRef": "API_1",
        "stage": "Imported",
        "status": "Imported",
        "tags": [],
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API",
        "updatedAt": 1683379108009,
        "updatedBy": "user@thehive.local"
    },
    "objectId": "~40997104",
    "objectType": "alert",
    "operation": "Update",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1471",
    "rootId": "~81948848",
    "startDate": 1683379108726
}
```

```json
{
    "_id": "~40992816",
    "_type": "audit",
    "base": true,
    "context": {
        "_id": "~41017576",
        "_type": "case_artifact",
        "case": {
            "_id": "~81948848",
            "_type": "case",
            "caseId": 4,
            "createdAt": 1683379107590,
            "createdBy": "user@thehive.local",
            "customFieldValues": {},
            "customFields": {},
            "description": "Hello world",
            "endDate": null,
            "extendedStatus": "New",
            "flag": false,
            "id": "~81948848",
            "impactStatus": null,
            "owner": "user@thehive.local",
            "pap": 1,
            "permissions": [],
            "resolutionStatus": null,
            "severity": 1,
            "stage": "New",
            "startDate": 1683379107537,
            "stats": {},
            "status": "Open",
            "summary": null,
            "tags": [
                "one-tag"
            ],
            "title": "TestAlert1",
            "tlp": 1,
            "updatedAt": null,
            "updatedBy": null
        },
        "createdAt": 1683379109195,
        "createdBy": "user@thehive.local",
        "data": "1.1.1.1",
        "dataType": "ip",
        "id": "~41017576",
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "maybe bad",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683379109195,
        "stats": {},
        "tags": [
            "destination-ip"
        ],
        "tlp": 0
    },
    "createdAt": 1683379109250,
    "createdBy": "user@thehive.local",
    "details": {
        "_createdAt": 1683379109195,
        "_createdBy": "user@thehive.local",
        "_id": "~41017576",
        "_type": "Observable",
        "data": "1.1.1.1",
        "dataType": "ip",
        "extraData": {},
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "maybe bad",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683379109195,
        "tags": [
            "destination-ip"
        ],
        "tlp": 0
    },
    "id": "~40992816",
    "object": {
        "_id": "~41017576",
        "_type": "case_artifact",
        "case": {
            "_id": "~81948848",
            "_type": "case",
            "caseId": 4,
            "createdAt": 1683379107590,
            "createdBy": "user@thehive.local",
            "customFieldValues": {},
            "customFields": {},
            "description": "Hello world",
            "endDate": null,
            "extendedStatus": "New",
            "flag": false,
            "id": "~81948848",
            "impactStatus": null,
            "owner": "user@thehive.local",
            "pap": 1,
            "permissions": [],
            "resolutionStatus": null,
            "severity": 1,
            "stage": "New",
            "startDate": 1683379107537,
            "stats": {},
            "status": "Open",
            "summary": null,
            "tags": [
                "one-tag"
            ],
            "title": "TestAlert1",
            "tlp": 1,
            "updatedAt": null,
            "updatedBy": null
        },
        "createdAt": 1683379109195,
        "createdBy": "user@thehive.local",
        "data": "1.1.1.1",
        "dataType": "ip",
        "id": "~41017576",
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "maybe bad",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683379109195,
        "stats": {},
        "tags": [
            "destination-ip"
        ],
        "tlp": 0
    },
    "objectId": "~41017576",
    "objectType": "case_artifact",
    "operation": "Creation",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1471",
    "rootId": "~81948848",
    "startDate": 1683379110293
}
```
