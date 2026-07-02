# cloud-1-
Automated deployment of Inception



Notes:
1- I am not using group_vars since we have only 1 group in inventory (likely 1 machine) we can add complexity by adding more groups (db, nginx, wp) then we may use group_vars.

also use host_vars only if a server(machine) needs a specific config/vars

we will need vault.yml to store sensitive credentials