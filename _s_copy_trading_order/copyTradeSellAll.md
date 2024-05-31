---
title: Sell all lead order
position_number: 6
type: post
description: /v4/order/copy-trade/order/sell-all
parameters:
    -
        name: leaderOrderId
        type: number
        mandatory: true
        default:
        description: leader order id
        ranges:
    -
        name: symbol
        type: string
        mandatory: true
        default:
        description: symbol
        ranges:
content_markdown: >-
    #### **Limit Flow Rules**

    10/s/apikey
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