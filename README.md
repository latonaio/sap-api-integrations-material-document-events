# sap-api-integrations-material-document-events  
sap-api-integrations-material-document-events は、外部システム(特にエッジコンピューティング環境)をSAPと統合することを目的として、SAP上で発生した入出庫伝票イベントを、SAP API で出力するマイクロサービスです。  
sap-api-integrations-material-document-events には、サンプルのAPI Json フォーマットが含まれています。  

## 動作環境
sap-api-integrations-material-document-events は、主にエッジコンピューティング環境における動作にフォーカスしています。  
使用する際は、事前に下記の通り エッジコンピューティングの動作環境（推奨/必須）を用意してください。  
・ エッジ Kubernetes （推奨）  
・ AION のリソース （推奨）  
・ OS: LinuxOS （必須）  
・ CPU: ARM/AMD/Intel（いずれか必須）  

## クラウド環境での利用
sap-api-integrations-material-document-events は、外部システムがクラウド環境である場合にSAPと統合するときにおいても、利用可能なように設計されています。  