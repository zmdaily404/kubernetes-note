minReadySeconds 如何影响就绪探测？
https://stackoverflow.com/questions/53239081/how-does-minreadyseconds-affect-readiness-probe

查看deployment的rs历史版本
<code>
kubectl rollout history deployment <DP_NAME>
</code>

回滚到上次deployment的rs版本
<code>
kubectl rollout undo deployment <DP_NAME>
</code>

回滚到指定revision的deploymentrs版本
<code>
kubectl rollout undo deployment <DP_NAME> --to-revision=<INT>
</code>
