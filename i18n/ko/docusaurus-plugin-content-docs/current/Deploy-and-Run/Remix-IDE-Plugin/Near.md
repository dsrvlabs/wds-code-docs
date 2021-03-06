---
sidebar_position: 1
---

## Choose a wallet
`multichain-builder`를 사용하기 위해서는 `WELLDONE Wallet`을 설치해야 합니다.

![Select Wallet](img/select-wallet.png?raw=true "Select Wallet")

`multichain-builder` 는 곧 Near Wallet을 지원할 예정입니다.

## Connect
`WELLDONE wallet`을 연결하기 이전에 `WELLDONE wallet`에 NEAR account를 생성해주세요.

![Connect Wallet](img/connect-wallet.png?raw=true "Connect Wallet")

## Create Project

AssemblyScript나 Rust로 작성된 간단한 샘플 컨트랙트 코드 탬플릿을 생성해주세요. 템플릿 소스는 [NEAR Examples](https://examples.near.org/)에서 확인하실 수 있습니다.

![Template Tree](img/template-tree.png?raw=true "Template Tree")

혹은 당신이 새로운 프로젝트를 생성하고자 한다면, New Project 버튼을 클릭하여 생성할 수 있습니다.

## Compile

- `PROJECT TO COMPILE` 섹션에서 컴파일하고자 하는 프로젝트를 선택하세요.
- 컴파일할 코드의 언어를 선택하세요. 
- Complie버튼을 클릭하세요.
- 컴파일이 완료되면, wasm file이 반환됩니다.

![Project Compile](img/project-compile.png?raw=true "Project Compile")

## Deploy

- If there is a compiled contract code(.wasm), enter a value for `receive_id` and click the deploy button.
- Use your wallet to sign the transaction.

- 컴파일된 컨트랙트 코드가 있는 경우 `receive_id`에 값을 입력하고 디플로이 버튼을 클릭하세요.
- 지갑을 사용하여 거래에 서명하십시오.

![Deploy](img/deploy.png?raw=true "Deploy")

- 컨트랙트가 배포되면, 당신은 함수를 실행시킬 수 있습니다.

![Deployed Contract](img/deployed-contract.png?raw=true "Deployed Contract")

## View and Call function

- `At Address` 내부에 컨트랙트 아이디를 입력하여 기존에 배포된 컨트랙트를 호출할 수 있습니다.
- 호출할 메서드를 선택합니다.
- 필요에 따라 매개변수를 추가합니다.
- `View` or `Call`를 통해 값을 읽거나 트랜젝션을 전송합니다.

![View Function](img/view-function.png?raw=true "View Function")


![Function Call](img/function-call.png?raw=true "Function Call")


