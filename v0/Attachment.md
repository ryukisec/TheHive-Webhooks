# Attachment

### An Attachment added to a Case

```json
{
    "_id": "~49304",
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
        "updatedAt": 1683360837222,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683360837230,
    "createdBy": "user@thehive.local",
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
    "id": "~49304",
    "object": {
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
            "updatedAt": 1683360837222,
            "updatedBy": "user@thehive.local"
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
    "objectType": "attachment",
    "operation": "Creation",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:566",
    "rootId": "~40976512",
    "startDate": 1683360837756
}
```

---

### Attachment deleted from a Case

```json
{
    "_id": "~24616",
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
        "updatedAt": 1683360955876,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683360955884,
    "createdBy": "user@thehive.local",
    "details": {},
    "id": "~24616",
    "objectId": "~45208",
    "objectType": "attachment",
    "operation": "Delete",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:580",
    "rootId": "~40976512",
    "startDate": 1683360956819
}
```
