# Deployment

[Source](https://thenewstack.io/deployment-strategies/)

- **Recreate**

  Version A is terminated then version B is rolled out.
  ![](img/deployment/recreate.gif)

- **Ramped**

  (also known as rolling-update or incremental): Version B is slowly rolled out and replacing version A.
  ![](img/deployment/ramped.gif)

- **Blue/Green**

  Version B is released alongside version A, then the traffic is switched to version B.
  ![](img/deployment/blue-green.gif)

- **Canary**

  Version B is released to a subset of users, then proceed to a full rollout.
  ![](img/deployment/canary.gif)

- **A/B testing**

  Version B is released to a subset of users under specific condition.
  ![](img/deployment/a-b.gif)

- **Shadow**

  Version B receives real-world traffic alongside version A and doesn’t impact the response.
  ![](img/deployment/shadow.gif)
