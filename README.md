# MDC
This is common vulnerability management scenario based Questions list using Microsoft Defender for cloud

## 1.Defender for cloud has identified some of your network security groups inbound rules to bee too permissive,inbound rules should not be allow access from ANY or internet ranges. This can potentially enable attackers to target your resources.

Solution :

All network ports should be restricted on NSG group associated to our VM 

Remediation steps:
Edit inbound rules of some of Virtual Machine to restrict access to specific source range.

1. Select a VM to restrict access to.
2. In the "Networking Blade", click the NSG group with overely permissive rules
3. In the "NSG Blade", click on each of the rules that are overly permissive.
4. Improve the rule by applying less permissive source IP ranges
5. Apply the suggested changes and click the save


### TTP involved 

1. Initial Access : External Remote services
                    Trusted Realtionship
2. Execution    
   
