+--------------------------------------------------------------------------+
<div class="pageheader">

<span class="pagetitle"> SmartOS Documentation : Patching the latest
QEMU </span>

</div>

<div class="pagesubheading">

This page last changed on Jun 25, 2012 by
<font color="#0050B2">nahamu</font>.

</div>

This is a page for the people who are working on patch sets that get
recent versions of QEMU working well on illumos in general, and SmartOS
in particular

<div>

- [Upstream QEMU 1.1.0](#PatchingthelatestQEMU-UpstreamQEMU1.1.0)
- [Things that need
    patching](#PatchingthelatestQEMU-Thingsthatneedpatching)
- [References](#PatchingthelatestQEMU-References)

</div>

Upstream QEMU 1.1.0
=======================

- [v1.1.0 tagged on June 1,
    2012](http://git.qemu.org/?p=qemu.git;a=commit;h=78260a5f085d34e4ae4
6e42bdc010dfcd6f6cc31)
- Repo: <git://git.qemu.org/qemu.git>

Things that need patching
=============================

- add in Illumos KVM headers
- VNIC support
- Multitick timer
- CTF data for debugging
- Spice listening on a UNIX socket
- ioctl refactor

References
==============

- Lee's Repo
    -   Currently about a month behind the upstream QEMU tree.
    -   Repo: <https://github.com/essele/illumos-qemu-port>
- Nahum's Repo
    -   One Commit ahead of Lee's
    -   Repo: <https://github.com/nshalman/illumos-qemu-port>
- Upstream QEMU
    -   Repo: <git://git.qemu.org/qemu.git>
- Joyent's Repo based on 0.14
    -   Repo: <https://github.com/joyent/illumos-kvm-cmd>
    -   [Playing the Joyent illumos-kvm-cmd git history on top of the
        upstream qemu-kvm
        repo](http://www.listbox.com/member/archive/184463/2012/03/searc
h/c2hhbG1hbg/sort/time_rev/page/1/entry/6:15/20120322112939:D2754100-743
3-11E1-971D-BCC2C88DEAFE/)
+--------------------------------------------------------------------------+

  ----------------------------------------------------------------------------------
  ![](images/border/spacer.gif){width="1" height="1"}
  <font color="grey">Document generated by Confluence on Jul 07, 2019 00:15</font>
  ----------------------------------------------------------------------------------

