# Case

### Case Created

```json
{
    "_createdAt": 1683314327296,
    "_createdBy": "user@thehive.local",
    "_id": "~12376",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
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
        "timeToDetect": 4868,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "assignee": "user@thehive.local",
        "customFields": [],
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
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
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
        "timeToDetect": 4868,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:313",
    "rootId": "~40976512"
}
```

```json
{
    "_createdAt": 1683314327291,
    "_createdBy": "user@thehive.local",
    "_id": "~40968192",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
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
        "timeToDetect": 4868,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "share": {
            "organisation": "sample-org",
            "profile": "org-admin"
        }
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
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
        "timeToDetect": 4868,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:313",
    "rootId": "~40976512"
}
```

---

### Status Changed

Status changed from `New` to `In Progress`

```json
{
    "_createdAt": 1683315315625,
    "_createdBy": "user@thehive.local",
    "_id": "~40980608",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683315315617,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "stage": "InProgress",
        "status": "InProgress"
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683315315617,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:381",
    "rootId": "~40976512"
}
```

---

### Tag added to a Case

```json
{
    "_createdAt": 1683356171751,
    "_createdBy": "user@thehive.local",
    "_id": "~8344",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356171734,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "new-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "tags": [
            "new-tag"
        ]
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356171734,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "new-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:92",
    "rootId": "~40976512"
}
```

A second tag is added, but it seems impossible to determine what tag was first. 

```json
{
    "_createdAt": 1683356440474,
    "_createdBy": "user@thehive.local",
    "_id": "~16536",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356440463,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "tags": [
            "first-tag",
            "second-tag"
        ]
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356440463,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:114",
    "rootId": "~40976512"
}
```

A third tag (`aaa`) was added, looks like they stay in order.

```json
{
    "_createdAt": 1683356541863,
    "_createdBy": "user@thehive.local",
    "_id": "~40972536",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356541847,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "first-tag",
            "second-tag",
            "aaa"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "tags": [
            "first-tag",
            "second-tag",
            "aaa"
        ]
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356541847,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "first-tag",
            "second-tag",
            "aaa"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:121",
    "rootId": "~40976512"
}
```

Adding multiple tags at once

```json
{
    "_createdAt": 1683356761744,
    "_createdBy": "user@thehive.local",
    "_id": "~40964336",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356761056,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "mult3",
            "mult2",
            "mult1",
            "aaa",
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
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
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356761056,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "mult3",
            "mult2",
            "mult1",
            "aaa",
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:168",
    "rootId": "~40976512"
}
```

---

### Tag removed from a Case

One and only tag is removed

```json
{
    "_createdAt": 1683356331455,
    "_createdBy": "user@thehive.local",
    "_id": "~40964144",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356330762,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "tags": []
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356330762,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:100",
    "rootId": "~40976512"
}
```

One tag (`aaa`) is removed

```json
{
    "_createdAt": 1683356907349,
    "_createdBy": "user@thehive.local",
    "_id": "~8232",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356907338,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "mult3",
            "mult2",
            "mult1",
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "tags": [
            "mult3",
            "mult2",
            "mult1",
            "first-tag",
            "second-tag"
        ]
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683356907338,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "mult3",
            "mult2",
            "mult1",
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:178",
    "rootId": "~40976512"
}
```

Multiple tags are removed

```json
{
    "_createdAt": 1683357060982,
    "_createdBy": "user@thehive.local",
    "_id": "~40968432",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683357060971,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "tags": [
            "first-tag",
            "second-tag"
        ]
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683357060971,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Test 3",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:187",
    "rootId": "~40976512"
}
```

---

### Description changed

```json
{
    "_createdAt": 1683358654984,
    "_createdBy": "user@thehive.local",
    "_id": "~81932464",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683358654975,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "A totally new description",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "description": "A totally new description"
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683358654975,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "A totally new description",
        "extraData": {},
        "flag": false,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:226",
    "rootId": "~40976512"
}
```

---

### Case closed as Other

```json
{
    "_createdAt": 1683361345108,
    "_createdBy": "user@thehive.local",
    "_id": "~40988920",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683361345100,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "closedDate": 1683361345074,
        "customFieldValues": {},
        "customFields": [],
        "description": "A totally new description",
        "endDate": 1683361345072,
        "extraData": {},
        "flag": false,
        "handlingDuration": 46029473,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "Closed",
        "startDate": 1683314322379,
        "status": "Other",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToResolve": 46029471,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "endDate": 1683361345072,
        "stage": "Closed",
        "status": "Other",
        "summary": "Closed as Other"
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683361345100,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "closedDate": 1683361345074,
        "customFieldValues": {},
        "customFields": [],
        "description": "A totally new description",
        "endDate": 1683361345072,
        "extraData": {},
        "flag": false,
        "handlingDuration": 46029473,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "Closed",
        "startDate": 1683314322379,
        "status": "Other",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToResolve": 46029471,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:638",
    "rootId": "~40976512"
}
```

---

### Case reopened

```json
{
    "_createdAt": 1683361471769,
    "_createdBy": "user@thehive.local",
    "_id": "~40988912",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683361471761,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "closedDate": 1683361345074,
        "customFieldValues": {},
        "customFields": [],
        "description": "A totally new description",
        "endDate": 1683361345072,
        "extraData": {},
        "flag": false,
        "handlingDuration": 46029473,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToResolve": 46029471,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "stage": "InProgress",
        "status": "InProgress"
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683361471761,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "closedDate": 1683361345074,
        "customFieldValues": {},
        "customFields": [],
        "description": "A totally new description",
        "endDate": 1683361345072,
        "extraData": {},
        "flag": false,
        "handlingDuration": 46029473,
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "InProgress",
        "startDate": 1683314322379,
        "status": "InProgress",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToResolve": 46029471,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:647",
    "rootId": "~40976512"
}
```

---

### Case closed as TruePositive with Impact

```json
{
    "_createdAt": 1683361544379,
    "_createdBy": "user@thehive.local",
    "_id": "~40993008",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683361544372,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "closedDate": 1683361345074,
        "customFieldValues": {},
        "customFields": [],
        "description": "A totally new description",
        "endDate": 1683361544346,
        "extraData": {},
        "flag": false,
        "handlingDuration": 46029473,
        "impactStatus": "WithImpact",
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "Closed",
        "startDate": 1683314322379,
        "status": "TruePositive",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToResolve": 46228745,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "details": {
        "endDate": 1683361544346,
        "impactStatus": "WithImpact",
        "stage": "Closed",
        "status": "TruePositive"
    },
    "object": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683361544372,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "closedDate": 1683361345074,
        "customFieldValues": {},
        "customFields": [],
        "description": "A totally new description",
        "endDate": 1683361544346,
        "extraData": {},
        "flag": false,
        "handlingDuration": 46029473,
        "impactStatus": "WithImpact",
        "inProgressDate": 1683315315601,
        "newDate": 1683314327247,
        "number": 3,
        "pap": 2,
        "severity": 2,
        "stage": "Closed",
        "startDate": 1683314322379,
        "status": "TruePositive",
        "summary": "Closed as Other",
        "tags": [
            "first-tag",
            "second-tag"
        ],
        "timeToAcknowledge": 993222,
        "timeToDetect": 4868,
        "timeToResolve": 46228745,
        "timeToTriage": 988354,
        "title": "Test 3",
        "tlp": 2,
        "userPermissions": []
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:656",
    "rootId": "~40976512"
}
```

---

### Case deleted

```json
{
    "_createdAt": 1683378965075,
    "_createdBy": "user@thehive.local",
    "_id": "~41005288",
    "_type": "Audit",
    "action": "delete",
    "context": {
        "_createdAt": 1683223840663,
        "_createdBy": "admin@thehive.local",
        "_id": "~40964176",
        "_type": "Organisation",
        "description": "sample-org",
        "extraData": {},
        "links": [],
        "locked": false,
        "name": "sample-org",
        "observableRule": "manual",
        "taskRule": "manual"
    },
    "details": {
        "number": 3,
        "title": "Test 3"
    },
    "objectId": "~40976512",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1450",
    "rootId": "~40964176"
}
```

---

### Create a Case from an Alert with a Template

```json
{
    "_createdAt": 1683379108025,
    "_createdBy": "user@thehive.local",
    "_id": "~41013480",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683379107590,
        "_createdBy": "user@thehive.local",
        "_id": "~81948848",
        "_type": "Case",
        "alertDate": 1683379038000,
        "alertImportedDate": 1683379107539,
        "alertInProgressDate": 1683379107539,
        "alertNewDate": 1683379038953,
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Hello world",
        "extraData": {},
        "flag": false,
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
        "timeToAcknowledge": 69539,
        "timeToDetect": 953,
        "timeToQualify": 68586,
        "timeToTriage": 68586,
        "title": "[Import in progress: 0%] TestAlert1",
        "tlp": 1,
        "userPermissions": []
    },
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
        "customFields": [],
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
    "object": {
        "_createdAt": 1683379107590,
        "_createdBy": "user@thehive.local",
        "_id": "~81948848",
        "_type": "Case",
        "alertDate": 1683379038000,
        "alertImportedDate": 1683379107539,
        "alertInProgressDate": 1683379107539,
        "alertNewDate": 1683379038953,
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Hello world",
        "extraData": {},
        "flag": false,
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
        "timeToAcknowledge": 69539,
        "timeToDetect": 953,
        "timeToQualify": 68586,
        "timeToTriage": 68586,
        "title": "[Import in progress: 0%] TestAlert1",
        "tlp": 1,
        "userPermissions": []
    },
    "objectId": "~81948848",
    "objectType": "Case",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1471",
    "rootId": "~81948848"
}
```

```json
{
    "_createdAt": 1683379108022,
    "_createdBy": "user@thehive.local",
    "_id": "~40984768",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683379107590,
        "_createdBy": "user@thehive.local",
        "_id": "~81948848",
        "_type": "Case",
        "alertDate": 1683379038000,
        "alertImportedDate": 1683379107539,
        "alertInProgressDate": 1683379107539,
        "alertNewDate": 1683379038953,
        "assignee": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "description": "Hello world",
        "extraData": {},
        "flag": false,
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
        "timeToAcknowledge": 69539,
        "timeToDetect": 953,
        "timeToQualify": 68586,
        "timeToTriage": 68586,
        "title": "[Import in progress: 0%] TestAlert1",
        "tlp": 1,
        "userPermissions": []
    },
    "details": {
        "caseId": "~81948848"
    },
    "object": {
        "_createdAt": 1683379038961,
        "_createdBy": "user@thehive.local",
        "_id": "~40997104",
        "_type": "Alert",
        "_updatedAt": 1683379108009,
        "_updatedBy": "user@thehive.local",
        "caseId": "~81948848",
        "customFieldValues": {},
        "customFields": [],
        "date": 1683379038000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "importedDate": 1683379108007,
        "inProgressDate": 1683379108007,
        "newDate": 1683379038953,
        "observableCount": 1,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "Imported",
        "status": "Imported",
        "tags": [],
        "timeToAcknowledge": 70007,
        "timeToDetect": 0,
        "timeToQualify": 69054,
        "timeToTriage": 69054,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "objectId": "~40997104",
    "objectType": "Alert",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1471",
    "rootId": "~81948848"
}
```

```json
{
    "_createdAt": 1683379109250,
    "_createdBy": "user@thehive.local",
    "_id": "~40992816",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683379109195,
        "_createdBy": "user@thehive.local",
        "_id": "~41017576",
        "_type": "Observable",
        "case": {
            "_createdAt": 1683379107590,
            "_createdBy": "user@thehive.local",
            "_id": "~81948848",
            "_type": "Case",
            "alertDate": 1683379038000,
            "alertImportedDate": 1683379107539,
            "alertInProgressDate": 1683379107539,
            "alertNewDate": 1683379038953,
            "assignee": "user@thehive.local",
            "customFieldValues": {},
            "customFields": [],
            "description": "Hello world",
            "extraData": {},
            "flag": false,
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
            "timeToAcknowledge": 69539,
            "timeToDetect": 953,
            "timeToQualify": 68586,
            "timeToTriage": 68586,
            "title": "TestAlert1",
            "tlp": 1,
            "userPermissions": []
        },
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
    "object": {
        "_createdAt": 1683379109195,
        "_createdBy": "user@thehive.local",
        "_id": "~41017576",
        "_type": "Observable",
        "case": {
            "_createdAt": 1683379107590,
            "_createdBy": "user@thehive.local",
            "_id": "~81948848",
            "_type": "Case",
            "alertDate": 1683379038000,
            "alertImportedDate": 1683379107539,
            "alertInProgressDate": 1683379107539,
            "alertNewDate": 1683379038953,
            "assignee": "user@thehive.local",
            "customFieldValues": {},
            "customFields": [],
            "description": "Hello world",
            "extraData": {},
            "flag": false,
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
            "timeToAcknowledge": 69539,
            "timeToDetect": 953,
            "timeToQualify": 68586,
            "timeToTriage": 68586,
            "title": "TestAlert1",
            "tlp": 1,
            "userPermissions": []
        },
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
    "objectId": "~41017576",
    "objectType": "Observable",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1471",
    "rootId": "~81948848"
}
```
