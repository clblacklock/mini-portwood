# Mini-Portwood roadmap

Each module of the course adds one piece, and each piece maps to a part of Portwood.

| Module | Adds to Mini-Portwood                                               | Portwood counterpart                                      |
| ------ | ------------------------------------------------------------------- | --------------------------------------------------------- |
| 2      | This repository, its rules and its history                          | Portwood's repository and pull request flow               |
| 3      | Salesforce DX project, `Mini_Template__c` object, permission set    | `sfdx-project.json`, `DocGen_Template__c`, `DocGen_Admin` |
| 4      | `MiniMergeService`, which merges `{Name}` and `{Account.Name}` tags | `DocGenService`, `DocGenDataRetriever`                    |
| 5      | `MiniMergeServiceTest` and user-mode security                       | Portwood's `*Test.cls` classes, `DocGenFlsGuard`          |
| 6      | `MiniPdfService`, which saves a PDF as a File                       | `DocGenHtmlRenderer`, `DocGenPdfSaveQueueable`            |
| 7      | `miniDocButton` Lightning Web Component                             | `docGenRunner`, `DocGenController`                        |
| 8      | Flow action, Queueable and a Postman collection                     | `DocGenFlowAction`, `DocGenBatch`                         |
| 9      | Unlocked package version 0.1.0                                      | Portwood's managed package                                |
