> cd .\toppers_osek\
> git init
Initialized empty Git repository in C:/Users/kunren/Desktop/toppers_osek/.git/
> git add README.md
fatal: pathspec 'README.md' did not match any files
> git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'kunren@teach_B.(none)')
> git config --global user.email "kaizen.nagoya@gmail.com"
> git config --global user.name "Dr. Kiyoshi Ogawa"
> git add README.md
fatal: pathspec 'README.md' did not match any files
> git commit -m "first commit"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        config/
        doc/
        include/
        kernel/
        sample/
        sg/
        syslib/
        tools/

nothing added to commit but untracked files present (use "git add" to track)
> git add config/
> git add doc/
> git add include/
> git add kernel/
> git add sample/
> git add sg/
> git add syslib/
> git add tools/
warning: in the working copy of 'tools/h8tiny-renesas/template/sample.pgs', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'tools/h8tiny-renesas/template/sample_cfg.pgs', LF will be replaced by CRLF the next time Git touches it
> git commit -m "first commit"
[master (root-commit) bd83bd7] first commit
 134 files changed, 34493 insertions(+)
 create mode 100644 config/h8tiny-renesas/cpu_config.c
 create mode 100644 config/h8tiny-renesas/cpu_config.h
 create mode 100644 config/h8tiny-renesas/cpu_config_asm.inc
 create mode 100644 config/h8tiny-renesas/cpu_context.h
 create mode 100644 config/h8tiny-renesas/cpu_defs.h
 create mode 100644 config/h8tiny-renesas/cpu_defs.inc
 create mode 100644 config/h8tiny-renesas/cpu_insn.h
 create mode 100644 config/h8tiny-renesas/cpu_support.src
 create mode 100644 config/h8tiny-renesas/h8_36057.h
 create mode 100644 config/h8tiny-renesas/h8_36057.sgt
 create mode 100644 config/h8tiny-renesas/hokuto_bb/sys_config.c
 create mode 100644 config/h8tiny-renesas/hokuto_bb/sys_config.h
 create mode 100644 config/h8tiny-renesas/hokuto_bb/sys_config_asm.inc
 create mode 100644 config/h8tiny-renesas/hokuto_bb/sys_defs.h
 create mode 100644 config/h8tiny-renesas/hokuto_bb/sys_support.src
 create mode 100644 config/h8tiny-renesas/kernel_support.inc
 create mode 100644 config/h8tiny-renesas/start.src
 create mode 100644 config/h8tiny-renesas/tool_config.h
 create mode 100644 config/h8tiny-renesas/tool_defs.h
 create mode 100644 config/m16c-renesas/cpu_config.c
 create mode 100644 config/m16c-renesas/cpu_config.h
 create mode 100644 config/m16c-renesas/cpu_context.h
 create mode 100644 config/m16c-renesas/cpu_defs.h
 create mode 100644 config/m16c-renesas/cpu_insn.h
 create mode 100644 config/m16c-renesas/cpu_support.a30
 create mode 100644 config/m16c-renesas/oaks16_mini/m16c26.sgt
 create mode 100644 config/m16c-renesas/oaks16_mini/sectm16c.inc
 create mode 100644 config/m16c-renesas/oaks16_mini/sfrm16c26.h
 create mode 100644 config/m16c-renesas/oaks16_mini/sys_config.c
 create mode 100644 config/m16c-renesas/oaks16_mini/sys_config.h
 create mode 100644 config/m16c-renesas/oaks16_mini/sys_defs.h
 create mode 100644 config/m16c-renesas/oaks16_mini/sys_support.a30
 create mode 100644 config/m16c-renesas/start.a30
 create mode 100644 config/m16c-renesas/tool_config.h
 create mode 100644 config/m16c-renesas/tool_defs.h
 create mode 100644 config/m32c-renesas/cpu_config.c
 create mode 100644 config/m32c-renesas/cpu_config.h
 create mode 100644 config/m32c-renesas/cpu_context.h
 create mode 100644 config/m32c-renesas/cpu_defs.h
 create mode 100644 config/m32c-renesas/cpu_insn.h
 create mode 100644 config/m32c-renesas/cpu_support.a30
 create mode 100644 config/m32c-renesas/oaks32/m32c83.sgt
 create mode 100644 config/m32c-renesas/oaks32/sectm32c.inc
 create mode 100644 config/m32c-renesas/oaks32/sfrm32c83.h
 create mode 100644 config/m32c-renesas/oaks32/sys_config.c
 create mode 100644 config/m32c-renesas/oaks32/sys_config.h
 create mode 100644 config/m32c-renesas/oaks32/sys_defs.h
 create mode 100644 config/m32c-renesas/oaks32/sys_support.a30
 create mode 100644 config/m32c-renesas/start.a30
 create mode 100644 config/m32c-renesas/tool_config.h
 create mode 100644 config/m32c-renesas/tool_defs.h
 create mode 100644 "doc/TOPPERS_OSEK\343\202\253\343\203\274\343\203\215\343\203\253SG\345\217\226\346\211\261\350\252\254\346\233\270.pdf"
 create mode 100644 "doc/TOPPERS_OSEK\343\202\253\343\203\274\343\203\215\343\203\253\343\202\242\343\203\227\343\203\252\343\202\261\343\203\274\343\202\267\343\203\247\343\203\263\343\203\216\343\203\274\343\203\210.pdf"
 create mode 100644 "doc/TOPPERS_OSEK\343\202\253\343\203\274\343\203\215\343\203\253\343\202\242\343\203\227\343\203\252\343\202\261\343\203\274\343\202\267\343\203\247\343\203\263\343\203\216\343\203\274\343\203\210m16c-renesas.pdf"
 create mode 100644 "doc/TOPPERS_OSEK\343\202\253\343\203\274\343\203\215\343\203\253\343\202\242\343\203\227\343\203\252\343\202\261\343\203\274\343\202\267\343\203\247\343\203\263\343\203\216\343\203\274\343\203\210m32c-renesas.pdf"
 create mode 100644 "doc/TOPPERS_OSEK\343\202\253\343\203\274\343\203\215\343\203\253\345\244\226\351\203\250\344\273\225\346\247\230\346\233\270.pdf"
 create mode 100644 doc/h8tiny.pdf
 create mode 100644 include/kernel.h
 create mode 100644 include/osek.h
 create mode 100644 include/t_config.h
 create mode 100644 include/t_stddef.h
 create mode 100644 kernel/alarm.c
 create mode 100644 kernel/alarm.h
 create mode 100644 kernel/check.h
 create mode 100644 kernel/event.c
 create mode 100644 kernel/interrupt.c
 create mode 100644 kernel/interrupt.h
 create mode 100644 kernel/osctl.c
 create mode 100644 kernel/osek_kernel.h
 create mode 100644 kernel/resource.c
 create mode 100644 kernel/resource.h
 create mode 100644 kernel/task.c
 create mode 100644 kernel/task.h
 create mode 100644 kernel/task_manage.c
 create mode 100644 sample/sample1.c
 create mode 100644 sg/impl_oil/impl_os_bcc1.oil
 create mode 100644 sg/impl_oil/impl_os_bcc2.oil
 create mode 100644 sg/impl_oil/impl_os_ecc1.oil
 create mode 100644 sg/impl_oil/impl_os_ecc2.oil
 create mode 100644 sg/sg.exe
 create mode 100644 syslib/h8tiny-renesas/hw_serial.c
 create mode 100644 syslib/h8tiny-renesas/hw_serial.h
 create mode 100644 syslib/h8tiny-renesas/hw_sys_timer.c
 create mode 100644 syslib/h8tiny-renesas/hw_sys_timer.h
 create mode 100644 syslib/h8tiny-renesas/sample_config.c
 create mode 100644 syslib/h8tiny-renesas/sample_config.h
 create mode 100644 syslib/m16c-renesas/oaks16_mini/hw_serial.c
 create mode 100644 syslib/m16c-renesas/oaks16_mini/hw_serial.h
 create mode 100644 syslib/m16c-renesas/oaks16_mini/hw_sys_timer.c
 create mode 100644 syslib/m16c-renesas/oaks16_mini/hw_sys_timer.h
 create mode 100644 syslib/m16c-renesas/oaks16_mini/sample_config.c
 create mode 100644 syslib/m16c-renesas/oaks16_mini/sample_config.h
 create mode 100644 syslib/m32c-renesas/oaks32/hw_serial.c
 create mode 100644 syslib/m32c-renesas/oaks32/hw_serial.h
 create mode 100644 syslib/m32c-renesas/oaks32/hw_sys_timer.c
 create mode 100644 syslib/m32c-renesas/oaks32/hw_sys_timer.h
 create mode 100644 syslib/m32c-renesas/oaks32/sample_config.c
 create mode 100644 syslib/m32c-renesas/oaks32/sample_config.h
 create mode 100644 syslib/serial.c
 create mode 100644 syslib/serial.h
 create mode 100644 syslib/sys_timer.c
 create mode 100644 syslib/sys_timer.h
 create mode 100644 tools/h8tiny-renesas/configure
 create mode 100644 tools/h8tiny-renesas/libkernel/debug/Debug.hdp
 create mode 100644 tools/h8tiny-renesas/libkernel/defaultsession.hsf
 create mode 100644 tools/h8tiny-renesas/libkernel/libkernel.hwp
 create mode 100644 tools/h8tiny-renesas/libkernel/libkernel.nav
 create mode 100644 tools/h8tiny-renesas/libkernel/libkernel.tps
 create mode 100644 tools/h8tiny-renesas/template/e8.hsf
 create mode 100644 tools/h8tiny-renesas/template/kernel_cfg_wrap.c
 create mode 100644 tools/h8tiny-renesas/template/sample.hwp
 create mode 100644 tools/h8tiny-renesas/template/sample.nav
 create mode 100644 tools/h8tiny-renesas/template/sample.pgs
 create mode 100644 tools/h8tiny-renesas/template/sample.tps
 create mode 100644 tools/h8tiny-renesas/template/sample1.oil
 create mode 100644 tools/h8tiny-renesas/template/sample_cfg.hwp
 create mode 100644 tools/h8tiny-renesas/template/sample_cfg.nav
 create mode 100644 tools/h8tiny-renesas/template/sample_cfg.pgs
 create mode 100644 tools/h8tiny-renesas/template/sample_cfg.tps
 create mode 100644 tools/h8tiny-renesas/template/sample_cfg_defaultsession.hsf
 create mode 100644 tools/h8tiny-renesas/template/sample_defaultsession.hsf
 create mode 100644 tools/h8tiny-renesas/toppers_osek.Hbp
 create mode 100644 tools/h8tiny-renesas/toppers_osek.hws
 create mode 100644 tools/h8tiny-renesas/toppers_osek.tws
 create mode 100644 tools/m16c-renesas/oaks16_mini/kernel_cfg.c
 create mode 100644 tools/m16c-renesas/oaks16_mini/kernel_id.h
 create mode 100644 tools/m16c-renesas/oaks16_mini/sample1.oil
 create mode 100644 tools/m16c-renesas/oaks16_mini/toppers_osek_oaks16mini.tmi
 create mode 100644 tools/m16c-renesas/oaks16_mini/toppers_osek_oaks16mini.tmk
 create mode 100644 tools/m32c-renesas/oaks32/kernel_cfg.c
 create mode 100644 tools/m32c-renesas/oaks32/kernel_id.h
 create mode 100644 tools/m32c-renesas/oaks32/sample1.oil
 create mode 100644 tools/m32c-renesas/oaks32/toppers_osek_oaks32.tmi
 create mode 100644 tools/m32c-renesas/oaks32/toppers_osek_oaks32.tmk
> git branch -M main
 git remote add origin https://github.com/nagoyakaizen-star/OSEK.git
> git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 160, done.
Counting objects: 100% (160/160), done.
Delta compression using up to 12 threads
Compressing objects: 100% (152/152), done.
Writing objects: 100% (160/160), 2.56 MiB | 1.88 MiB/s, done.
Total 160 (delta 71), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (71/71), done.
To https://github.com/nagoyakaizen-star/OSEK.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

-----
