## Open a Case with Keys

#### HTTP Request

`POST https://api-trade.opskins.com/ICase/OpenWithKeys/v1`

#### Authentication

API key required.

#### Input

Parameter | Type | Required   | Description
--------- | -----| :--------: | -----------
case_id | int | + | The ID of the case being opened
amount  | int |  | Number of cases to open.  Defaults to `1`.  Maximum value of `100`.
    
#### Output

Parameter | Type | Description
--------- | -----| -------- 
cases | object | [Standard OpenedCase Object](/ICase.md#standard-openedcase-object)