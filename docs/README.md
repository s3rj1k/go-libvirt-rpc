# Scheduling:
https://github.com/dLobatog/kvmScheduling

# Guest-Agent examples:
http://furalol.blogspot.com/2016/09/kvm-qemu-agent-guest-exec.html
http://furalol.blogspot.com/2016/09/kvm-qemu-agent-guest-file.html

# ToDo:
  - fix error messages in responses (?):
    "virError(Code=49, Domain=18, Message='Storage pool not found: no storage pool with matching name 'images0'')"
  - change naming convention for network -> pf-port105 {SWITCHNUM/PORTNUM}
  - /proc/meminfo -> move away from libvirt functions, parse /proc with go library
  - add JRPC function to remove volume from pool
