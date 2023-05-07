# Observable

### Observable added

```json
{
    "_createdAt": 1683315002815,
    "_createdBy": "user@thehive.local",
    "_id": "~40988832",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683315002778,
        "_createdBy": "user@thehive.local",
        "_id": "~12336",
        "_type": "Observable",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683315002806,
            "_updatedBy": "user@thehive.local",
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
    "object": {
        "_createdAt": 1683315002778,
        "_createdBy": "user@thehive.local",
        "_id": "~12336",
        "_type": "Observable",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683315002806,
            "_updatedBy": "user@thehive.local",
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
    "objectId": "~12336",
    "objectType": "Observable",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:346",
    "rootId": "~40976512"
}
```

---

### Add Tag to an Observable

```json
{
    "_createdAt": 1683360607326,
    "_createdBy": "user@thehive.local",
    "_id": "~40980528",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683315002778,
        "_createdBy": "user@thehive.local",
        "_id": "~12336",
        "_type": "Observable",
        "_updatedAt": 1683360607316,
        "_updatedBy": "user@thehive.local",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683360607307,
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
            "a-sample-tag",
            "new-tag"
        ],
        "tlp": 2
    },
    "details": {
        "tags": [
            "a-sample-tag",
            "new-tag"
        ]
    },
    "object": {
        "_createdAt": 1683315002778,
        "_createdBy": "user@thehive.local",
        "_id": "~12336",
        "_type": "Observable",
        "_updatedAt": 1683360607316,
        "_updatedBy": "user@thehive.local",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683360607307,
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
            "a-sample-tag",
            "new-tag"
        ],
        "tlp": 2
    },
    "objectId": "~12336",
    "objectType": "Observable",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:537",
    "rootId": "~40976512"
}
```

---

### Observable deleted

```json
{
    "_createdAt": 1683360734678,
    "_createdBy": "user@thehive.local",
    "_id": "~81940656",
    "_type": "Audit",
    "action": "delete",
    "context": {
        "_id": "~40976560",
        "_type": "Share"
    },
    "details": {
        "data": "1.1.1.1",
        "dataType": "domain"
    },
    "objectId": "~12336",
    "objectType": "Observable",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:546",
    "rootId": "~40976512"
}
```
