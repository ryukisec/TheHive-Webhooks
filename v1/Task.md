# Task

### Task created

```json
{
    "_createdAt": 1683315183562,
    "_createdBy": "user@thehive.local",
    "_id": "~16616",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683315183553,
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
        "description": "The description",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "status": "Waiting",
        "title": "Sample-Title"
    },
    "details": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "description": "The description",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "status": "Waiting",
        "title": "Sample-Title"
    },
    "object": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683315183553,
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
        "description": "The description",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "status": "Waiting",
        "title": "Sample-Title"
    },
    "objectId": "~4288",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:364",
    "rootId": "~40976512"
}
```

---

### Task started

Status changed from `New` to `In Progress`

```json
{
    "_createdAt": 1683315958974,
    "_createdBy": "user@thehive.local",
    "_id": "~16472",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "_updatedAt": 1683315958970,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
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
        "description": "The description",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683315958955,
        "status": "InProgress",
        "title": "Sample-Title"
    },
    "details": {
        "endDate": null,
        "status": "InProgress"
    },
    "object": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "_updatedAt": 1683315958970,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
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
        "description": "The description",
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683315958955,
        "status": "InProgress",
        "title": "Sample-Title"
    },
    "objectId": "~4288",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:389",
    "rootId": "~40976512"
}
```

---

### Task closed

```json
{
    "_createdAt": 1683317197106,
    "_createdBy": "user@thehive.local",
    "_id": "~16432",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "_updatedAt": 1683317197099,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
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
        "description": "The description",
        "endDate": 1683317197089,
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683315958955,
        "status": "Completed",
        "title": "Sample-Title"
    },
    "details": {
        "status": "Completed"
    },
    "object": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "_updatedAt": 1683317197099,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
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
        "description": "The description",
        "endDate": 1683317197089,
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683315958955,
        "status": "Completed",
        "title": "Sample-Title"
    },
    "objectId": "~4288",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "a5855809ed2f5223:-33c619e3:187ec6a2aad:-8000:398",
    "rootId": "~40976512"
}
```

---

### Task flagged

```json
{
    "_createdAt": 1683355785832,
    "_createdBy": "user@thehive.local",
    "_id": "~40964344",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "_updatedAt": 1683355785051,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
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
        "description": "The description",
        "endDate": 1683317197089,
        "extraData": {},
        "flag": true,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683315958955,
        "status": "Completed",
        "title": "Sample-Title"
    },
    "details": {
        "flag": true
    },
    "object": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "_updatedAt": 1683355785051,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
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
        "description": "The description",
        "endDate": 1683317197089,
        "extraData": {},
        "flag": true,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683315958955,
        "status": "Completed",
        "title": "Sample-Title"
    },
    "objectId": "~4288",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:62",
    "rootId": "~40976512"
}
```

---

### Task unflagged

```json
{
    "_createdAt": 1683356000939,
    "_createdBy": "user@thehive.local",
    "_id": "~4248",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "_updatedAt": 1683356000236,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
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
        "description": "The description",
        "endDate": 1683317197089,
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683315958955,
        "status": "Completed",
        "title": "Sample-Title"
    },
    "details": {
        "flag": false
    },
    "object": {
        "_createdAt": 1683315183519,
        "_createdBy": "user@thehive.local",
        "_id": "~4288",
        "_type": "Task",
        "_updatedAt": 1683356000236,
        "_updatedBy": "user@thehive.local",
        "assignee": "user@thehive.local",
        "case": {
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
        "description": "The description",
        "endDate": 1683317197089,
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683315958955,
        "status": "Completed",
        "title": "Sample-Title"
    },
    "objectId": "~4288",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:73",
    "rootId": "~40976512"
}
```

---

### Task requires action

```json
{
    "_createdAt": 1683359422832,
    "_createdBy": "user@thehive.local",
    "_id": "~40972336",
    "_type": "Audit",
    "action": "update",
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
    "details": {
        "actionRequired.sample-org": true
    },
    "object": {
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
    "objectId": "~40968384",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:323",
    "rootId": "~40976512"
}
```

---

### Task does not require action anymore

```json
{
    "_createdAt": 1683359583419,
    "_createdBy": "user@thehive.local",
    "_id": "~16424",
    "_type": "Audit",
    "action": "update",
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
    "details": {
        "actionRequired.sample-org": false
    },
    "object": {
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
    "objectId": "~40968384",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:366",
    "rootId": "~40976512"
}
```

---

### Task Due Date set

```json
{
    "_createdAt": 1683359728983,
    "_createdBy": "user@thehive.local",
    "_id": "~40980720",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683359728975,
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
        "dueDate": 1683460800604,
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
        "dueDate": 1683460800604
    },
    "object": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683359728975,
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
        "dueDate": 1683460800604,
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683358838135,
        "status": "InProgress",
        "title": "A sample task"
    },
    "objectId": "~40968384",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:379",
    "rootId": "~40976512"
}
```

---

### Task closed

```json
{
    "_createdAt": 1683361274256,
    "_createdBy": "user@thehive.local",
    "_id": "~40980712",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683361274244,
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
        "endDate": 1683361274239,
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683358838135,
        "status": "Completed",
        "title": "A sample task"
    },
    "details": {
        "status": "Completed"
    },
    "object": {
        "_createdAt": 1683358821765,
        "_createdBy": "user@thehive.local",
        "_id": "~40968384",
        "_type": "Task",
        "_updatedAt": 1683361274244,
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
        "endDate": 1683361274239,
        "extraData": {},
        "flag": false,
        "group": "default",
        "mandatory": false,
        "order": 0,
        "startDate": 1683358838135,
        "status": "Completed",
        "title": "A sample task"
    },
    "objectId": "~40968384",
    "objectType": "Task",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:626",
    "rootId": "~40976512"
}
```

---

### Task Deleted

No webhook
