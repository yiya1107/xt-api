---
title: Get user role
position_number: 11
type: get
description: /v4/account/copy-trade/user-status
parameters:
 
content_markdown: >-
    #### **Limit Flow Rules**

    1/s/apikey
left_code_blocks:
    -
        code_block:
        title: Java
        language: java
    -
        code_block:
        title: Python
        language: python
right_code_blocks:
    -
        code_block: |-
                {
                  "ma": [
                    {}
                  ],
                  "mc": "string",
                  "rc": 0,
                  "result": "string"        //LEADER、FOLLOWER、NONE
                }
        title: Response
        language: json
---