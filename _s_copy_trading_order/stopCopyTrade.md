---
title: Stop copy trading
position_number: 24
type: post
description: /v1/copy-trade-account/copy-trade/cancel-follow
parameters:
    -
        name: leaderOrderId
        type: number
        mandatory: true
        default:
        description: leader order id
        ranges:
content_markdown: >-
    #### **Limit Flow Rules**

    2/s/apikey
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
                     "rc": 0,
                     "mc": "string",
                     "ma": [
                       {}
                     ],
                     "result": true
                   }
        title: Response
        language: json
---