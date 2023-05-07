# Procedure

### TTP added to a Case

```json
{
    "_id": "~40976432",
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
        "updatedAt": 1683359963919,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683359963929,
    "createdBy": "user@thehive.local",
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
    "id": "~40976432",
    "object": {
        "_createdAt": 1683359963916,
        "_createdBy": "user@thehive.local",
        "_id": "~37016",
        "alert": null,
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
            "updatedAt": 1683359963919,
            "updatedBy": "user@thehive.local"
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
            "description": "Adversaries may gather employee names that can be used during targeting. Employee names be used to derive email addresses as well as to help guide other reconnaissance efforts and/or craft more-believable lures.\\Adversaries may easily gather employee names, since they may be readily available and exposed via online or other accessible data sets (ex: [Social Media](https://attack.mitre.org/techniques/T1593/001) or [Search Victim-Owned Websites](https://attack.mitre.org/techniques/T1594)).(Citation: OPM Leak) Gathering this information may reveal opportunities for other forms of reconnaissance (ex: [Search Open Websites/Domains](https://attack.mitre.org/techniques/T1593) or [Phishing for Information](https://attack.mitre.org/techniques/T1598)), establishing operational resources (ex: [Compromise Accounts](https://attack.mitre.org/techniques/T1586)), and/or initial access (ex: [Phishing](https://attack.mitre.org/techniques/T1566) or [Valid Accounts](https://attack.mitre.org/techniques/T1078)).",
            "detection": "Much of this activity may have a very high occurrence and associated false positive rate, as well as potentially taking place outside the visibility of the target organization, making detection difficult for defenders.\\Detection efforts may be focused on related stages of the adversary lifecycle, such as during Initial Access.",
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
    "objectType": "procedure",
    "operation": "Creation",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:467",
    "rootId": "~40976512",
    "startDate": 1683359964378
}
```

---

### TTP removed from a Case

```json
{
    "_id": "~41112",
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
        "updatedAt": 1683360211352,
        "updatedBy": "user@thehive.local"
    },
    "createdAt": 1683360211376,
    "createdBy": "user@thehive.local",
    "details": {},
    "id": "~41112",
    "objectId": "~37016",
    "objectType": "procedure",
    "operation": "Delete",
    "organisation": {
        "organisation": "sample-org",
        "organisationId": "~40964176"
    },
    "requestId": "fe83537a8ffa36d3:18887829:187efcf369e:-8000:479",
    "rootId": "~40976512",
    "startDate": 1683360212618
}
```
