https://cap.cloud.sap/docs/guides/using-services#external-service-api

https://cap.cloud.sap/docs/guides/using-services#using-destinations

cf create-service-key \<service-instance-name> \<service-instance-key>

cds bind -2 \<instance-name>:\<key-name>

cds watch --profile hybrid

      
    {

      "name": "Stargate",

      "request": "launch",

      "type": "pwa-node",

      "cwd": "${workspaceFolder}/",

      "runtimeExecutable": "npm",

      "args": [

        "run-script",

        "watch"

      ],

      "console": "internalConsole",

      "internalConsoleOptions": "openOnSessionStart",

      "skipFiles": [

        "<node_internals>/**"

      ]

    }

https://www.youtube.com/watch?v=ObGkZ62mPFk
https://www.youtube.com/watch?v=rWQFbXFEr1M

https://blogs.sap.com/2020/05/26/cap-consume-external-service-part-1/
https://blogs.sap.com/2020/05/27/cap-consume-external-service-part-2/

https://help.sap.com/docs/btp/sap-business-technology-platform/using-mta-extension-descriptors?locale=3f1247537c1a4f069235ee63633659c5.html
https://sap.github.io/cloud-mta-build-tool/usage/

https://blogs.sap.com/2020/08/20/demystifying-xsuaa-in-sap-cloud-foundry/

https://github.wdf.sap.corp/pages/CPSecurity/Knowledge-Base/03_ApplicationSecurity/Syntax%20and%20Semantics%20of%20xs-security.json/
