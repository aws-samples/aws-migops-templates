
# Module: Cleanup and Decommission VMC
## Task 1: VMware specific tools cleanup from migrated EC2 instances
#### Description
Remove VMware specific unwanted tools and services from migrated servers
## Task 2: SDDC Shutdown
#### Description
Decommission all SDDC components
## Task 2: Subtask 1: Delete SDDC Groups
#### Description
Remove all SDDCs from any SDDC groups, then delete the SDDC Groups https://docs.vmware.com/en/VMware-Cloud-on-AWS/services/com.vmware.vmc-aws-networking-security/GUID-CA3054F7-1EDA-420E-A359-83D900E1BCE3.html
## Task 2: Subtask 2: Delete SDDCs
#### Description
Delete all SDDCs https://docs.vmware.com/en/VMware-Cloud-on-AWS/services/com.vmware.vmc-aws-operations/GUID-2396818B-DB45-4754-A7FC-65B284E0CA0D.html
## Task 2: Subtask 3: Revoke permissions
#### Description
Remove employee administrative access to the VMware Cloud Services Platform. https://docs.vmware.com/en/VMware-Cloud-services/services/Using-VMware-Cloud-Services/GUID-84E54AD5-A53F-416C-AEBE-783927CD66C1.html