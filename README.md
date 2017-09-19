# blackhawk
example for parameterized pipeline and deploying

structure:
```
├── LICENSE
├── README.md
└── q2_acq_zml
    ├── bin
    ├── conf
    ├── deploy
    │   ├── 00_core
    │   ├── acquirer-bhnumshttp
    │   ├── acquirer-bhnumsxml
    │   │   ├── 22_bhnumsxml-acquirer-space-loader.xml <- potential target
    │   │   ├── 40_bhnumsxml-acquirertxnmgr.xml <- potential target
    │   │   └── lib
    │   ├── acquirer-creditlimit
    │   ├── acquirer-eNetwork
    │   └── acquirer-paypoint
    ├── jpos-1.6.jar
    ├── lib
    └── nohup.out
```
