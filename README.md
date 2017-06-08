# st2kitpack
#### StackStorm Skeleton Pack
This pack contains the absolute basics in order to help you create structure for your pack.

/bin exists as a mental pointer to demonstrate your packs are completely configurable. In /bin I put binaries that are part of my custom pack.

You will see commonalities between packs like /rules, /actions, /actions/workflows, /sensors etc.

Requirements.txt is a file that Python uses to build a virtual environment. You can lock packages down to specific versions.

This is work in progress.

__Note__
Since StackStorm 2.x, configuration is now stored in /opt/stackstorm/configs and not in the pack directory.

When a pack is installed, your config.schema.yaml file will generate configurationa and place it in the directory above.
