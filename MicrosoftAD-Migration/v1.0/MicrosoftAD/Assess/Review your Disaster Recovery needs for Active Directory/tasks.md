
# Module: Review your Disaster Recovery needs for Active Directory
## Task 1: Replicating the entire environment, including the AD server(s)
#### Description
In this approach it is recommended to launch the drill or recovery AD servers first, wait until it's up and running and then launch the other drill or recovery instances, to make sure the AD servers are ready to authenticate them.
## Task 2: Leaving the AD server(s) in the Source environment
#### Description
In this approach, the drill or recovery instances will communicate back to the AD server in the source environment and will take the source server's place in the AD automatically.
In this case, it is important to conduct any drills using an isolated subnet in the AWS cloud, so to avoid having the drill or recovery instances communicate into the source AD server outside of a recovery.