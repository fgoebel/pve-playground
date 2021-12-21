# Test Pve cluster -  vagrant with virtualbox

    THIS IS NOT SUITABLE FOR PRODUCTION USE IN ANY WAY!!

In this Repo i gathered resources to play around with a Proxmox VE Cluster

I have to document this some further but here are some first notes:

- The boxes will be attached to your local LAN, see and change variable `public_net_bridge_interface_name`
  in Vagrantfile accordingly
- to change the number of hosts created see variable `num` in Vagrantfile

I basically just created these hosts with vagrant and did most of the stuff by hand...
There might be a Problem with bridges on vbox interfaces ... i never got them to work for VMs ...

