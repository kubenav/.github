<div align="center">
  <img src="https://github.com/kubenav/kubenav/blob/main/utils/images/repo/github-readme-logo.png" width="200" />
  <br><br>

  **kubenav** is the navigator for your **Kubernetes** clusters right in your pocket. kubenav is a **mobile** app to manage Kubernetes clusters and to get an overview of the status of your Kubernetes resources.

  <p>
    <a href="https://apps.apple.com/us/app/kubenav/id1494512160" target="_blank"><img src="https://github.com/kubenav/kubenav/blob/main/utils/images/repo/badge-app-store.svg" height="50" /></a>
    <a href="https://play.google.com/store/apps/details?id=io.kubenav.kubenav" target="_blank"><img src="https://github.com/kubenav/kubenav/blob/main/utils/images/repo/badge-google-play.svg" height="50" /></a>
  </p>

  <table>
    <tr>
      <td><img src="https://github.com/kubenav/kubenav/blob/main/utils/images/stores/iphone65-1.png" /></td>
      <td><img src="https://github.com/kubenav/kubenav/blob/main/utils/images/stores/iphone65-2.png" /></td>
      <td><img src="https://github.com/kubenav/kubenav/blob/main/utils/images/stores/iphone65-3.png" /></td>
    </tr>
  </table>
</div>

kubenav is a mobile app to manage Kubernetes clusters. The app provides an overview of all resources in a Kubernetes cluster, including current status information for workloads. The details view for resources provides additional information. It is possible to view logs and events or to get a shell into a container. You can also edit and delete resources or scale your workloads within the app.

The app is developed using [Flutter](https://flutter.dev) and [Go](https://go.dev). For more information you can read through our [contribution guidelines](https://github.com/kubenav/kubenav/blob/main/CONTRIBUTING.md) for development.

## Features

- **Available mobile:** kubenav provides the same experience as kubectl for mobile.
- **Manage Resources:** All major resources like Deployments, StatefulSets, DaemonSets, Pods, etc. are supported.
- **Custom Resource Definitions:** View all Custom Resource Definitions and mange Custom Resources.
- **Modify Resources:** Edit and delete all available resources or scale your Deployments, StatefulSets, DaemonSets.
- **Filter and Search:** Filter the resources by Namespace and find them by their name.
- **Status Information:** Fast overview of the status of workloads and detailed information including Events.
- **Resource Usage:** View the requests, limits and current usage of Pods and Containers.
- **Logs:** View the logs of a container or stream the logs in realtime.
- **Terminal:** Get a shell into a container, right from your phone.
- **Manage multiple Clusters:** Add multiple clusters via `kubeconfig` or your preferred Cloud Provider, including Google, AWS and Azure.
- **Port-Forwarding:** Create a port-forwarding connection to one of your Pods and open the served page in your browser.
- **Prometheus Integration:** kubenav allows you to view your Prometheus metrics directly in the dashboard and to build your own dashboards via the Prometheus plugin.
