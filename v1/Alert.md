# Alert

### Create an Alert with an Observable (via API)

```json
{
    "_createdAt": 1683378066274,
    "_createdBy": "user@thehive.local",
    "_id": "~57496",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "_updatedAt": 1683378066250,
        "_updatedBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "newDate": 1683378066166,
        "observableCount": 1,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "New",
        "status": "New",
        "tags": [],
        "timeToDetect": 0,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "details": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "newDate": 1683378066166,
        "observableCount": 0,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "New",
        "status": "New",
        "tags": [],
        "timeToDetect": 0,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "object": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "_updatedAt": 1683378066250,
        "_updatedBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "newDate": 1683378066166,
        "observableCount": 1,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "New",
        "status": "New",
        "tags": [],
        "timeToDetect": 0,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "objectId": "~40993016",
    "objectType": "Alert",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1265",
    "rootId": "~40993016"
}
```

```json
{
    "_createdAt": 1683378067271,
    "_createdBy": "user@thehive.local",
    "_id": "",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "_updatedAt": 1683378066250,
        "_updatedBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "newDate": 1683378066166,
        "observableCount": 1,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "New",
        "status": "New",
        "tags": [],
        "timeToDetect": 0,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "details": {
        "_createdAt": 1683378066243,
        "_createdBy": "user@thehive.local",
        "_id": "~40993000",
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
        "startDate": 1683378066243,
        "tags": [
            "destination-ip"
        ],
        "tlp": 0
    },
    "object": {
        "_createdAt": 1683378066243,
        "_createdBy": "user@thehive.local",
        "_id": "~40993000",
        "_type": "Observable",
        "alert": {
            "_createdAt": 1683378066188,
            "_createdBy": "user@thehive.local",
            "_id": "~40993016",
            "_type": "Alert",
            "_updatedAt": 1683378066250,
            "_updatedBy": "user@thehive.local",
            "customFieldValues": {},
            "customFields": [],
            "date": 1683378066000,
            "description": "Hello world",
            "extraData": {},
            "follow": true,
            "newDate": 1683378066166,
            "observableCount": 1,
            "pap": 1,
            "severity": 1,
            "source": "API",
            "sourceRef": "API_1",
            "stage": "New",
            "status": "New",
            "tags": [],
            "timeToDetect": 0,
            "title": "TestAlert1",
            "tlp": 1,
            "type": "API"
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
        "startDate": 1683378066243,
        "tags": [
            "destination-ip"
        ],
        "tlp": 0
    },
    "objectId": "~40993000",
    "objectType": "Observable",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1265",
    "rootId": "~40993016"
}
```

---

### Add an Observable to an existing Alert (via API)

```json
{
    "_createdAt": 1683378434866,
    "_createdBy": "user@thehive.local",
    "_id": "~40997096",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "_updatedAt": 1683378434862,
        "_updatedBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "newDate": 1683378066166,
        "observableCount": 2,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "New",
        "status": "New",
        "tags": [],
        "timeToDetect": 0,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "details": {
        "_createdAt": 1683378434859,
        "_createdBy": "user@thehive.local",
        "_id": "~40984624",
        "_type": "Observable",
        "data": "1.1.1.2",
        "dataType": "ip",
        "extraData": {},
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "maybe bad",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683378434859,
        "tags": [
            "destination-ip"
        ],
        "tlp": 0
    },
    "object": {
        "_createdAt": 1683378434859,
        "_createdBy": "user@thehive.local",
        "_id": "~40984624",
        "_type": "Observable",
        "alert": {
            "_createdAt": 1683378066188,
            "_createdBy": "user@thehive.local",
            "_id": "~40993016",
            "_type": "Alert",
            "_updatedAt": 1683378434862,
            "_updatedBy": "user@thehive.local",
            "customFieldValues": {},
            "customFields": [],
            "date": 1683378066000,
            "description": "Hello world",
            "extraData": {},
            "follow": true,
            "newDate": 1683378066166,
            "observableCount": 2,
            "pap": 1,
            "severity": 1,
            "source": "API",
            "sourceRef": "API_1",
            "stage": "New",
            "status": "New",
            "tags": [],
            "timeToDetect": 0,
            "title": "TestAlert1",
            "tlp": 1,
            "type": "API"
        },
        "data": "1.1.1.2",
        "dataType": "ip",
        "extraData": {},
        "ignoreSimilarity": false,
        "ioc": false,
        "message": "maybe bad",
        "pap": 2,
        "reports": {},
        "sighted": false,
        "startDate": 1683378434859,
        "tags": [
            "destination-ip"
        ],
        "tlp": 0
    },
    "objectId": "~40984624",
    "objectType": "Observable",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1326",
    "rootId": "~40993016"
}
```

---

### Start an Alert

```json
{
    "_createdAt": 1683378632644,
    "_createdBy": "user@thehive.local",
    "_id": "~40988720",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "_updatedAt": 1683378632635,
        "_updatedBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "inProgressDate": 1683378632622,
        "newDate": 1683378066166,
        "observableCount": 2,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "InProgress",
        "status": "InProgress",
        "summary": "",
        "tags": [],
        "timeToAcknowledge": 566622,
        "timeToDetect": 0,
        "timeToTriage": 566456,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "details": {
        "stage": "InProgress",
        "status": "InProgress",
        "summary": ""
    },
    "object": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "_updatedAt": 1683378632635,
        "_updatedBy": "user@thehive.local",
        "customFieldValues": {},
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "inProgressDate": 1683378632622,
        "newDate": 1683378066166,
        "observableCount": 2,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "InProgress",
        "status": "InProgress",
        "summary": "",
        "tags": [],
        "timeToAcknowledge": 566622,
        "timeToDetect": 0,
        "timeToTriage": 566456,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "objectId": "~40993016",
    "objectType": "Alert",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1347",
    "rootId": "~40993016"
}
```

---

### Close an Alert as Duplicate

```json
{
    "_createdAt": 1683378744394,
    "_createdBy": "user@thehive.local",
    "_id": "~28712",
    "_type": "Audit",
    "action": "update",
    "context": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "_updatedAt": 1683378744388,
        "_updatedBy": "user@thehive.local",
        "closedDate": 1683378744380,
        "customFieldValues": {},
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "inProgressDate": 1683378632622,
        "newDate": 1683378066166,
        "observableCount": 2,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "Closed",
        "status": "Duplicate",
        "summary": "",
        "tags": [],
        "timeToAcknowledge": 566622,
        "timeToDetect": 0,
        "timeToQualify": 678214,
        "timeToTriage": 566456,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "details": {
        "stage": "Closed",
        "status": "Duplicate",
        "summary": ""
    },
    "object": {
        "_createdAt": 1683378066188,
        "_createdBy": "user@thehive.local",
        "_id": "~40993016",
        "_type": "Alert",
        "_updatedAt": 1683378744388,
        "_updatedBy": "user@thehive.local",
        "closedDate": 1683378744380,
        "customFieldValues": {},
        "customFields": [],
        "date": 1683378066000,
        "description": "Hello world",
        "extraData": {},
        "follow": true,
        "inProgressDate": 1683378632622,
        "newDate": 1683378066166,
        "observableCount": 2,
        "pap": 1,
        "severity": 1,
        "source": "API",
        "sourceRef": "API_1",
        "stage": "Closed",
        "status": "Duplicate",
        "summary": "",
        "tags": [],
        "timeToAcknowledge": 566622,
        "timeToDetect": 0,
        "timeToQualify": 678214,
        "timeToTriage": 566456,
        "title": "TestAlert1",
        "tlp": 1,
        "type": "API"
    },
    "objectId": "~40993016",
    "objectType": "Alert",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1414",
    "rootId": "~40993016"
}
```

---

### Delete an Alert

```json
{
    "_createdAt": 1683378856805,
    "_createdBy": "user@thehive.local",
    "_id": "~41001192",
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
    "details": {},
    "objectId": "~40993016",
    "objectType": "Alert",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:1423",
    "rootId": "~40964176"
}
```
