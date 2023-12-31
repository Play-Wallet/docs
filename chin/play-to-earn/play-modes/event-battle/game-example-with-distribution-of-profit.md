# 游戏示例与利润分配

以下是一个有五名参与者的 "特朗普会进监狱吗?" 事件示例，以及他们对事件是否发生的预测。

| 参与者    | 事件结果 | 金额 (ARB) |
| -------- | ------- | ---------- |
| 玩家 1   | 否      | 10,000     |
| 玩家 2   | 否      | 10,000     |
| 玩家 3   | 是      | 1,000      |
| 玩家 4   | 是      | 100        |
| 玩家 5   | 是      | 10         |

在这个示例中，对"否"的总金额是20,000 ARB，而对"是"的总金额是1,110 ARB。

假设事件发生了（"是"结果胜出），我们可以使用按份彩票系统为参与者3、4和5计算支付款。

| 参与者    | 事件结果 | 金额 (ARB) | 支付 (ARB) |
| -------- | ------- | ---------- | ---------- |
| 玩家 3   | 是      | 1,000      | 18,000     |
| 玩家 4   | 是      | 100        | 1,800      |
| 玩家 5   | 是      | 10         | 180        |

为了计算支付款，我们首先确定获胜结果的总资金池，这是失败结果上放置的金额的总和（在这种情况下为20,000 ARB）。然后，我们将总池除以获胜结果的放置金额总和（1,110 ARB）以获得支付乘数（20,000 / 1,110 ≈ 18）。最后，我们将每个参与者的放置金额乘以支付乘数，以确定他们各自的支付款。

例如，对于参与者3，支付款是 1,000 ARB \* 18 = 18,000 ARB。类似地，参与者4和5的支付款分别为1,800 ARB和180 ARB。
