---
title: 스테이킹 관리
weight: 70
type: docs
---

이 가이드를 사용하여 XPLA 볼트에서 스테이킹 위임을 관리하세요. 보상을 스테이킹하거나 출금하는 방법을 알아보려면 [XPLA 모바일 볼트 튜토리얼]({{< ref "vaults/mobile-vault" >}})을 참조하세요.

XPLA 볼트를 처음 사용하는 경우 [XPLA 볼트 튜토리얼]({{< ref "web-vault" >}})을 참조하세요.

## XPLA 스테이킹

XPLA를 검증인에게 스테이킹하여 보상을 받으세요. 스테이킹하기 전에 지갑에 XPLA가 있는지 확인하세요. [거래소]({{< ref "wallet" >}})에서 XPLA를 전송할 수 있습니다.

1. XPLA 볼트를 열고 **Stake**를 클릭합니다.

2. 검증인을 선택하고 검증인 목록의 **Moniker** 열에서 이름을 클릭합니다.

3. **My delegations** 섹션에서 **Delegate**를 클릭합니다. 새 창이 나타납니다.

4. **Amount** 필드에 위임할 XPLA양을 지정합니다.

   {{< alert context="warning" >}}
   **수수료를 위한 코인 보관**

   수수료 지불을 위해 항상 코인을 일부 보관하세요. 지갑 전체 금액을 스테이킹하지 마세요. 수수료로 사용할 돈이 없으면 거래를 할 수 없습니다.
   {{< /alert >}}

5. 금액과 수수료를 다시 한 번 확인합니다. 비밀번호를 입력하고 **Submit**을 클릭합니다.

축하합니다. 방금 XPLA를 위임하셨습니다!

## 스테킹 보상 인출

보상은 XPLA 스테이킹하는 순간부터 적립되기 시작합니다. XPLA 볼트의 스테이킹 섹션에서 보상을 모니터링하세요. 보상이 충분하면 다음 단계에 따라 보상을 인출하세요:

1. XPLA 볼트를 열고 **Stake**를 클릭합니다.

2. 모든 보상을 수령하려면 스테이킹 페이지의 오른쪽 상단에 있는 **Withdraw all rewards**을 클릭합니다. 단일 검증인으로부터 보상을 인출하려면 목록에서 해당 검증인의 이름을 클릭하고 해당 페이지에서 **Withdraw rewards**을 클릭합니다. 새 창이 나타납니다.

3. 금액을 검토하고 **Submit**을 클릭합니다.

축하합니다. 방금 스테이킹 보상을 출금하셨습니다!

## 재위임

재위임은 21일의 스테이킹 해제 기간을 기다리지 않고도 스테이킹된 XPLA를 다른 검증인에게 이전할 수 있는 기능입니다. 재위임은 즉시 이루어집니다.

{{< alert context="warning" >}}
**경고**

사용자가 한 검증자에서 다른 검증자로 스테이킹된 XPLA를 재위임하면, 스테이킹된 XPLA를 받은 검증자는 21일 동안 추가 재위임 트랜잭션을 할 수 없습니다. 이 요건은 재위임 트랜잭션을 생성한 지갑에만 적용됩니다.
{{< /alert >}}

1. XPLA 볼트를 열고 지갑을 연결합니다. **Stake**를 클릭합니다.

2. 재위임할 검증인을 클릭합니다.

3. **My delegations** 섹션에서 **Redelegate**를 클릭합니다.

4. 재위임할 검증자를 선택합니다.

5. 재위임할 XPLA의 양을 입력합니다.

6. 금액을 확인하고 **Submit**을 클릭합니다.

스테이킹한 XPLA가 새 검증인에게 이전됩니다.

## 위임 취소

위임을 취소하면 검증인으로부터 XPLA를 스테이킹 해제할 수 있습니다. 스테이킹 해제 기간은 21일이 소요됩니다.

{{< alert context="warning" >}}
**경고**

위임 또는 위임 취소 프로세스는 한 번 시작하면 중지할 수 없습니다.
위임 취소는 완료하는데 21일이 걸립니다. 트랜잭션 위임 또는 위임 취소를 취소하는 유일한 방법은 언본딩 프로세스가 완료될 때까지 가디라는 것입니다. 또는 21일을 기다리지 않고 다른 검증인에게 스테이킹된 XPLA를 재위임할 수 있습니다.
{{< /alert >}}

1. XPLA 볼트를 열고 지갑을 연결합니다. **Stake**를 클릭합니다.

2. 스테이킹을 해제하려는 검증인을 클릭합니다.

3. **My delegations** 섹션에서 **Undelegate**를 클릭합니다.

4. 위임 취소하려는 XPLA의 양을 입력합니다. **Submit**을 클릭합니다.

스테이킹된 XPLA의 바인딩이 해제됩니다. 절차를 완료하려면 21일 후에 다시 확인해주세요.
