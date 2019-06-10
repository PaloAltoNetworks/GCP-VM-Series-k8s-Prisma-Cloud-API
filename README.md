# GCP-k8s-Prisma-Cloud-API

This lab will guide through deploying a Terraform template that creates a Kubernetes(k8s) cluster and Palo Alto Networks VM-Series firewall into an existing GCP project. After successfully deploying the terraform template, the following infrastructure will be instantiated:

![k8s-lab](https://user-images.githubusercontent.com/21991161/59230804-42048280-8ba4-11e9-9a05-0fe8227c54ce.jpg)

Then the lab will then guide through the use of the Prisma Public Cloud API Scanning of a K8s Manifest file.  

![k8s-lab](https://user-images.githubusercontent.com/21991161/59230805-42048280-8ba4-11e9-9ff5-54fbbd0c5ed2.jpg)

Finally the lab will deploy the manifest file to the k8s cluster and walk through visibility of both North/South and select East/West traffic flows.  The following diagram shows the deployed pods with the traffic flows:

![k8s-lab](https://user-images.githubusercontent.com/21991161/59230806-42048280-8ba4-11e9-935d-2eef2a3f2d6b.jpg)


# Support Policy
The guide in this directory and accompanied files are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself.
Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.

# License
                                                                              
                                                                              
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at                                                  
                                                                              
  http://www.apache.org/licenses/LICENSE-2.0                           
                                                                              
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.           
