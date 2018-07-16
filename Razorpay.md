## Razorpay Specific Env Variables

Environment | Variable Description
----------- | --------------------
`AUDIT_LOG_PATH`|Define the path to the [Kubernetes Audit Log](https://kubernetes.io/docs/tasks/debug-application-cluster/audit/) <br/><br/> Default: `/mnt/log/kube-apiserver-audit.log`
`TRACE_LOGS_PATH`| *Required* Define the path to the files that need to be logged. <br/><br/> No Default provided. 
`TRACE_EXCLUDE_PATH`| *Required* Define the path to the files that need to be excluded. <br/><br/> No Default provided. 
`TRACE_LOGS_POS_PATH`| *Required* Define the path to the pos file. This has to be in a volume that is writable by the pod. <br/><br/> No Default provided. 