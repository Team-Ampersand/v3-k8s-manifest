# DOTORI V3 K8s Resource 관리

DOTORI V3의 K8s 리소스를 관리하기 위한 리퍼지토리입니다.

- `/apps`: ArgoCD가 관리하는 메니페스트 파일들을 저장합니다. 자주 변하는 리소스를 저장합니다. (Application)

- `/charts`: Helm으로 관리하는 차트를 정의해놓습니다. 자주 변하지 않는 리소스를 저장합니다. (ArgoCD, Karpenter)

