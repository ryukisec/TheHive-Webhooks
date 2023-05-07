# Comment

### Comment added to a Case

```json
{
    "_createdAt": 1683357200987,
    "_createdBy": "user@thehive.local",
    "_id": "~24728",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683357200975,
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
        "author": "user@thehive.local"
    },
    "object": {
        "alert": null,
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683357200975,
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
        "message": "Test"
    },
    "objectId": "~20632",
    "objectType": "Comment",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:197",
    "rootId": "~40976512"
}
```

---

### Comment on a Case edited

```json
{
    "_createdAt": 1683360331755,
    "_createdBy": "user@thehive.local",
    "_id": "~20520",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683360331742,
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
        "author": "user@thehive.local"
    },
    "object": {
        "alert": null,
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683360331742,
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
        "message": "Test; EDITED"
    },
    "objectId": "~20632",
    "objectType": "Comment",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:490",
    "rootId": "~40976512"
}
```

### Comment on a Case deleted

```json
{
    "_createdAt": 1683360449470,
    "_createdBy": "user@thehive.local",
    "_id": "~40984816",
    "_type": "Audit",
    "action": "delete",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683360449454,
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
    "details": {},
    "objectId": "~20632",
    "objectType": "Comment",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:496",
    "rootId": "~40976512"
}
```
