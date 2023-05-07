# Attachment

### An Attachment added to a Case

```json
{
    "_createdAt": 1683360837230,
    "_createdBy": "user@thehive.local",
    "_id": "~49304",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683360837222,
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
        "_createdAt": 1683360837214,
        "_createdBy": "user@thehive.local",
        "_id": "~45208",
        "_type": "Attachment",
        "contentType": "application/zip",
        "hashes": [
            "c8b78ead4a382d7f93c0e502980e34dbf0d51fcd3b35f25e64ef8dc4bc2807de",
            "9329a90a3d11b9dfc2d117a491fec105a9564a26",
            "f8b926358f2cd1301e7310732a2e1e5d"
        ],
        "id": "c8b78ead4a382d7f93c0e502980e34dbf0d51fcd3b35f25e64ef8dc4bc2807de",
        "name": "taxonomies.zip",
        "size": 1799
    },
    "object": {
        "_createdAt": 1683360837214,
        "_createdBy": "user@thehive.local",
        "_id": "~45208",
        "_type": "Attachment",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683360837222,
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
        "contentType": "application/zip",
        "hashes": [
            "c8b78ead4a382d7f93c0e502980e34dbf0d51fcd3b35f25e64ef8dc4bc2807de",
            "9329a90a3d11b9dfc2d117a491fec105a9564a26",
            "f8b926358f2cd1301e7310732a2e1e5d"
        ],
        "id": "c8b78ead4a382d7f93c0e502980e34dbf0d51fcd3b35f25e64ef8dc4bc2807de",
        "name": "taxonomies.zip",
        "size": 1799
    },
    "objectId": "~45208",
    "objectType": "Attachment",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:566",
    "rootId": "~40976512"
}
```

---

### Attachment deleted from a Case

```json
{
    "_createdAt": 1683360955884,
    "_createdBy": "user@thehive.local",
    "_id": "~24616",
    "_type": "Audit",
    "action": "delete",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683360955876,
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
    "objectId": "~45208",
    "objectType": "Attachment",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:580",
    "rootId": "~40976512"
}
```
