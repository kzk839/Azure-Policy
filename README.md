# Azure-Policy
以下を満たすような NSG ルールの作成を、 Deny するための Azure ポリシーです。

1. NSG の受信許可ルールであること
1. 送信元 IP アドレスに、"許可されている IP アドレス リスト" 以外の IP アドレスが含まれていること
1. 宛先ポートに、3389, 22, * のいずれかが含まれていること

詳しくは以下を参照ください。
https://www.michikusayan.com/entry/20221015/1665760446#%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%A0-%E3%83%9D%E3%83%AA%E3%82%B7%E3%83%BC
