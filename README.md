# ICO Library
A library of ICO workflows, tasks, and custom data types. All operations are categorized based on the target type. See below for a list of all currently supported target types:
* [Cisco Intersight Hyperconverged](#cisco-intersight-hyperconverged)
* [Cisco Intersight Kubernetes](#cisco-intersight-kubernetes)
* [Cisco Intersight Platform](#cisco-intersight-platform)
* [Cisco Webex](#cisco-webex)


<!--  
Object states:

:white_check_mark: Implemented

:construction: Work in Progress

:large_blue_circle: Planned

:red_circle: Blocked
-->

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
    <td>:large_blue_circle: Planned</td>
    <td></td>
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
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesAddonsPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesAddonsPolicy.json">Link</a></td>
  </tr>
  
  <!-- Cluster Profile -->
  <tr>
    <td rowspan="4">Cluster Profile</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Deploy</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeployCiscoIntersightKubernetesClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Undeploy</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/UndeployCiscoIntersightKubernetesClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesClusterProfile.json">Link</a></td>
  </tr>
  
  <!-- Container Runtime Policy -->
  <tr>
    <td rowspan="2">Container Runtime Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesContainerRuntimePolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesContainerRuntimePolicy.json">Link</a></td>
  </tr>
  
  <!-- Kubernetes Version Policy -->
  <tr>
    <td rowspan="2">Kubernetes Version Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesKubernetesVersionPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesKubernetesVersionPolicy.json">Link</a></td>
  </tr>
  
  <!-- Network CIDR Policy -->
  <tr>
    <td rowspan="2">Network CIDR Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesNetworkCIDRPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesNetworkCIDRPolicy.json">Link</a></td>
  </tr>
  
  <!-- NodeGroup Profiles -->
  <tr>
    <td rowspan="3">NodeGroup Profile</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesNodeGroupProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Scale</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/ScaleCiscoIntersightKubernetesNodeGroupProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesNodeGroupProfile.json">Link</a></td>
  </tr>
  
  <!-- Node OS Configuration Policy -->
  <tr>
    <td rowspan="2">Node OS Configuration Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesNodeOSConfigurationPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesNodeOSConfigurationPolicy.json">Link</a></td>
  </tr>
  
  <!-- Trusted Certificate Authorities Policy -->
  <tr>
    <td rowspan="2">Trusted Certificate Authorities Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesTrustedCertificateAuthoritiesPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesTrustedCertificateAuthoritiesPolicy.json">Link</a></td>
  </tr>
  
  <!-- Virtual Machine Infra Config Policy -->
  <tr>
    <td rowspan="2">Virtual Machine Infra Config Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesVirtualMachineInfraConfigPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesVirtualMachineInfraConfigPolicy.json">Link</a></td>
  </tr>
  
  <!-- Virtual Machine Instance Type Policy -->
  <tr>
    <td rowspan="2">Virtual Machine Instance Type Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateCiscoIntersightKubernetesVirtualMachineInstanceTypePolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/DeleteCiscoIntersightKubernetesVirtualMachineInstanceTypePolicy.json">Link</a></td>
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
    <td>Create and deploy a new cluster on VMware</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_kubernetes/CreateanddeployanewClusteronVMware.json">Link</a></td>
  </tr>
  
  <tr>
    <td>Create and deploy a new cluster on Cisco HyperFlex with VMware</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:large_blue_circle: Planned</td>
    <td></td>
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
    <td><a href="./cisco_intersight_platform/CreateHTTPTarget.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/DeleteHTTPTarget.json">Link</a></td>
  </tr>
  
  <!-- Managed Object -->
  <tr>
    <td>Managed Object</td>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td></td>
  </tr>
  
  <!-- Workflow -->
  <tr>
    <td>Workflow</td>
    <td>Cancel</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_intersight_platform/CancelWorkflow.json">Link</a></td>
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
    <td><a href="./cisco_webex/CreateMembership.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/DeleteMembership.json">Link</a></td>
  </tr>
  
  <!-- Message -->
  <tr>
    <td rowspan="2">Message</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/CreateMessage.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/DeleteMessage.json">Link</a></td>
  </tr>
  
  <!-- Room -->
  <tr>
    <td rowspan="2">Room</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/CreateRoom.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/DeleteRoom.json">Link</a></td>
  </tr>
  
  <!-- Webhook -->
  <tr>
    <td rowspan="2">Webhook</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/CreateWebhook.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./cisco_webex/DeleteWebhook.json">Link</a></td>
  </tr>
</table>
