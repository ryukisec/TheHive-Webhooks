# Task Log

### Task Log created

```json
{
    "_createdAt": 1683358854982,
    "_createdBy": "user@thehive.local",
    "_id": "~40980728",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683358854965,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683358854965,
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
        "description": "",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683358838135,
        "status": "InProgress",
        "title": "A sample task"
    },
    "details": {
        "_createdAt": 1683358854934,
        "_createdBy": "user@thehive.local",
        "_id": "~40964328",
        "_type": "Log",
        "attachments": [],
        "date": 1683358854934,
        "extraData": {},
        "message": "A new log",
        "owner": "user@thehive.local"
    },
    "object": {
        "_createdAt": 1683358854934,
        "_createdBy": "user@thehive.local",
        "_id": "~40964328",
        "_type": "Log",
        "attachments": [],
        "date": 1683358854934,
        "extraData": {},
        "message": "A new log",
        "owner": "user@thehive.local",
        "task": {
            "_createdAt": 1683358821765,
            "_createdBy": "user@thehive.local",
            "_id": "~40968384",
            "_type": "Task",
            "_updatedAt": 1683358854965,
            "_updatedBy": "user@thehive.local",
            "assignee": "user@thehive.local",
            "case": {
                "_createdAt": 1683314327257,
                "_createdBy": "user@thehive.local",
                "_id": "~40976512",
                "_type": "Case",
                "_updatedAt": 1683358854965,
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
            "description": "",
            "extraData": {},
            "flag": false,
            "group": "default",
            "mandatory": false,
            "order": 0,
            "startDate": 1683358838135,
            "status": "InProgress",
            "title": "A sample task"
        }
    },
    "objectId": "~40964328",
    "objectType": "Log",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:276",
    "rootId": "~40976512"
}
```

### Task Log created with `Include in timeline`

```json
{
    "_createdAt": 1683359147553,
    "_createdBy": "user@thehive.local",
    "_id": "~12328",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683359147543,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683359147543,
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
        "description": "",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683358838135,
        "status": "InProgress",
        "title": "A sample task"
    },
    "details": {
        "_createdAt": 1683359147535,
        "_createdBy": "user@thehive.local",
        "_id": "~40976624",
        "_type": "Log",
        "attachments": [],
        "date": 1683359147535,
        "extraData": {},
        "includeInTimeline": 1683359147509,
        "message": "Include this in the timeline",
        "owner": "user@thehive.local"
    },
    "object": {
        "_createdAt": 1683359147535,
        "_createdBy": "user@thehive.local",
        "_id": "~40976624",
        "_type": "Log",
        "attachments": [],
        "date": 1683359147535,
        "extraData": {},
        "includeInTimeline": 1683359147509,
        "message": "Include this in the timeline",
        "owner": "user@thehive.local",
        "task": {
            "_createdAt": 1683358821765,
            "_createdBy": "user@thehive.local",
            "_id": "~40968384",
            "_type": "Task",
            "_updatedAt": 1683359147543,
            "_updatedBy": "user@thehive.local",
            "assignee": "user@thehive.local",
            "case": {
                "_createdAt": 1683314327257,
                "_createdBy": "user@thehive.local",
                "_id": "~40976512",
                "_type": "Case",
                "_updatedAt": 1683359147543,
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
            "description": "",
            "extraData": {},
            "flag": false,
            "group": "default",
            "mandatory": false,
            "order": 0,
            "startDate": 1683358838135,
            "status": "InProgress",
            "title": "A sample task"
        }
    },
    "objectId": "~40976624",
    "objectType": "Log",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:297",
    "rootId": "~40976512"
}
```

---

### Attachment added to Task Log

```json
{
    "_createdAt": 1683361067650,
    "_createdBy": "user@thehive.local",
    "_id": "~53400",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683361067638,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683361067638,
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
        "description": "",
        "dueDate": 1682942400604,
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683358838135,
        "status": "InProgress",
        "title": "A sample task"
    },
    "details": {
        "_createdAt": 1683361067554,
        "_createdBy": "user@thehive.local",
        "_id": "~40972520",
        "_type": "Log",
        "attachments": [
            {
                "_createdAt": 1683361067636,
                "_createdBy": "user@thehive.local",
                "_id": "~40976616",
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
            }
        ],
        "date": 1683361067554,
        "extraData": {},
        "message": "Attachment-Test",
        "owner": "user@thehive.local"
    },
    "object": {
        "_createdAt": 1683361067554,
        "_createdBy": "user@thehive.local",
        "_id": "~40972520",
        "_type": "Log",
        "attachments": [
            {
                "_createdAt": 1683361067636,
                "_createdBy": "user@thehive.local",
                "_id": "~40976616",
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
            }
        ],
        "date": 1683361067554,
        "extraData": {},
        "message": "Attachment-Test",
        "owner": "user@thehive.local",
        "task": {
            "_createdAt": 1683358821765,
            "_createdBy": "user@thehive.local",
            "_id": "~40968384",
            "_type": "Task",
            "_updatedAt": 1683361067638,
            "_updatedBy": "user@thehive.local",
            "assignee": "user@thehive.local",
            "case": {
                "_createdAt": 1683314327257,
                "_createdBy": "user@thehive.local",
                "_id": "~40976512",
                "_type": "Case",
                "_updatedAt": 1683361067638,
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
            "description": "",
            "dueDate": 1682942400604,
            "extraData": {},
            "flag": false,
            "group": "default",
            "mandatory": false,
            "order": 0,
            "startDate": 1683358838135,
            "status": "InProgress",
            "title": "A sample task"
        }
    },
    "objectId": "~40972520",
    "objectType": "Log",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:600",
    "rootId": "~40976512"
}
```

---

### Task Log edited

```json
{
    "_createdAt": 1683359004713,
    "_createdBy": "user@thehive.local",
    "_id": "~40972480",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683359004693,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683359004694,
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
        "description": "",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683358838135,
        "status": "InProgress",
        "title": "A sample task"
    },
    "details": {
        "message": "A new log; EDITED"
    },
    "object": {
        "_createdAt": 1683358854934,
        "_createdBy": "user@thehive.local",
        "_id": "~40964328",
        "_type": "Log",
        "_updatedAt": 1683359004692,
        "_updatedBy": "user@thehive.local",
        "attachments": [],
        "date": 1683358854934,
        "extraData": {},
        "message": "A new log; EDITED",
        "owner": "user@thehive.local",
        "task": {
            "_createdAt": 1683358821765,
            "_createdBy": "user@thehive.local",
            "_id": "~40968384",
            "_type": "Task",
            "_updatedAt": 1683359004693,
            "_updatedBy": "user@thehive.local",
            "assignee": "user@thehive.local",
            "case": {
                "_createdAt": 1683314327257,
                "_createdBy": "user@thehive.local",
                "_id": "~40976512",
                "_type": "Case",
                "_updatedAt": 1683359004694,
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
            "description": "",
            "extraData": {},
            "flag": false,
            "group": "default",
            "mandatory": false,
            "order": 0,
            "startDate": 1683358838135,
            "status": "InProgress",
            "title": "A sample task"
        }
    },
    "objectId": "~40964328",
    "objectType": "Log",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:287",
    "rootId": "~40976512"
}
```

---

### Task Log deleted

```json
{
    "_createdAt": 1683359286793,
    "_createdBy": "user@thehive.local",
    "_id": "~40968424",
    "_type": "Audit",
    "action": "delete",
    "context": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683359286761,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683359286761,
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
        "description": "",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683358838135,
        "status": "InProgress",
        "title": "A sample task"
    },
    "details": {},
    "objectId": "~40964328",
    "objectType": "Log",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:308",
    "rootId": "~40976512"
}
```
