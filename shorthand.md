
---

| **Full Name**                 | **Short Name**        | **Description**                                      |
|-------------------------------|-----------------------|----------------------------------------------------|
| **Pod**                       | `po`                 | Represents a single or multiple containers running on a node. |
| **ReplicaSet**                | `rs`                 | Ensures a specified number of pod replicas are running. |
| **ReplicationController**     | `rc`                 | Legacy object to manage pod replication (less used now). |
| **Deployment**                | `deploy`             | Manages ReplicaSets and provides declarative updates. |
| **StatefulSet**               | `sts`                | Manages stateful applications like databases.      |
| **DaemonSet**                 | `ds`                 | Ensures all nodes run a copy of a pod.             |
| **Job**                       | `job`                | Manages batch and short-lived jobs.               |
| **CronJob**                   | `cj`                 | Manages jobs that run periodically on a schedule.  |
| **Service**                   | `svc`                | Exposes a set of pods as a network service.        |
| **ConfigMap**                 | `cm`                 | Stores configuration data as key-value pairs.      |
| **Secret**                    | `secret`             | Stores sensitive data such as passwords.          |
| **Namespace**                 | `ns`                 | Provides logical separation for resources.         |
| **Node**                      | `no`                 | Represents a worker node in the cluster.           |
| **PersistentVolume**          | `pv`                 | Represents storage in the cluster.                 |
| **PersistentVolumeClaim**     | `pvc`                | Requests storage resources from a PersistentVolume.|
| **Ingress**                   | `ing`                | Manages external HTTP/S access to services.        |
| **HorizontalPodAutoscaler**   | `hpa`                | Automatically scales the number of pods based on metrics. |
| **NetworkPolicy**             | `netpol`             | Defines network access policies for pods.          |
| **Role**                      | `role`               | Defines permissions within a namespace.            |
| **ClusterRole**               | `clusterrole`        | Defines permissions across the cluster.            |
| **RoleBinding**               | `rb`                 | Binds a Role to users or service accounts.         |
| **ClusterRoleBinding**        | `crb`                | Binds a ClusterRole to users or service accounts.  |
| **ServiceAccount**            | `sa`                 | Provides identities for pods to interact with the API. |

---