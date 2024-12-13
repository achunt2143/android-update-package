Updated webos_deploy.sh to have a fallback to regular tar rather than busybox-static. I noticed some devices do NOT like extracting the system with `/tmp/busybox-static` but would with just `tar`
