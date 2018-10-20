# Bliss device tree for Nexus 5X (bullhead)

## Build errors

**Help! I'm running into an error where Python fails to find a `userdata.img`!**

This is a known problem. We're working on it. In the meantime, run these two commands after running `. build/envsetup.sh`:

    m -j brillo_update_payload
    m -j otatools

It should probably fix the problem.
