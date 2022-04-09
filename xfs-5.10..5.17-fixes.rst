`[GIT PULL] xfs: fixes for 5.17-rc3: <https://lore.kernel.org/r/20220205025606.GX8313@magnolia>`_

- `[PATCHSET 0/1] xfs: tighten GETBMAP input validation <https://lore.kernel.org/r/164316351504.2600306.5900193386929839795.stgit@magnolia>`_
- `[PATCH 2/5] xfs: fallocate() should call file_modified() <https://lore.kernel.org/r/20220131233920.784181-3-david@fromorbit.com>`_

`[GIT PULL] xfs: new code for 5.17: <https://lore.kernel.org/r/20220110220615.GA656707@magnolia>`_

- `[PATCH] xfs: check sb_meta_uuid for dabuf buffer recovery <https://lore.kernel.org/r/20211216001709.3451729-1-david@fromorbit.com>`_
- `[PATCH 1/2] xfs: refactor xfs_file_fsync <https://lore.kernel.org/r/20210111161544.1414409-2-hch@lst.de>`_
- `[PATCH 09/39] xfs: xfs_log_force_lsn isn't passed a LSN <https://lore.kernel.org/r/20210603052240.171998-10-david@fromorbit.com>`_
- `[PATCH v2] xfs: prevent UAF in xfs_log_item_in_current_chkpt <https://lore.kernel.org/r/20211217174500.GI27664@magnolia>`_

`[GIT PULL] xfs: bug fixes for 5.16-rc4: <https://lore.kernel.org/r/20211211172242.GH1218082@magnolia>`_

- `[PATCH 1/2] xfs: remove all COW fork extents when remounting readonly] <https://lore.kernel.org/r/163890214556.3375879.16529642634341350231.stgit@magnolia>`_

`[GIT PULL] xfs: bug fixes for 5.16-rc3: <https://lore.kernel.org/r/20211204235020.GO8467@magnolia>`_

- `[PATCH] xfs: remove incorrect ASSERT in xfs_rename <https://lore.kernel.org/r/bbb4b6d5-744c-11c8-fcda-62777e8d7b19@redhat.com>`_

`[GIT PULL] xfs: new code for 5.16: <https://lore.kernel.org/r/20211102184650.GH24307@magnolia>`_

- `[PATCH] xfs: punch out data fork delalloc blocks on COW writeback failure <https://lore.kernel.org/r/20211021163330.1886516-1-bfoster@redhat.com>`_

`[GIT PULL] xfs: new code for 5.15: <https://lore.kernel.org/r/20210831211847.GC9959@magnolia>`_

- `[PATCH 1/2] xfs: remove support for disabling quota accounting on a mounted file system <https://lore.kernel.org/r/20210420072256.2326268-2-hch@lst.de>`_
- `[PATCH 1/3] mm: Add kvrealloc() <https://lore.kernel.org/r/20210714023440.2608690-2-david@fromorbit.com>`_
- `[PATCH] xfs: only set IOMAP_F_SHARED when providing a srcmap to a write <https://lore.kernel.org/r/20210824003739.GC12640@magnolia>`_
- `[PATCH] xfs: fix I_DONTCACHE <https://lore.kernel.org/r/20210824023208.392670-1-david@fromorbit.com>`_

`[GIT PULL] xfs: bug fixes for 5.14-rc4: <https://lore.kernel.org/r/20210731213740.GN3601443@magnolia>`_

- `[PATCH 09/11] xfs: Enforce attr3 buffer recovery order <https://lore.kernel.org/r/20210727071012.3358033-10-david@fromorbit.com>`_
- `[PATCH] [RFC] xfs: logging the on disk inode LSN can make it go backwards <https://lore.kernel.org/r/20210722110247.3086929-1-david@fromorbit.com>`_

`[GIT PULL] xfs: bug fixes for 5.14-rc2: <https://lore.kernel.org/r/20210718163931.GB22402@magnolia>`_

- `[PATCH] xfs: reset child dir '..' entry when unlinking child <https://lore.kernel.org/r/20210703030233.GD24788@locust>`_

`[GIT PULL] xfs: new code for 5.14: <https://lore.kernel.org/r/20210702201643.GA13765@locust>`_

- `[PATCHSET 0/2] xfs: minor fixes to log recovery problems <https://lore.kernel.org/r/162388773802.3427167.4556309820960423454.stgit@locust>`_
- `[PATCH v2 0/2] xfs: fix buffer use after free on unpin abort <https://lore.kernel.org/r/20210621131644.128177-1-bfoster@redhat.com>`_

`[GIT PULL] xfs: fixes for 5.13-rc4: <https://lore.kernel.org/r/20210529171212.GQ2402049@locust>`_

- `[PATCH 2/6] xfs: bunmapi has unnecessary AG lock ordering issues <https://lore.kernel.org/r/20210527045202.1155628-3-david@fromorbit.com>`_

`[GIT PULL] xfs: fixes for 5.13-rc3: <https://lore.kernel.org/r/20210522041115.GB15971@magnolia>`_

`[GIT PULL] xfs: more new code for 5.13: <https://lore.kernel.org/r/20210507003244.GF8582@magnolia>`_

- `[PATCH] xfs: update superblock counters correctly for !lazysbcount <https://lore.kernel.org/r/20210427011201.4175506-1-hsiangkao@redhat.com>`_
- `[PATCH] xfs: fix xfs_reflink_unshare usage of filemap_write_and_wait_range <https://lore.kernel.org/r/20210429054416.GJ1251862@magnolia>`_

`[GIT PULL] xfs: new code for 5.13: <https://lore.kernel.org/r/20210429170619.GM3122264@magnolia>`_

- `[PATCH v2 0/2] xfs: Skip repetitive warnings about mount options <https://lore.kernel.org/r/20210224214323.394286-1-preichl@redhat.com>`_
- `[PATCH] xfs: ensure xfs_errortag_random_default matches XFS_ERRTAG_MAX <https://lore.kernel.org/r/20210309184205.18675-1-hsiangkao@aol.com>`_

`[GIT PULL] xfs: fixes for 5.12-rc4: <https://lore.kernel.org/r/20210318191436.GL22100@magnolia>`_

- `[PATCH 3/4] xfs: force log and push AIL to clear pinned inodes when aborting mount <https://lore.kernel.org/r/161514875722.698643.971171271199400538.stgit@magnolia>`_

`[GIT PULL] xfs: fixes for 5.12-rc1: <https://lore.kernel.org/r/20210227173725.GE7272@magnolia>`_

- `[PATCH] xfs: don't reuse busy extents on extent trim <https://lore.kernel.org/r/20210222153442.897089-1-bfoster@redhat.com>`_

`[GIT PULL] xfs: new code for 5.12: <https://lore.kernel.org/r/20210219041244.GZ7193@magnolia>`_

- `[PATCH v3] xfs: fix an ABBA deadlock in xfs_rename <https://lore.kernel.org/r/20210111225053.GE1164246@magnolia>`_
- `[PATCH V15 00/16] Bail out if transaction can cause extent count to overflow <https://lore.kernel.org/r/20210126063232.3648053-1-chandanrlinux@gmail.com>`_
- `[RFC] xfs: fix up non-directory creation in SGID directories when umask S_IXGRP <https://lore.kernel.org/r/1647929219-5388-1-git-send-email-xuyang2018.jy@fujitsu.com>`_
- `[PATCH] xfs: set inode size after creating symlink <https://lore.kernel.org/r/20210121151912.4429-1-jeffrey.mitchell@starlab.io>`_
- `[PATCH v2 1/9] xfs: sync lazy sb accounting on quiesce of read-only mounts <https://lore.kernel.org/r/20210121154526.1852176-2-bfoster@redhat.com>`_
- `[PATCH 01/16] xfs: fix chown leaking delalloc quota blocks when fssetxattr fails <https://lore.kernel.org/r/161223139756.491593.10895138838199018804.stgit@magnolia>`_
- `[PATCH] xfs: fix incorrect root dquot corruption error when switching group/project quota types <https://lore.kernel.org/r/20210202193945.GP7193@magnolia>`_
- `[PATCH] xfs: restore shutdown check in mapped write fault path <https://lore.kernel.org/r/20210210170112.172734-1-bfoster@redhat.com>`_
- `[PATCH] xfs: consider shutdown in bmapbt cursor delete assert <https://lore.kernel.org/r/20210211143911.289537-1-bfoster@redhat.com>`_

`[GIT PULL] xfs: new code for 5.11: <https://lore.kernel.org/r/20201218171242.GH6918@magnolia>`_

- `[PATCH 1/3] xfs: detect overflows in bmbt records <https://lore.kernel.org/r/160704437017.736504.13199098088562847416.stgit@magnolia>`_
- `[PATCH] xfs: show the proper user quota options <https://lore.kernel.org/r/1606124332-22100-1-git-send-email-kaixuxia@tencent.com>`_
- `[PATCH] xfs: fix the forward progress assertion in xfs_iwalk_run_callbacks <https://lore.kernel.org/r/20201208171651.GA1943235@magnolia>`_
