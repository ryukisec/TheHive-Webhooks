# Procedure

### TTP added to a Case

```json
{
    "_createdAt": 1683359963929,
    "_createdBy": "user@thehive.local",
    "_id": "~40976432",
    "_type": "Audit",
    "action": "create",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683359963919,
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
        "_createdAt": 1683359963916,
        "_createdBy": "user@thehive.local",
        "_id": "~37016",
        "extraData": {},
        "occurDate": 1683359960175,
        "patternId": "T1589.003",
        "patternName": "Employee Names",
        "tactic": "reconnaissance",
        "tacticLabel": "Reconnaissance"
    },
    "object": {
        "_createdAt": 1683359963916,
        "_createdBy": "user@thehive.local",
        "_id": "~37016",
        "alert": null,
        "case": {
            "_createdAt": 1683314327257,
            "_createdBy": "user@thehive.local",
            "_id": "~40976512",
            "_type": "Case",
            "_updatedAt": 1683359963919,
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
        "extraData": {},
        "occurDate": 1683359960175,
        "pattern": {
            "_createdAt": 1683222920778,
            "_createdBy": "system@thehive.local",
            "_id": "~2547792",
            "_type": "Pattern",
            "dataSources": [],
            "defenseBypassed": [],
            "description": "Adversaries may gather employee names that can be used during targeting. Employee names be used to derive email addresses as well as to help guide other reconnaissance efforts and/or craft more-believable lures.\\n\\nAdversaries may easily gather employee names, since they may be readily available and exposed via online or other accessible data sets (ex: [Social Media](https://attack.mitre.org/techniques/T1593/001) or [Search Victim-Owned Websites](https://attack.mitre.org/techniques/T1594)).(Citation: OPM Leak) Gathering this information may reveal opportunities for other forms of reconnaissance (ex: [Search Open Websites/Domains](https://attack.mitre.org/techniques/T1593) or [Phishing for Information](https://attack.mitre.org/techniques/T1598)), establishing operational resources (ex: [Compromise Accounts](https://attack.mitre.org/techniques/T1586)), and/or initial access (ex: [Phishing](https://attack.mitre.org/techniques/T1566) or [Valid Accounts](https://attack.mitre.org/techniques/T1078)).",
            "detection": "Much of this activity may have a very high occurrence and associated false positive rate, as well as potentially taking place outside the visibility of the target organization, making detection difficult for defenders.\\n\\nDetection efforts may be focused on related stages of the adversary lifecycle, such as during Initial Access.",
            "extraData": {},
            "name": "Employee Names",
            "patternId": "T1589.003",
            "patternType": "attack-pattern",
            "permissionsRequired": [],
            "platforms": [
                "PRE"
            ],
            "remoteSupport": false,
            "revoked": false,
            "systemRequirements": [],
            "tactics": [
                "reconnaissance"
            ],
            "url": "https://attack.mitre.org/techniques/T1589/003",
            "version": "1.0"
        },
        "patternId": "T1589.003",
        "patternName": "Employee Names",
        "tactic": "reconnaissance",
        "tacticLabel": "Reconnaissance"
    },
    "objectId": "~37016",
    "objectType": "Procedure",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:467",
    "rootId": "~40976512"
}
```

----

### TTP removed from a Case

```json
{
    "_createdAt": 1683360211376,
    "_createdBy": "user@thehive.local",
    "_id": "~41112",
    "_type": "Audit",
    "action": "delete",
    "context": {
        "_createdAt": 1683314327257,
        "_createdBy": "user@thehive.local",
        "_id": "~40976512",
        "_type": "Case",
        "_updatedAt": 1683360211352,
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
    "objectId": "~37016",
    "objectType": "Procedure",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:479",
    "rootId": "~40976512"
}
```
