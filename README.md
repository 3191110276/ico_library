# ICO Library
A library of ICO workflows, tasks, and custom data types. All operations are categorized based on the target type. See below for a list of all currently supported target types:
* [Cisco AppDynamics](#cisco-appdynamics)
* [Cisco Intersight Hyperconverged](#cisco-intersight-hyperconverged)
* [Cisco Intersight Kubernetes](#cisco-intersight-kubernetes)
* [Cisco Intersight Platform](#cisco-intersight-platform)
* [Cisco IOx](#cisco-iox)
* [Cisco ThousandEyes](#cisco-thousandeyes)
* [Cisco Webex](#cisco-webex)
* [Continuous Integration](#continuous-integration)
* [Kubernetes](#kubernetes)

<!--  
Object states:

:white_check_mark: Implemented

:construction: Work in Progress

:large_blue_circle: Planned

:red_circle: Blocked
-->

## Cisco AppDynamics

### Tasks
<table>
  <tr>
    <th>Object</th>
    <th>Operation</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <!-- Application -->
  <tr>
    <td rowspan="2">Application</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Database -->
  <tr>
    <td rowspan="2">Database</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
</table>


## Cisco Intersight Hyperconverged

### Tasks
<table>
  <tr>
    <th>Object</th>
    <th>Operation</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <!-- Cluster Profile -->
  <tr>
    <td>Cluster Profile</td>
    <td>Read</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_hyperconverged/tasks/ReadClusterProfile.json">Link</a></td>
  </tr>
</table>


## Cisco Intersight Kubernetes

### Tasks
<table>
  <tr>
    <th>Object</th>
    <th>Operation</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <!-- Add-Ons Policy -->
  <tr>
    <td rowspan="2">Add-Ons Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateAdd-OnsPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Cluster Profile -->
  <tr>
    <td rowspan="4">Cluster Profile</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Deploy</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/DeployClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Undeploy</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/UndeployClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/DeleteClusterProfile.json">Link</a></td>
  </tr>
  
  <!-- Container Runtime Policy -->
  <tr>
    <td rowspan="2">Container Runtime Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateContainerRuntimePolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Kubernetes Version Policy -->
  <tr>
    <td rowspan="2">Kubernetes Version Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateKubernetesVersionPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Network CIDR Policy -->
  <tr>
    <td rowspan="2">Network CIDR Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateNetworkCIDRPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- NodeGroup Profiles -->
  <tr>
    <td rowspan="3">NodeGroup Profile</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateNodeGroupProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Scale</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/ScaleNodeGroupProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Node OS Configuration Policy -->
  <tr>
    <td rowspan="2">Node OS Configuration Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateNodeOSConfigurationPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Trusted Certificate Authorities Policy -->
  <tr>
    <td rowspan="2">Trusted Certificate Authorities Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateTrustedCertificateAuthoritiesPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Virtual Machine Infra Config Policy -->
  <tr>
    <td rowspan="2">Virtual Machine Infra Config Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateVirtualMachineInfraConfigPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Virtual Machine Instance Type Policy -->
  <tr>
    <td rowspan="2">Virtual Machine Instance Type Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/tasks/CreateVirtualMachineInstanceTypePolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
</table>
* These Delete operations use the generic "Delete Managed Object" task for Intersight

### Workflows
<table>
  <tr>
    <th>Action</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <tr>
    <td>Create and deploy a new cluster</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/workflows/CreateanddeployanewCluster.json">Link</a></td>
  </tr>
  
  <tr>
    <td>Auto-Scale Cluster based on IVS utilization</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <tr>
    <td>Auto-Scale Cluster based on IWO utilization</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
</table>


## Cisco Intersight Platform

### Tasks
<table>
  <tr>
    <th>Object</th>
    <th>Operation</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <!-- HTTP Target -->
  <tr>
    <td rowspan="2">HTTP Target</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/CreateHTTPTarget.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteHTTPTarget.json">Link</a></td>
  </tr>
  
  <!-- Managed Object -->
  <tr>
    <td>Managed Object</td>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/DeleteManagedObject.json">Link</a></td>
  </tr>
  
  <!-- Workflow -->
  <tr>
    <td>Workflow</td>
    <td>Cancel</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/tasks/CancelWorkflow.json">Link</a></td>
  </tr>
</table>

### Workflows
<table>
  <tr>
    <th>Action</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <tr>
    <td>Cancel Workflow</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/workflows/CancelWorkflow.json">Link</a></td>
  </tr>
</table>


## Cisco IOx
To be evaluated


## Cisco ThousandEyes

### Tasks
<table>
  <tr>
    <th>Object</th>
    <th>Operation</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <!-- Test: Routing - BGP -->
  <tr>
    <td>Test: Routing - BGP</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: Network - Agent to Server -->
  <tr>
    <td>Test: Network - Agent to Server</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: Network - Agent to Agent -->
  <tr>
    <td>Test: Network - Agent to Agent</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: DNS - DNS to Server -->
  <tr>
    <td>Test: DNS - DNS to Server</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: DNS - DNS Trace -->
  <tr>
    <td>Test: DNS - DNS Trace</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: DNS - DNSSEC -->
  <tr>
    <td>Test: DNS - DNSSEC</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: Web - HTTP Server -->
  <tr>
    <td>Test: Web - HTTP Server</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: Web - Page Load -->
  <tr>
    <td>Test: Web - Page Load</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: Web - Transaction -->
  <tr>
    <td>Test: Web - Transaction</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: Web - FTP Server -->
  <tr>
    <td>Test: Web - FTP Server</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: Voice - SIP Server -->
  <tr>
    <td>Test: Voice - SIP Server</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Test: Voice - RTP Stream -->
  <tr>
    <td>Test: Voice - RTP Stream</td>
    <td>Create</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Any Test -->
  <tr>
    <td>Test</td>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
</table>


### Workflows
<table>
  <tr>
    <th>Action</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <tr>
    <td>Create a new ThousandEyes test</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
</table>


## Cisco Webex

### Tasks
<table>
  <tr>
    <th>Object</th>
    <th>Operation</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <!-- Membership -->
  <tr>
    <td rowspan="2">Membership</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/tasks/CreateMembership.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/tasks/DeleteMembership.json">Link</a></td>
  </tr>
  
  <!-- Message -->
  <tr>
    <td rowspan="2">Message</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/tasks/CreateMessage.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/tasks/DeleteMessage.json">Link</a></td>
  </tr>
  
  <!-- Room -->
  <tr>
    <td rowspan="2">Room</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/tasks/CreateRoom.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/tasks/DeleteRoom.json">Link</a></td>
  </tr>
  
  <!-- Webhook -->
  <tr>
    <td rowspan="2">Webhook</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/tasks/CreateWebhook.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/tasks/DeleteWebhook.json">Link</a></td>
  </tr>
</table>


## Continuous Integration
To be evaluated


## Kubernetes

### Tasks
<table>
  <tr>
    <th>Object</th>
    <th>Operation</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <!-- ClusterRole -->
  <tr>
    <td rowspan="2">ClusterRole</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- ClusterRoleBinding -->
  <tr>
    <td rowspan="2">ClusterRoleBinding</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- ConfigMap -->
  <tr>
    <td rowspan="2">ConfigMap</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- CronJob -->
  <tr>
    <td rowspan="2">CronJob</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- CustomResourceDefinition -->
  <tr>
    <td rowspan="2">CustomResourceDefinition</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- DaemonSet -->
  <tr>
    <td rowspan="2">DaemonSet</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Deployment -->
  <tr>
    <td rowspan="2">Deployment</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- HorizontalPodAutoscaler -->
  <tr>
    <td rowspan="2">HorizontalPodAutoscaler</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Ingress -->
  <tr>
    <td rowspan="2">Ingress</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Job -->
  <tr>
    <td rowspan="2">Job</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Namespace -->
  <tr>
    <td rowspan="2">Namespace</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Node -->
  <tr>
    <td rowspan="2">Node</td>
    <td>Drain</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Uncordon</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- NetworkPolicy -->
  <tr>
    <td rowspan="2">NetworkPolicy</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- PersistentVolume -->
  <tr>
    <td rowspan="2">PersistentVolume</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- PersistentVolumeClaim -->
  <tr>
    <td rowspan="2">PersistentVolumeClaim</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Pod -->
  <tr>
    <td rowspan="2">Pod</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- PodDisruptionBudget -->
  <tr>
    <td rowspan="2">PodDisruptionBudget</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- PodSecurityPolicy -->
  <tr>
    <td rowspan="2">PodSecurityPolicy</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- ReplicaSet -->
  <tr>
    <td rowspan="2">ReplicaSet</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- ResourceQuota -->
  <tr>
    <td rowspan="2">ResourceQuota</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Role -->
  <tr>
    <td rowspan="2">Role</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- RoleBinding -->
  <tr>
    <td rowspan="2">RoleBinding</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Secret -->
  <tr>
    <td rowspan="2">Secret</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- Service -->
  <tr>
    <td rowspan="2">Service</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- ServiceAccount -->
  <tr>
    <td rowspan="2">ServiceAccount</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- StatefulSet -->
  <tr>
    <td rowspan="2">StatefulSet</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  
  <!-- StorageClass -->
  <tr>
    <td rowspan="2">StorageClass</td>
    <td>Create/Update</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
  </tr>
</table>
