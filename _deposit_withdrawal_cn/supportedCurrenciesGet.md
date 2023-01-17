---
title: 获取XT可充提的币种
position_number: 1
type: get
description: /v4/public/wallet/support/currency
parameters:
    

content_markdown: >-
    #### **备注**

    currency  、chain 字段需要在后续充值/提现接口中使用
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
                  "result": [
                    {
                        "currency": "string",               //币种
                        "supportChains": [
                            {
                                "chain": "Bitcon",          //支持的转账网络
                                "depositEnabled": true,     //是否支持充值，true:支持，false:不支持
                                "withdrawEnabled": true     //是否支持提现，true:支持，false:不支持
                            }
                            {
                                "chain": "FIO",
                                "depositEnabled": true,
                                "withdrawEnabled": true
                            }
                        ]           
                    },
                    {
                        "currency": "string",
                        "supportChains": [
                            {
                                "chain": "Ethereum",
                                "depositEnabled": true,
                                "withdrawEnabled": true
                            }
                        ]
                    }
                  ]
                }
        title: Response
        language: json
---