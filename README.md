🖥️ Resources Created
EC2 Instances
LINUX-SERVER
WINDOWS-SERVER
EBS Volumes (5 GB)
LINUX-VOLUME
WINDOWS-VOLUME
⚙️ Implementation Steps
1. Launch EC2 Instances
Launched one Linux EC2 instance
Launched one Windows EC2 instance
2. Create and Attach EBS Volumes
Created 5GB EBS volumes:
LINUX-VOLUME
WINDOWS-VOLUME
Attached volumes to respective EC2 instances
3. Mount Volumes
Linux Server
Mounted volume to:
/data
Created sample files inside /data
Windows Server
Mounted volume as:
E: Drive
Created sample files inside E drive
4. Create Snapshots
Created snapshots from:
LINUX-VOLUME
WINDOWS-VOLUME
5. Create Volumes from Snapshots
Created new volumes:
Linux-shanp-volume
Win-shanp-volume
6. Attach & Verify Snapshot Volumes
Attached new volumes to respective EC2 instances
Mounted them again:
Linux → /data (or new mount point)
Windows → New drive (e.g., F:)
Verified previously created files are present
✅ Result
Successfully created and attached EBS volumes
Mounted volumes in Linux and Windows
Created snapshots and restored volumes
Verified data persistence from snapshot
